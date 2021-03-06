# HW 1

**Objective**: Implement contrastive representation learning with SimCLR on small dataset.

**Build with**:
* _**Pytorch**_ (1) 
* _**Tensorflow**_ (2) 

![data_aug](https://user-images.githubusercontent.com/46875754/134620941-faea7495-74b1-4ad8-a2b7-1b08d70de2e3.png)

**Techniques applied**:
* **Image Augmentation (Random Crop/Resize/Color Distortion)** 
* **ResNet18 and ResNet50**
* **Contrastive Loss (NT-XEnt)**
* **ReLU Activation Layer**
* **TSNE Visualization** 

**SimCLR Loss Achieved**:
* **Pytorch** (Linear Model Test Accuracy with SimCLR = 0.67)
    - SimCLR: ImageNet using only Elephant, Car, and Airplane Images, Batch Size = 50, Number of Epoch = 10, Temperature = 0.05
* **Tensorflow** (Linear Model Test Accuracy with SimCLR  = 0.72)
    - SimCLR: ImageNet using only Elephant, Car, and Airplane Images, Batch Size = 32, Number of Epoch = 50, Temperature = 0.1
    
_**Note - Result can change with bigger dataset and different projection head**_

Reference/Modified code from the following notebooks: 
* https://medium.com/analytics-vidhya/understanding-simclr-a-simple-framework-for-contrastive-learning-of-visual-representations-d544a9003f3c
* https://github.com/sayakpaul/SimCLR-in-TensorFlow-2

