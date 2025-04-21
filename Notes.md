Convolutional Neural Networks

Seeing our world through the lens of mathematics

Images are comprised of a two dimensional array of vectors

In colored images, each pixel's vector matches its color on the RGB scale

Grayscale pixel vectors consist of a single value in the range of 0 (black) to 255 (white)

Red Green Blue


### Feature Extraction

Techniques used in the identification 

### Image Resolution 
High reso imgs increase computational complexity unn, while low reso imgs might lose information.


### Pre-processing Pipeline


## The Power of CNNs

### History

In 2010, by Dr. Fei Fei Li started the ILSVRC. A competition where to goal was to classify i diverse set of images

In 2012 a team from U of Toronto won the comp by a large margin using a novel, CNN based, architecture named 'AlexNet'

### Convolution

Convo ops facilitate dimensionalaity reduction in an img while maintaining the positional relationships and presence of important features.

Window

Stride: how many squares...

Padding: technique used to manage the spatial dimensions of input data (extra layer outside)

Kernel/Filter: defines the mathematical transformation applied to a window when determine the resultant value

Pooling: when a convolution operation focuses on extracting a single value from a given window via min-max-median operation

## Model Metrics

Evaluating the performance of a model lets us know how it's architecture and training metholodygy...


ROC Curve: a graphd that shows how well a binary classifier can discriminate between two classes

Confusion matrix: plots a model's predicted classes against the data's true classes. This helps indicate overfitting to a particular class as well as overall model performance.






