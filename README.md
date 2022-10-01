# CropCare
It is a web application that that will help farmers to detect crop
disease just by uploading an image of the leaf and also read about its cure, causes, prevention and best practices.

Developed a plant disease recognition model based upon leaf image classification by using deep convolutional networks.
The model is able to recognize 38 types of plant diseases with the ability to distinguish plant leaves from their surroundings.

## Leaf Image Classification

This process for building a model which can detect the disease assocaited with the leaf image. The key points to be followed are:

1. Data gathering

   The dataset taken was **"New Plant Diseases Dataset"**. It can be downloaded through the link "https://www.kaggle.com/vipoooool/new-plant-diseases-dataset".
   
2. Model building

   - Pytorch was used for building the model suing Transfer learning resnet34 Architecture

3. Training

   The model was trained by using variants of above layers mentioned in model building and by varying hyperparameters. The best model was able to achieve 98.42% of test accuracy.

4. Testing

   The model was tested on total 17572 images of 38 classes.<br/>
   
   
