# CNN-model
## CNN-Based Classification of Open and Closed Eyes

The model is built with Keras using Convolutional Neural Networks (CNN). 
A CNN basically consists of an input layer, an output layer and a hidden layer which can have multiple layers
A convolution operation is performed on these layers using a filter that performs 2D matrix multiplication on the layer and filter.
<br/>
<br/>The CNN model architecture consists of the following layers:
<br/>•	Convolutional layer; 32 nodes, kernel size 3
<br/>•	Convolutional layer; 32 nodes, kernel size 3
<br/>•	Convolutional layer; 64 nodes, kernel size 3
<br/>•	Fully connected layer; 128 nodes
<br/>The final layer is also a fully connected layer with 2 nodes. A ‘Relu’ activation function is used in all the layers except the output layer in which we used ‘Softmax’.
