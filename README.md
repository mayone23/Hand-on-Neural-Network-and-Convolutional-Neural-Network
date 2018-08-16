Hand on Neural-Network using Pyhton.

	We are living in a world with Python and Anaconda..... Ha ha ha.... Jokes apart.

	Coding from scratch for those who are new to Neural Network like me.. :) :p
	
	This repo includes the basic code to use python with tensorflow/keras for Neural Network implementation.

	The codes or the methods are implemented using CS231n course of Standford University.
	
Network Layer Parameters:
	
	1. Input Layer: It depends upon the shape of training data. The number of feature column is equal to the 
	number of neurons in that layer. To provide flexibility in the network or to overcome the network from 
	being dead due to zero inputs in between, the bias term is used.
	
	2. Output Layer: It depends upon the type of model configuration.If our model is regression model then the
	output layer will have only one output node and if our model is based on classification then the number of 
	output layer is the number of classes or number of different labels. So, it is completely depends upon the
	type of model we have chosen.
	
	3. Hidden Layer: This is the most important portion of the Neural Network. There is no hard and fast rules 
	in choosing number of neurons and number of hidden layers. But, if we follow some of the basic tricks or 
	techniques then the modle accuracy can be very much affected. So, here is the techniques/tricks:
	
	If our dataset is linearly seperable then twe don't need any hidden layers and we don't need any Neural 
	Network at all to resolve the task. But if the dataset is not linearly seperable then we do need a Neural 
	Network with proper configuration. Therefore, the optimal size of hidden layer is in between the input 
	layer and output layer. 

Transfer Learning:

	When the developed machine learing model is used to develop some other machine learning models, the new model
	that learnt from the first model is known as the transfer learning.
	
	It is a well known approach in deep learning where the pre-trained machine learninig models are used as the 
	ignitition point or the starting point for the new machine learning models.
	
	For eg. in Convolution Neural Network sometime we used to choose the pre-trained models such as ImageNet, 
	ResNet etc. for our new model. So, this comes under transfer learning.
	
	It is a short cut to get better performance or in saving time. But there is always the pros and cons of uisng 
	pre-trained model or so called transfer learning. As mentioned in above line about its one of the pros. There
	are some contraints such as taking arbitary Convulational layer out of the pre-trained machine learning models.
	
https://machinelearningmastery.com/transfer-learning-for-deep-learning/

	For further reading on transfer learning visit the above mentioned site.
	
Need of Non-Linear activation functions?

	In Neural Network without any non-linear function, no matter how many layers it had, it will simply act as a
	single layer perceptron. Because summing these layers would give us an another layer with linear function. So,
	to introdeuce non-linearity in the network, non-linear activation functions are used.
	
	Suppose if our data is linearly separable then the linear classifier is sufficient to classify the data, but if
	our data is non-linear in nature then linear classifier will not able to produce the desired result. Here comes the 
	need of non-linear activation functions to seperate that non-linear data. Some of the non-linear activation fuctions
	are as follows:
	
	Tanh
	logistic function etc.
	

