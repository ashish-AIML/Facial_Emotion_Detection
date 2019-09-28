# Facial_Emotion_Detection
Facial Emotion Detection presented in ICML
Keras


If you want to train this model or train after making changes to the model, use python kerasmodel.py --mode train.

If you want to view the predictions without training again, you can download my pre-trained model (model.h5) from here and then run python kerasmodel.py --mode display.


pre-trained model: https://drive.google.com/file/d/1FUn0XNOzf-nQV7QjbBPA6-8GLoHNNgv-/view

dataset: https://www.kaggle.com/deadskull7/fer2013

Data must be in the format:
  Divide .csv file into 2 files:
     1. train.csv
     2.test.csv
From fer2013.csv, cut cells from usage:PublicTest and PrivateTest and paste it in test.csv

Create train folder:
    train.csv
    
Create test folder:
   test.csv
