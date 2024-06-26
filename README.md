# Image Classification for Disease Detection

The sole purpose of this application is to predict whether an image belongs to the diseased class or not. In this dataset, we have four classes: diseased leaf, diseased plant, fresh leaf, and fresh plant. This project leverages transfer learning techniques using VGG16 and VGG19 models to classify images and assess how the accuracy is affected by these models.

## Table of Contents

### Training VGG16 Model
1. [Libraries](#libraries)
2. [Training & DataLoader](#training--dataloader)
3. [Building the VGG16](#building-the-vgg16)
4. [Summary](#summary)
5. [Training The VGG16](#training-the-vgg16)
6. [Testing](#testing)
7. [Conclusion](#conclusion)

### Training VGG19 Model
1. [Libraries](#libraries-1)
2. [Training & DataLoader](#training--dataloader-1)
3. [Building the VGG19](#building-the-vgg19)
4. [Summary](#summary-1)
5. [Training The VGG19](#training-the-vgg19)
6. [Testing](#testing-1)
7. [Conclusion](#conclusion-1)

#### Final Conclusion

## Libraries

To train and test the models, you need to install the required libraries:

```bash
pip install tensorflow keras numpy matplotlib
