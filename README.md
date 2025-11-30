# 🌟 MLP for MNIST classification

## By Gabriel Padilla Haro

<figure>
  <img src="images/mlp.png" alt="Model representation">
  <figcaption>Subtítulo de la imagen</figcaption>
</figure>

## Description

In this project, a multilayer perceptron (MLP) neural network is constructed for the classification of digit images from the MNIST dataset. First, an exploratory analysis of the dataset images is performed, including their visualization and the normalization of pixel intensity values. After applying one-hot encoding to transform the categorical output variable, the model is built: two hidden layers with 256 neurons each, using the ReLU activation function, and an output layer with the softmax activation function, along with two Dropout regularization layers to prevent overfitting. Categorical cross-entropy is employed as the loss function, the Adam optimizer is used for training, and accuracy is adopted as the performance metric.

To obtain the model with the highest accuracy, a callback is defined to store in a folder the model achieving the best validation accuracy. In addition, accuracy curves for both training and validation sets are plotted with respect to training epochs. Subsequently, the model is evaluated on the test set. Finally, similar models are trained on data to which Gaussian noise has been added. We examine the variations in accuracy, as well as a potential improvement in model robustness through the inclusion of noisy samples as a data augmentation technique.

---

## 🚀 Technologies Used
- **Languages:** Python.
- **Libraries:** Keras, NumPy, Matplotlib, os.
- **Tools:** Jupyter Notebook, VSCode.

---

## 💡 Key Features
1. Step-by-step explanation of the complete learning process of the model.
2. Visualization of the dataset and the model’s accuracy.
3. Use of data augmentation techniques, such as adding Gaussian noise.

---

## 📸 Project Screenshots

<div style="display: flex; gap: 50px; flex-wrap: wrap;">
  <img src="images/five.png" alt="Screenshot 1" height="300px" />
  <img src="images/train_val.png" alt="Screenshot 2" height="300px" />
</div>
