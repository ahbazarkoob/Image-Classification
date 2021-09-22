# Image-Classification

In this project, I build a model to identity the type of ball.

I used the dataset from Kaggle-"Balls - Image Classification". The dataset contains mages of various types of balls.
There are 24 different types (classes) . train set includes 2860 files in 24 subdirectories. 
I started the project by loading the Dataset from Kaggle, in order to load dataset from Kaggle to google colab notebook we first need to install Kaggle,
create new directory, copy files in the directory, upload the file kaggle.json, 
use the command "! chmod 600 ~/.kaggle/kaggle.json'in order to read and write files from the directory,  download the dataset, and extract the zip file.
After that we need to import libraries for dataset reading and CNN (convolutional neural network) model creation. The libraries used are pandas, numpy,
matplotlib, PIL, os and cv2. However, I imported the libraries in the cell in which they were required.
Now, I set the path to read the data in the file (describe, display images).
After that, I set the path of training, testing, and validation directories. 
After that, I started with Data Visualization (plot pie-chart, bar-graph).
After that, I preprocessed data (train, test, validation), which includes, rescaling, the size (height, width) of images.
Then, I build my custom CNN (convolutional neural networks) architecture, which will include different (CNN, dropout, polling, flatten, dense) layers.
Once the model is completed i checked the summary of model before we start our training process.
Then, I compiled the custom CNN (convolutional neural networks) model. 
After that, I trained the model.
After that, I predicted the model.
After that, I tested the model on testing data.
