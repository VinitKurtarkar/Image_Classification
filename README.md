# Image Classification System
<br>
<br>
Built a simple image classification system that distinguishes between Cats and Dogs. Used Kaggle dataset for the model but unable to attach it due to the size of the folder. The libraries which i used in the project are TensorFlow and Keras. Used Keras generators for training and for the purpose of validation in the model and normalized the model. Initialized a CNN Model with Sequential API and defined it  with 3 Layers 32, 64 and 128.
<br>
<br>
Compiled the data and plotted some graph to see if there was any overfitting or loss of validation data and since there was later applied BatchNormalization and Dropout which reduced the overfitting and loss of validation as you can see in Second Graph marked as NEW. After that wrote some small cade to take any image in "JPG" Format, resized it to (256,256) and gave the output. 
