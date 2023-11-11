# Research_project_ELEC5305
Music Genre Classification with Deep Learning Methods

DATA

For a project, I compared four methods to classify music genres from the GTZAN dataset. The main purpose of this project is to develop an efficient deep-learning music genre classification system to classify music genres and try to achieve the highest accuracy.

HOW TO RUN THIS CODE?

To run this code, you need to upload Jupiter Notebook to the Google Colab and upload the "Kaggle.json" file. Then, click the run button. The first run will create a Kaggle folder in the Colab root directory, and the program will say that it cannot find the "Kaggle.json" file. Then, click the run button again, and the program can properly download the dataset and start to train all methods one by one. 

METHODS OVERVIEW

The overview of the four methods is that methods 1 and 2 will use the extracted audio features as the training data to train their models. Method 3 will first convert the audio file to a spectrogram and then train the model on those spectrogram images to classify music genres. Method 4 used the extracted 40 MFCC audio features and shape as a 3-dimensional matrix [x,x,x] as the training dataset to train CNN models.

The method 2 has the best performance. Here is the confusion matrix of method 2:

<img width="284" alt="image" src="https://github.com/GhostDragon124/Research_project_ELEC5305/assets/47167674/1ace7cd8-9938-44a4-8bb6-634e50e9abf7">
