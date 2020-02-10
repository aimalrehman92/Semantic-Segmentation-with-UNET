# Semantic-Segmentation-with-UNET
In one line, it is pixel-wise classification. The deep learning model we use here is UNET model designed for Biomedical Image Segmentation originally proposed in the paper entitled: U-Net: Convolutional Networks for Biomedical Image Segmentation by Olaf Ronneberger, Philipp Fischer, Thomas Brox.

The advantage of this model over other models is that it does not require many thousand annotated images as training samples. It is pure convolutional network and does not consist of any fully-connected layer. The architecture consists of a contracting path to capture context and a symmetric expanding path that enables precise localization.

**Dataset Description:** The dataset consists of car images. Each image has just one car. We are provided with the binary mask of each image which serves as label and is used in training the model.
We use 1000 images in training dataset.
