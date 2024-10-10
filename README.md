# DL-Assignment-1

EXP 1 :

AlexNet

AlexNet, introduced in 2012, was a breakthrough in deep learning for image classification, 
especially after its success in the ImageNet competition. The architecture consists of 5 
convolutional layers followed by 3 fully connected layers, with ReLU activations for faster 
training, max-pooling layers for down-sampling, and dropout layers to prevent overfitting. 
It was designed to handle large-scale image data and significantly influenced the field of 
deep learning, marking a shift toward deeper neural networks for complex tasks like image recognition.

ResNet-18

ResNet-18, part of the Residual Networks family introduced in 2015, solved the "vanishing gradient" 
problem in deep networks by using skip connections, allowing gradients to flow directly through certain 
layers. This architecture starts with an initial convolution and pooling layer, followed by 4 residual 
blocks, each containing 2 convolutional layers. The residual (or skip) connections allow for the training 
of very deep networks without degradation in performance, making ResNet-18 both stable and highly accurate 
for image classification and other vision tasks.


EXP 2 :

Implementing Faster R-CNN with ResNet-50 backbone to detect objects in the COCO dataset.

Faster R-CNN with a ResNet-50 backbone is a deep learning model used for object detection.
The model combines two primary components: **Faster R-CNN**, which is responsible for 
detecting and classifying objects within an image, and **ResNet-50**, a pre-trained convolutional 
neural network that acts as the feature extractor.
The model processes input images, extracts key features using ResNet-50, proposes 
potential object regions using a Region Proposal Network (RPN), and then classifies 
and refines bounding boxes for detected objects. The goal is to train the model to accurately detect 
and localize objects in unseen images.
