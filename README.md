# AIapplicationSystem
## week 4
https://github.com/IAMJASURBEK/AIapplicationSystem/blob/main/week%234.ipynb

### Stage 1
First we prepared libraries and the variables consist of all sample data which will be used for the demonstration



### Stage 2
we setup a function which will be used as our neuron.
It will feature characteristics like the quantity of inputs, layers, and neurons in each layer.

### Stage 3

We just finished creating all the needed function to do the training process.

### Last stage 
we created a loop to keep training the model until we reached the desried result.


## week 5
https://github.com/IAMJASURBEK/AIapplicationSystem/blob/main/week5.ipynb

### Stage 1
 we learnt about tensorflow basic including the TensorFlow session, placeholder, mathematical operators. Also, we learnt how to visualize the result on tensorboard

we installed TensorFlow 1.15.5
### Stage 2
In the next section, we used a variable, constant, and placeholder to work with numbers

Variables
Variable is trainable, after being constructed, we can use the assign method to add value. Default value is None.
Constants
Constant is NOT trainable, and has to be put initial value (can't be null).
Placeholder
Place holder is used to store value, but the value can be given in the later process.
### Stage 3
We showed the graph and histogram on the tensorboard

## week 6
Session 1:
https://github.com/IAMJASURBEK/AIapplicationSystem/blob/main/Week%236_1.ipynb
### Stage 1
In this section, we saw how to make a Linear Regression using TensorFlow and used TensorBoard to show the result.

After we successfully make the linear regression, we proceeded with one classification example which is MNIST dataset classification. MNIST is dataset consist of handwritten digit images.
### Stage 2
Next we created the hyperparameters. Hyperparameter consist of constant value which will be used during the whole session. In this case, we are going to need the parameter for learning rate and epochs, then we created a sample dataset with random numbers to be shown on the graph later
### Stage 3
Once the data is created, we showed it using matplotlib libraries using the code
After that, we wanted to fit noisy dataset to our linear regression model,then made the placeholders and variables

The linear regression formula that we use is quite simple : Y= WX + B
Everything is settled and finished, we can use tensorboard to show the scalar summary result
### Stage 4
MNIST Classification
We successfully created a linear regression model. Next we  created a new model that is able to make another prediction.

This time, we used dataset provided by tensorflow which is MNIST dataset.

The MNIST dataset consist of handwritten images of number 0-9. Since we precicted images, we did not use Linear Regression. Instead, we perdicted images based on its pixels' value.
MNIST dataset is split into 3 different types of data, which are training, validation, and testing.

Training
The dataset which will be used to teach/train the model in order to make prediction.
Validation
The dataset which will be used to understand the model's performance through different types and hyperparameters.
Testing
The dataset which will be used to approximate the model's performance on real cases after being trained completely.


Session 2:
https://github.com/IAMJASURBEK/AIapplicationSystem/blob/main/week%236_session2.ipynb

### Stage 1
 we learnt about imge denoising using neural network

In real life cases, it's hard to get clean and such good dataset like digit MNIST. So for the next section we  created  noisy images and convert it into a much cleaner image





## week 7



Week 7 folder above includes two session files
https://github.com/IAMJASURBEK/AIapplicationSystem/tree/main/week7

 In this section we are made a neural network model out of torch and torchvision API. And with the help of Convolutional Neural Network we  made a new accurate model that later be used for prediction.

What is Convolutional Neural Network (CNN)?
CNN is pretty similar to Neural Network, they consist of neurons that have weight and biases and is used to make preduction. The difference is that CNN is used for image prediction by looking at the pixel and modify the value to finally make the prediction.

There are some popular popular terms in CNN, which are :

Convolution Layer
The first layer in CNN that transforms the input image to extract features/part of the image that is considered important. Convolutional Layer works with the help of kernel, stride, padding, etc.
Kernel
Kernel is a small matrix (smaller than the input image) that will move accross the image to extract the features from the input image.
Stride
Stride takes control of how far the kernel will move accross the image, it uses pixel as the unit. If the stride is very large, the result picture would not be accurate.
### Stage 1
We installed needed dataset and libraries in order to make CNN model
downloaded the CIFAR10 dataset consist of different object images. This dataset have 10 different classes with 6000 images per class with the size of 32x32 pixels.
### Stage 2
 we need to install 'requests' which is a libraries from GitHub. Requests allows us to import any API from any users on GitHub.
 then, we can import torch and some other libraries to help us create the neural network model for the next step.
 ### Stage 3
 Our CNN Model is finally done, continue by initializing tehe moedl and then train the model
### Last stage
The CNN Model training process is completed and done. We can see the final result of the training accuracy and validation accuracy.





12192063
University Honor Code

" 나는 정직하게 시험에 응할 것을 서약합니다."

"By signing this pledge, I promise to adhere to exam requirements and

maintain the highest level of ethical principles during the exam period."
