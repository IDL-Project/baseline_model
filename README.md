# Multimodal Approach to Subtitle Generation - 11785
### Baseline model pieces

* [Bi_LSTM Model](https://github.com/IDL-Project/baseline_model/blob/main/Bi_LSTM_model.ipynb) (An earlyphoneme classification experiment)
* [CNN_LSTM Model](https://github.com/IDL-Project/baseline_model/blob/main/CNN_LSTM_model.ipynb) (Improvement to the Bi_LSTM phoneme classifier with a CNN as the first layer)
* [ResNet34 Model](https://github.com/IDL-Project/baseline_model/blob/main/Resnet34.ipynb) (Image feature extractor meant to extract features from video frames)
* [KNNW audio dataset class](https://github.com/IDL-Project/baseline_model/blob/main/KNNW_Audio_Dataset_Class.ipynb) (Dataset class for processing KNNW data to the model)

### Tested models
* [LAS_Model](https://github.com/IDL-Project/baseline_model/blob/main/LAS_Model.ipynb) (Implementation of the Listen Attend Spell Model for text to speech transcription)
* [KNNW_Audio2Text_From_Scratch](https://github.com/IDL-Project/baseline_model/blob/main/KNNW_Audio2Text_From_Scratch.ipynb) (LAS Model applied to KNNW data from scratch)
* [KNNW_Audio2Text_Transfer Learning](https://github.com/IDL-Project/baseline_model/blob/main/KNNW_Audio2Text_Transfer_Learning.ipynb) (LAS Model transfer-learned from HW4P2 dataset to KNNW dataset)
