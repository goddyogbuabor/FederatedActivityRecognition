# FederatedActivityRecognition
Federated Algorithms for Activity Recogntion


This project contain 5 files.
The “Readme.mb” file is for instructions on how to train the algorithms.
The FeatureExtraction.ipynb is used for feature extraction. To train algorithm, features needs to be extracted from the raw sensor data. Use this file to extract feature from each of the dataset. 
The GlobalTrain.ipynb is used for global model training. Different machine learning algorithms were trained using “Globaltrain” dataset. 
The UseCase1.ipynb is used for the first  scenario where the participants were grouped into four. The corresponding dataset is “UseCase1”. 
The UseCase2.ipynb is used for the second  scenario where  each participants  is regarded as a client. The corresponding dataset is “UseCase2”. 
For each experiment, import the corresponding dataset, the globaltrain dataset and the TestData. Change the directory to suit you and run “FeatureExtraction.ipynb” to extract features. The extracted features are then used as input vector for the algorithms training. 
