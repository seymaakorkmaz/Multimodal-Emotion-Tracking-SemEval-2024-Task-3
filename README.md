# Multimodal Emotion Tracking From Videos Using Image, Audio and Text - SemEval 2024 Task-3
 
Our **final project**, __"Multimodal Emotion Tracking From Videos Using Image, Audio and Text"__, involves predicting emotional states in video, audio and text modes. The aim of our project is to examine the effect of different types of data such as video, text and audio on emotion prediction. Learn more about [competition](https://nustm.github.io/SemEval-2024_ECAC/).

## Dataset
Within the scope of the project, two different data sets were studied:
- [SemEval Dataset](https://drive.google.com/drive/folders/1TIRBiL8z4ZnoxtuKM8pnjtm2BxB5mS4Y)
- [IEMOCAP Dataset](https://drive.google.com/file/d/1zWCN2oMdibFkOkgwMG2m02uZmSmynw8c/view)

Since more consistent results were obtained on the IEMOCAP data set, the studies on this data set were shared. You can review the [report](Report.pdf) file to examine results of the work done on the SemEval dataset.

## Feature Extraction

- BERT and BiLSM were used to extract text features. You can see the text feature extraction processes in the [IEMOCAP_BERT.ipynb](IEMOCAP_BERT.ipynb) file.
- OpenSMILE was used to extract audio features. You can see the text feature extraction processes in the [OpenSMILE_Feature_Extraction.ipynb](OpenSMILE_Feature_Extraction.ipynb) file.
- 3D-CNN was used to extract video features. You can see the text feature extraction processes in the [3D_CNN_Feature_Extraction.ipynb](3D_CNN_Feature_Extraction.ipynb) file.

  ## Models
  
Since the most successful results among single models were obtained in the text model, and among multiple models, the most successful results were obtained in the text-audio-video model, these studies are shared. You can review the [report](Report.pdf) file to examine results of other models.

### Text Model
- [IEMOCAP_BERT.ipynb](IEMOCAP_BERT.ipynb) : Text features extracted with BERT were classified with the BERT classifier.

### Text - Audio - Video Model 
- [IEMOCAP_Text_Audio_Video.ipynb](IEMOCAP_Text_Audio_Video.ipynb) : Text features extracted with BERT, audio features extracted with OpenSMILE and video features extracted with 3D-CNN were concatenated and classified with the XGBoost classifier.

## Macro Average F1-Scores

| Model        | Macro Avg. F1-Score               |
|------------------|----------------------------|
| Text Model     | 58% |
| Text - Audio - Video  Model | 53%|

  
