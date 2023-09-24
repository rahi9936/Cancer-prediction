# Cancer-prediction

This Model  is better suited for breast cancer detection between M (malignant) and B (benign)
compared to the model1 .
The Model uses (CNNs) which are specifically designed to work with image data. It
consists of three convolutional layers, each with an increasing number of filters and
followed by ReLU activation functions and max-pooling layers. This will help us to extract
features from the input image and reduce its dimensions. The output from the
convolutional layers is then flattened and passed through two fully connected layers with
ReLU activation functions and a final linear layer with 2 outputs (representing the M and B
classes). This architecture is commonly used for image classification tasks and has been
shown to perform well in various benchmark datasets.
On the other hand, the first model is a simple feedforward neural network (FFNN) with
three fully connected layers and sigmoid activation functions. It takes a 30-dimensional
input and outputs a single value between 0 and 1, which may not be sufficient to
differentiate between the M and B classes. While the sigmoid function can be used to
represent binary classification problems, it is not optimized for image data and may not
perform well compared to CNNs.

![alt text](image.png)

![alt text](image.png)

![alt text](image.png)
