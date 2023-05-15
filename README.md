# Dogs-vs-Cats-Image-Classification-using-Convolutional-Neural-Networks-CNNs-
This project is an implementation of a Convolutional Neural Network (CNN) for classifying images of dogs and cats. 
The CNN is trained on a dataset of 25,000 images (12,500 of dogs and 12,500 of cats) and is able to achieve an accuracy of around 80%.

## Getting Started
**Prerequisites**
- This project requires Python 3.7 or higher and the following Python libraries:

- tensorflow
- keras
- matplotlib
- Installing
- To install the required libraries, run the following command:

## Copy code<br>
```
pip install tensorflow keras matplotlib
```
## Downloading the Dataset
The dataset used in this project can be downloaded from Kaggle. You will need to sign up for a Kaggle account and accept the competition rules to download the dataset. Once downloaded, extract the files to a directory of your choice.

## Training the Model
To train the CNN, run the following command:

**Copy code**<br>
```
python cnn.py
```
This will train the CNN on the dataset for 5 epochs and save the trained model to a file called model.h5.

## Evaluating the Model
To evaluate the performance of the trained model on the test set, run the following command:

**Copy code**<br>
```
python evaluate.py
```
This will load the trained model from the model.h5 file and evaluate its performance on the test set.

## Authors
Kundeshwar V. Pundalik
## License
This project is licensed under the MIT License - see the LICENSE.md file for details.
