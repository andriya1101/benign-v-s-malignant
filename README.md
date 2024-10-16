## benign-v-s-malignant
This project uses a neural network model built with TensorFlow/Keras to classify cancer tumors as malignant or benign based on medical data. The dataset used is assumed to contain features related to cancer diagnosis, including characteristics of cell nuclei, and the target label is whether the tumor is malignant (1) or benign (0).

**Project Overview**
The main objective of this project is to build and train a neural network that can predict whether a cancer tumor is malignant or benign based on various input features. The model is trained on a labeled dataset, which contains features representing different characteristics of cancer cells.

**Dataset**
The dataset used for this project is cancer.csv.[DATASET](https://www.youtube.com/redirect?event=video_description&redir_token=QUFFLUhqa0h4U3VmNGJ6WjBWOVNlRlJrMmdiUi14cGg3QXxBQ3Jtc0ttNTJfdW5wS0tNd1J3WmIwVUw4WW55X1VvWHIxbVpjYmtSMGdKTEIyY2RwNnFuZDk2cDJuZENvakVjVUZYMmhEY0VOTnhCeHNFUFJMdnMwZ1h1VE1UMVBRS1V2bTdPR1RzekVMVXFlaDRpdl83UUg5WQ&q=https%3A%2F%2Fgist.github.com%2Fadameubanks%2F35a6beea49e5b9ba62797e595a9626c0&v=z1PGJ9quPV8) It contains various features related to cancer diagnosis:

Features: Characteristics of cell nuclei (e.g., radius, texture, perimeter, area, smoothness, etc.).
Target: A binary column diagnosis(1=m, 0=b) representing whether the cancer is malignant (1) or benign (0).
**Model Architecture**
The neural network used for classification is a fully connected feedforward network with the following architecture:

Input Layer: 30 input features (the number of columns in the dataset after excluding the target column).
Hidden Layers:
First hidden layer: 256 neurons, activation function = sigmoid.
Second hidden layer: 256 neurons, activation function = sigmoid.
Output Layer: 1 neuron (binary classification), activation function = sigmoid.
Model Training
Optimizer: Adam
Loss Function: Binary Crossentropy
Metrics: Accuracy
Epochs: 1000
