# Style_Transfer_with_Deep_Neural_Network

## The creation of this style transfer model was undertaken to fulfill the requirements set by the Udacity Introduction to Deep Learning Nanodegree program.

Adhering to the approach outlined in the Image Style Transfer Using Convolutional Neural Networks [Image Style Transfer Using Convolutional Neural Networks](https://www.cv-foundation.org/openaccess/content_cvpr_2016/papers/Gatys_Image_Style_Transfer_CVPR_2016_paper.pdf), I replicated an image style transfer technique in PyTorch.

The methodology presented in this paper involves leveraging the features extracted from the 19-layer VGG Network, which encompasses a sequence of convolutional and pooling layers along with a handful of fully-connected layers. The convolutional layers are categorized and named according to their respective stacks and positions within each stack. For instance, Conv1_1 is the initial convolutional layer through which an image passes in the first stack, while Conv2_1 serves the same role in the second stack. Notably, the deepest convolutional layer in the network is referred to as conv5_4.

## Separating Style and Content
Style transfer relies on separating the content and style of an image. Given one content image and one style image, we aim to create a new, target image which should contain our desired content and style components:

- objects and their arrangement are similar to that of the content image
- style, colors, and textures are similar to that of the style image


## Requirements
- PyTorch
- Matplotlib
- VGG19 model
- Convolutional Neural Network (CNN)
- Content/Style Images



