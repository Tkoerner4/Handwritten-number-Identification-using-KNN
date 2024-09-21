# Handwritten-number-Identification-using-KNN
This project features an implementation of the KNN (K- Nearest Neighbors) algorithm for classifying handwritten digits. It includes Principal Component Analysis (PCA) to reduce feature dimensionality, enhancing both the speed and accuracy of the KNN classification. The project also focuses on hyperparameter tuning to optimize preformance.

# Dataset
These are the files used for training and test data

Validation data:

[Download File](validationData.txt)

Training Data:

[Download File](train.txt)

Results of guesses:

[Download File](hw1_Miner2_2.txt)

Test Data

[Download File](test.txt)

# Installation
1. Clone the repository:
  ```git clone https://github.com/Tkoerner4/Handwritten-number-Identification-using-KNN.git```

3. Navigate to the project directory:
  ```cd Handwritten-number-Identification-using-KNN```

4. Install the required dependencies:
  ```pip install numpy pandas scikit-learn matplotlib```

# Usage
Open knn.ipynb

# Results

For k I've tried: 17, 35, 51,65,79,101,109,155,255,3, 5, 7,  13, 15,21,251
The way that I tuned my hyperparameters was setting up the algorithim to run at first with smaller sizes of training data so that runtimes would not be excessive, that way I could constantly improve upon any inefficiencies. I used cross validation as a method of using different validation and training sets, with each partition being run one time for every possible combination. The highest averages of the scores was what I used to determine optimal hyperparameters.
For methods of getting the distance I tried :Euclidean,Cosine,L1 Norm
For pca dimensions I've tried: 30,45,50, 100, 150, 200, 350, 400, 550

