# SMAI Assignment 5 README

This README provides an overview of the completed tasks for the Statistical Methods in Artificial Intelligence (SMAI) Assignment 5.

## 2. Kernel Density Estimation

### 2.1 Question 1

#### 2.2 Task-1 : (20)
- Implemented Kernel Density Estimation (KDE) with the following functions:
  - Allows selection from box, gaussian, and triangular kernels
  - Fits data
  - Selects appropriate bandwidth using the pseudo-likelihood method
  - Evaluates the density given an input x
  - Visualizes the data and the estimated pdf for 1-D or 2-D input datasets
- The KDE supports n-dimensional input

#### 2.3 Task-2 : (80)
- Used the implemented KDE to estimate appropriate horizontal and vertical thresholds for the bounding box problem from Assignment 2
- Experimented with different bandwidths for 4 chosen images from the dataset
- Visualized the density estimated and thresholded document for each hyperparameter setting per image (12 figures for each hyperparameter configuration)
- Compared the generated output from the KDE with the best hyperparameter configuration with the output obtained from Assignment 2 Question 4.2 for the following images:
  - 29.jpg
  - 68.jpg
  - 145.jpg
  - 201.jpg
  - 232.jpg
  - 250.jpg
- Visualized the output images side by side for each test image

## 3. Hidden Markov Models

### 3.4 Task-3

#### 3.4.1 Dataset
- Used the provided `rolls.npy` file containing data from 50,000 observed rolls at the casino

#### 3.4.2 Part 1 (20)
1. Trained an HMM model with a 50% train and validation split (sequential split)
2. Experimented with different emission probabilities for the loaded die and reported the best model using the validation split
3. Found the most likely sequence of switching between the fair and loaded die
4. Plotted the generated states
5. Identified the corresponding problem in Hidden Markov Models

#### 3.4.3 Part 2 (20)
1. Estimated how often the casino is switching out the fair die for the loaded one and vice versa
2. Identified the corresponding problem in Hidden Markov Models

#### 3.4.4 Part 3 (20)
1. Analyzed how the loaded die is biased
2. Identified the corresponding problem in Hidden Markov Models

### 3.5 Task-4 : (30)
- Used the provided `runs.npy` file containing a sequence of length 30000 representing the runs scored by the players for each ball
1. Found the optimal transition, emission, and start probability for the HMM model
2. Chose the best HMM based on the data and model information to predict who played the first and the last ball

The code for each question can be found in the Jupyter Notebook files `1.ipynb` and `2.ipynb`, respectively.
