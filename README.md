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


  
