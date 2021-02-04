# Handwritten-Digit-Recognition-Dataset

The MNIST problem is a dataset developed by Yann LeCun, Corinna Cortes and Christopher
Burges for evaluating machine learning models on the handwritten digit classification problem1.
The dataset was constructed from a number of scanned document datasets available from the
National Institute of Standards and Technology (NIST). This is where the name for the dataset
comes from, as the Modified NIST or MNIST dataset.
Images of digits were taken from a variety of scanned documents, normalized in size and
centered. This makes it an excellent dataset for evaluating models, allowing the developer to
focus on the machine learning with very little data cleaning or preparation required. Each
image is a 28 ⇥ 28 pixel square (784 pixels total). A standard split of the dataset is used to
evaluate and compare models, where 60,000 images are used to train a model and a separate set
of 10,000 images are used to test it.
It is a digit recognition task. As such there are 10 digits (0 to 9) or 10 classes to predict.
Results are reported using prediction error, which is nothing more than the inverted classification
accuracy. Excellent results achieve a prediction error of less than 1%. State-of-the-art prediction
error of approximately 0.2% can be achieved with large Convolutional Neural Networks. There
is a listing of the state-of-the-art results and links to the relevant papers on the MNIST and
other datasets on Rodrigo Benenson’s webpage
