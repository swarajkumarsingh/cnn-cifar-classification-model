## CNN Model for CIFAR-10 Classification

### Project Overview
This project involves training a Convolutional Neural Network (CNN) to classify images from the CIFAR-10 dataset. The CIFAR-10 dataset consists of 60,000 32x32 color images in 10 different classes, with 6,000 images per class. The classes are: airplane, automobile, bird, cat, deer, dog, frog, horse, ship, and truck.

### Model Architecture
The CNN model is designed with multiple convolutional layers, followed by max-pooling layers, and fully connected layers. The architecture is as follows:
1. Convolutional Layer 1: 32 filters, 3x3 kernel, ReLU activation
2. Max Pooling Layer 1: 2x2 pool size
3. Convolutional Layer 2: 64 filters, 3x3 kernel, ReLU activation
4. Max Pooling Layer 2: 2x2 pool size
5. Fully Connected Layer 1: 512 units, ReLU activation
6. Output Layer: 10 units, Softmax activation

### CNN Kernel overview
<img src="https://miro.medium.com/max/1070/1*Zx-ZMLKab7VOCQTxdZ1OAw.gif" style="max-width:400px;">

### 2x2 Max-Pool diagram
<img src="https://computersciencewiki.org/images/8/8a/MaxpoolSample2.png" style="max-width:400px;">

### Conv2d
<img src="https://i.imgur.com/KKtPOKE.png" style="max-width:540px">

### Dataset
The CIFAR-10 dataset is used, which can be downloaded from the official website.

### Training
The model is trained using the following parameters:
- Optimizer: Adam
- Loss Function: Categorical Crossentropy
- Batch Size: 128

### Installation
1. Clone the repository:
```
git clone https://github.com/swarajkumarsingh/cnn-cifar-classification-model.git
```

2. Open google collab and open the model file

### Results
The trained model achieves an accuracy of approximately 75% on the test set.

### Contributing
Contributions are welcome! Please fork the repository and create a pull request with your changes.

### License
This project is licensed under the MIT License. See the LICENSE file for more details.

### Acknowledgments
- The CIFAR-10 dataset creators
- Pytorch and nn Module
