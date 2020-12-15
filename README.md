# Pneumonia-Diagnosis
Detecting Pneumonia with CNN

# Main Code: Pneumonia_Diagnosis.ipynb

Detecting Pneumonia Diagnosis on a small and challenging dataset that contains Xray iamges of Patients with three different Convolutional models.

**1. Fine tuning.**
Training all the base-layers of VGG-16 once again + the newly added fully connected layers for better accuracy.

Results: 1. Val_accuracy: 0.8750  2.Evaluate  on Test data: 0.9359


**2. Transfer learning.**
Training only the newly added fully connected layers of our network.

Results: 1. Val_accuracy: 0.9375  2. Evaluate on Test data: 0.9295

**3. Depthwise Convolutional Network.**
Training with our own depthwise Convolutional Network

Results: 1. Val_accuracy: 0.8750  2. Evaluate  on Test data: 0.8958


The famous VGG-16 network that I used for first two models for finetuning and transfer learning respectively.
![VGG-16 ](https://github.com/Kaif10/Pneumonia-Diagnosis/blob/master/vgg16.jpg)


In the below image, the network on the left is an example of the fine-tuned model.
![VGG-16 ](https://github.com/Kaif10/Pneumonia-Diagnosis/blob/master/img.png)


