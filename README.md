# Fashion MNIST Image Classification

## About the Dataset

https://www.kaggle.com/zalando-research/fashionmnist

Fashion-MNIST is a dataset of Zalando's article images—consisting of a training set of 60,000 examples and a test set of 10,000 examples. 
Each example is a 28x28 grayscale image, associated with a label from 10 classes.Each image is 28 pixels in height and 28 pixels in width,
for a total of 784 pixels in total. Each pixel has a single pixel-value associated with it, indicating the lightness or darkness of that 
pixel, with higher numbers meaning darker. This pixel-value is an integer between 0 and 255.

## Evaluation

In this repo, I have trained 4 models whose summary and results are as follows:

* **CNN Model 1**: *A simple CNN model with 1 convolutional layer, 1 max-pooling layer, 2 dense layers and 1 dropout layer.*
  - Accuracy : 92.28%
  - Loss and Accuracy Plots
  
  ![alt-text](https://github.com/CheshtaK/Fashion-MNIST/blob/master/pngs/model_1_plots.PNG)
  
 
* **CNN Model 2**: *A CNN model with 3 convolutional layers, 2 max-pooling layer, 2 dense layers and 4 dropout layers.*
  - Accuracy : 92.81%
  - Loss and Accuracy Plots
  
  ![alt-text](https://github.com/CheshtaK/Fashion-MNIST/blob/master/pngs/model_2_plots.PNG)
  

* **CNN Model 3**: *A deeper CNN model with 4 convolutional layers, 2 max-pooling layer, 3 dense layers, 5 dropout layers and 6 batch normalization layers.*
  - Accuracy : 93.97%
  - Loss and Accuracy Plots
  
  ![alt-text](https://github.com/CheshtaK/Fashion-MNIST/blob/master/pngs/model_3_plots.PNG)
  
  
 * **VGG-19**: *Transfer Learning with pre-trained VGG19 model*
  - Accuracy : 71.04%
  - Loss and Accuracy Plots
  
  ![alt-text](https://github.com/CheshtaK/Fashion-MNIST/blob/master/pngs/model_4_plots.PNG)
