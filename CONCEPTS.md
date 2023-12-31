# Important terms and concepts to know

## Normalization
Normalization in machine learning refers to the process of transforming numerical data into a standardized range. It involves adjusting the values of features in a dataset 
to have a common scale, typically between 0 and 1 or -1 and 1. Normalization is an important preprocessing step as it helps in improving the performance and convergence of 
many machine learning algorithms.

## Data Augmentation
Data augmentation is a technique used in machine learning and computer vision to increase the size and diversity of a training dataset by applying various transformations to 
the existing data. It is particularly useful when the available training data is limited or when the model would benefit from exposure to a wider range of variations in the 
input data.

## Batches
In deep learning, a batch refers to a subset of the training data that is processed together during each iteration of the training algorithm. Instead of updating the model's parameters based on individual training examples, batches allow for more efficient computation by processing multiple examples simultaneously.

Typically, the entire training dataset is divided into smaller batches, and each batch is fed into the neural network for forward propagation, followed by backpropagation to calculate the gradients and update the model's parameters. This process is repeated for multiple epochs until the model converges.

## Filters
In Convolutional Neural Networks (CNNs), filters, also known as convolutional kernels or feature detectors, are small-sized matrices used to perform the convolution operation 
on input data. Filters play a crucial role in CNNs by extracting local features and patterns from the input data, enabling the network to learn hierarchical representations.

## Kernels
In Convolutional Neural Networks (CNNs), a kernel refers to the same concept as a filter or a convolutional filter. Kernels are small matrices of weights that are applied to the
input data during the convolutional operation.

## Strides
The stride determines how much the filter shifts or moves horizontally and vertically after each convolution operation. A stride of 1 means the filter moves one unit at a time, a stride of 2 means it moves two units at a time, and so on. The stride can also be different for the horizontal and vertical directions.

_To know more about kernels, filters and all other terms related to CNN in detail refer CNN explainer website_
>https://poloclub.github.io/cnn-explainer/

<hr>

### Why to shuffle your dataset?
In many real-world datasets, the order of the examples may contain inherent patterns or biases. If the dataset is not shuffled, the model can inadvertently learn to rely on the order of the examples rather than learning the underlying patterns. Shuffling the dataset helps to break any sequential patterns, ensuring that the model is exposed to a diverse range of examples during training and reducing the risk of biased learning.


