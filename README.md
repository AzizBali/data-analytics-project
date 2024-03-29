# FIFA 21 Data Analytics & Visualization + Face Recognition Model of Football Players (8 classes)

### Authors
- **ALEYA Mohamed**
- **RIAHI Alaa**
- **BALI Aziz**

## PART 1: FIFA 21 Data Analytics & Visualization
In this part of the project, we used the database of FIFA 21 players to check for correlations between different stats and draw conclusions/insights.

## PART 2: Face Recognition Model of Football Players (8 classes)
The notebook code unzips the dataset (fifa_player_dataset.zip) and splits it into the training and validation sets based on the given ratio (0.8 t / 0.2 v). Transfer Learning has been implemented with the MobileNetV2 model and imagenet weights. The pre-trained model consists of 155 layers and the whole layers of the pretrained model is retrained to get a better accuracy. Image Augmentation has been implemented to avoid the overfitting of the model. The model has been trained for the 30 epochs and the Validation Accuracy of 97% has been yielded.

Download the "Weights Face Recognitions.h5" file and add it to the same directory: https://www.file.io/download/oT5QYX0uKg7m
Note: This file can be loaded with the Tensorflow in case of without training the model again to obtain the new weights.

Dataset: https://www.kaggle.com/azizbali/football-players-faces-dataset
