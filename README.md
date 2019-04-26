# Digit-Recognizer-CNN

You will be working on MNIST data, a dataset of thousands of images of handwritten digits. You can
download the dataset here - https://www.kaggle.com/c/digit-recognizer/data. The data files train.csv
and test.csv contain gray-scale images of hand-drawn digits, from zero through nine. Each image is 28
pixels in height and 28 pixels in width, for a total of 784 pixels in total. Each pixel has a single pixel-value
associated with it, indicating the lightness or darkness of that pixel, with higher numbers meaning
darker. This pixel-value is an integer between 0 and 255, inclusive. The training data set, (train.csv), has
785 columns. The first column, called "label", is the digit that was drawn by the user. The rest of the
columns contain the pixel-values of the associated image.” You only need to download the train.csv file.
test.csv is not required. The train.csv file contains 42k samples of images. To reduce time of running the
program, you will only work with 10,000 randomly selected samples out of these, although make sure
you have equal number of samples belonging to each label (i.e.,1,000 samples of label ‘0’, 1,000 samples
of label ‘1’ and so on).
Apply PyTorch package to implement the CNN algorithm, and train the model using the training set
generated in the last task and use your model to predict labels in the test set. The structure of CNN
isdefined as follows. You have the flexibility to define the parameters of different layers (e.g., No. of
nodes, filter dimension, pooling dimension etc.). Show your results on both training and testing sets.

Structure:
Convolutional layer -> Max pooling layer -> Convolutional layer - > Max pooling layer -> Fully connected
layer x2 -> Softmax layer
Deliverabl
