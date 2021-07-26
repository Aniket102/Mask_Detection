To use the model download the Face_Mask_Detection.ipynb file whose hyperparameter has been tuned using keras optimizer which is in HyperParameter_tuning.ipynb
 TABLE OF CONTENT  Face_Mask_Detection
  Introduction
  Fetch datasets
  Load Dataset
  Import library
  Data Augmentation
  Model Building
  Model Fitting
  Training Loss & Accuracy Visualization
  Find prediction

Training Accuracy of 93.17%  
Validation Accuracy of 90.5%
Test Accuracy 92%

The model is Trained on CNN with two convolution layer and two dense layer
To appropiately choose the filters and neurons in dense layer keras tuner has been used whose experimentation output is saved in folder output3
To prevent overfitting of data seeing the validation accuracy in tuning phase dropout has been implemeted in the model for enhanced accuracy and image augmentation is used


You can get the complete Dataset here
https://www.kaggle.com/prithwirajmitra/covid-face-mask-detection-dataset

The model can be implemented on video with the file Mask Detection On video  using opencv and haaracascade classifier with the above trained model 

