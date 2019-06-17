# Face-recognition-
      Automated attendance system using Google Inception v3 architecture

# Data preparation
      Data for training is created using 'data_creator.py' and store it in two classes using glob library

# Data plotting
      Data gathered is then plotted using matplotlib

# Model Customization
      Loading the inception model without the input layer and customize for our needs
      Set activation as "sigmoid" if it is a binary classification else set as "softmax" if it is a multi- class classification
      
# Data Augmentation
      Image data generator to generate new data by flipping the data to prevent the model to not overfit
      
# Transfer Learning
      Training the model with the images and save it in a model "filename.model"
      
# prediction
      Using opencv to detect the face and use it as real time test data and pass the data to 'classifier' and with the predicted output mark the attendance using excel gspread library
