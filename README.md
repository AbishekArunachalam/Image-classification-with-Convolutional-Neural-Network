# Image-classification-with-Convolutional-Neural-Network
The project involves working with the famous Mnist fashion dataset to classify clothes in each category using Convolutional Neural Networks (CNN). 

In the part-1, transfer learning is performed by using the RESNET-50 model weights from the Keras package and classify the images. 

In part-2, CNN model is build from scratch by stacking layers and training on the dataset to find its weights.

Grid search is use to find the most optimal parameters for this model.

Save the weights of the best model in Hierarchical data format(HDF5).

#### Optimisation algorithms: ####

* Adam
* Singular value decomposition(SGD)
* Ada Delta
* Nadam

![alt text](https://ibb.co/bNzRGRX)
	
Optimizer	Accuracy score
Adam	92.6%
Nadam	91.7%
Adadelta	93.1%
Sgd	89.3%



