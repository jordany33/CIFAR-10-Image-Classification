# CIFAR-10 Image Classification

## Overview
This project involves implementing and evaluating various classification methods on the CIFAR-10 dataset. The dataset consists of 60,000 32x32 color images across 10 different classes. Our goal was to compare the performance of different classifiers and gain insights into their strengths and weaknesses.

## Classification Methods
We investigated the following classifiers:
- k-Nearest Neighbors (kNN)
- Logistic Regression
- Random Forest
- Neural Networks (MLP and CNN)

## Project Structure
- **data/**: Contains the CIFAR-10 dataset.
- **notebooks/**: Jupyter notebooks with code implementations.
  - `CIFAR-10_logistic_Classifier_Implementation.ipynb`
  - `CIFAR-10_Neural_Network.ipynb`
  - `CIFAR-10_Random_Forest.ipynb`
  - `CIFAR-10_report.ipynb`
- **results/**: Contains graphs and results generated from the models.
- **README.md**: Project overview and instructions.

## Setup
1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/CIFAR-10-Image-Classification.git
   cd CIFAR-10-Image-Classification
2. Install the required packages:
   ```bash
   pip install -r requirements.txt

## Usage
Run the Jupyter notebooks to see the implementation of each classifier and the corresponding results.

## Results
The results of our experiments showed that convolutional neural networks (CNNs) achieved the highest accuracy, followed by random forests. We also observed that kNN and logistic regression performed well under certain hyperparameter settings.

#Insights 
- Classifiers struggled to distinguish between different animal classes.
- Data preprocessing and hyperparameter tuning significantly impacted model performance.
- Practical applications include object recognition in autonomous vehicles, security and surveillance, and medical imaging analysis.

## Contributors
- Jordan Yee: Implemented kNN and logistic regression classifiers.
- Travis Moore: Designed neural network structures for MLP and CNN.
 Shifeng Hong: Implemented random forest classifier and generated graphs.

## License
This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.
