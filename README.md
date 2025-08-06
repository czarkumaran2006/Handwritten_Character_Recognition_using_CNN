🧠 Project Title: Handwritten Character Recognition using CNN
📌 Objective
To develop a deep learning model that can recognize handwritten digits (0–9) from images using the MNIST dataset. The model uses Convolutional Neural Networks (CNN) to accurately classify digits from grayscale image inputs.

🧰 Tools & Technologies
Programming Language: Python

Libraries: TensorFlow, Keras, NumPy, Matplotlib

Model Type: Convolutional Neural Network (CNN)

Dataset: MNIST (built-in Keras dataset)

📚 Dataset Description
The MNIST dataset consists of:

60,000 training images

10,000 testing images

Each image is 28x28 pixels, grayscale

Each image contains a handwritten digit from 0 to 9

⚙️ Project Workflow
Data Loading
Load MNIST data directly from Keras datasets.

Data Preprocessing

Normalize image pixel values to [0,1]

Reshape input to (28,28,1) for CNN

One-hot encode the target labels

Model Architecture (CNN)

2 convolutional layers with ReLU activation

MaxPooling to reduce spatial dimensions

Dropout layers for regularization

Fully connected Dense layer with softmax for classification

Model Training
Trained using Adam optimizer and categorical crossentropy loss function for 5 epochs.

Model Evaluation

Achieved ~98–99% accuracy on test data

Visualized training and validation accuracy

Model Saving
Final model saved as mnist_cnn_model.h5 for future use or deployment.
