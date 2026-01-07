# SVM vs Neural Network

We compare the SVM model to a Neural Network based model to see performance differences.


## Neural Network Highlights

We take a deep dive into how to build a Multi-Layer Perceptron (MLP) and its different parameters

- **Architecture**: Feedforward MLP with 1-3 hidden layers (32-256 neurons), ReLU activation, Dropout regularization
- **Tuning**: Keras Tuner RandomSearch optimizing for recall (critical for cancer detection)
- **Key Finding**: MLP achieves **100% recall with fewer false alarms** than SVM when tuned for medical context
