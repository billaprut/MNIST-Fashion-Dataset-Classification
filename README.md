# MNIST-Fashion-Dataset-Classification

To build and refine a neural network model capable of classifying images of retail products (Fashion MNIST dataset). Utilizing TensorFlow and Keras, I implemented a model that effectively categorized images into ten distinct classes, such as dresses, coats, shirts, and more, from the Fashion MNIST dataset.

The dataset, sourced from TensorFlow, comprised 70,000 grayscale images, each 28x28 pixels, portraying various fashion items. I divided the dataset into two segments: 60,000 images for training and 10,000 for testing. The images represented a spectrum of shades of grey, correlating to pixel values ranging between 0 and 255.

To prepare the data for the neural network, I scaled the pixel values to a range of 0 to 1 for both training and test datasets. This preprocessing was critical for the neural network to process the input effectively.

The core of my project was building the neural network model. It consisted of three layers: a Flatten layer to transform the images into a one-dimensional array, a Dense layer with 128 neurons and ReLU activation, and another Dense layer with 10 neurons, corresponding to the 10 classes of fashion items, using softmax activation. After compiling the model with the Adam optimizer and sparse categorical crossentropy as the loss function, I trained it for 5 epochs.

The model achieved an impressive 88% accuracy on the training data. To evaluate its performance, I used the test dataset, where the model demonstrated a commendable accuracy of 87.12%.
