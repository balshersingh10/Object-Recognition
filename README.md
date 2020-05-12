![Object-Recognition-with-Deep-Learning](https://16sp2o45qs973i2kpolavg37-wpengine.netdna-ssl.com/wp-content/uploads/61769640_thumbnail-3-e1457541721182.jpg)
# Object Recognition Using Supervised Machine Learning Techniques
We obtained the training Dataset from Keras library and used Jupyter Notebook as the platform for the purpose of coding. Our methodology involves use of Convolutional Neural Networks (CNN).

More specifically, we will be using the All-CNN network published in the 2015 ICLR paper, "Striving For Simplicity:The All Convolutional Net". This paper can be found at the following link:

### https://arxiv.org/pdf/1412.6806.pdf

## Model All-CNN-C
* Input 32 × 32 RGB image
* 3 × 3 conv. 96 ReLU
* 3 × 3 conv. 96 ReLU
* 3 × 3 max-pooling stride 2
* 3 × 3 conv. 192 ReLU
* 3 × 3 conv. 192 ReLU
* 3 × 3 max-pooling stride 2
* 3 × 3 conv. 192 ReLU
* 1 × 1 conv. 192 ReLU
* 1 × 1 conv. 10 ReLU
* global averaging over 6 × 6 spatial dimensions
* 10 or 100-way softmax

## Training the models with Data
The data taken is from **Cifar-10** dataset imported from keras library.

### Then the Class is predicted:
- 0 if airplane
- 1 if automobile
- 2 if bird
- 3 if cat
- 4 if deer
- 5 if dog
- 6 if frog
- 7 if horse
- 8 if ship
- 9 if truck

# Result =>
As there are 1.3 million parameters in CNN so, training data will take a lot more time than normal.
We loaded pre-trained weights saving our time from file **all_cnn_weights_0.9088_0.4994.hdf5**.

Algorithm has an accuracy of 87.51%. <br />
## Files included in repository are:
- **source.ipynb(Jupyter Notebook-https://jupyter.org/)**
- **source.pdf(Just a pdf print of jupyter notebook)**
- **all_cnn_weights_0.9088_0.4994.hdf5(Trained weights for CNN)**  <br />
