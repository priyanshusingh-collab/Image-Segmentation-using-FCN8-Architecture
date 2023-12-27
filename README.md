# Image-Segmentation-using-FCN8-Architecture

FCN8 stands for Fully Convolutional Network with 8x upsampling. It is a type of neural network that can perform semantic segmentation, which means assigning a class label to each pixel in an image. We can use a VGG-16 network as the feature extractor, followed by a series of convolutional and deconvolutional layers to generate the segmentation mask. The model also uses skip connections to combine low-level and high-level features from different layers of the VGG-16 network. The camvid dataset is a subset of the Cambridge-Driving Labeled Video Database. It contains video frames from a moving vehicle and annotations with pixel-wise label maps for 12 classes, such as sky, road, building, vehicle, etc.
The FCN8 model can achieve good results on the camvid dataset, with high Intersection over Union (IoU) scores for most classes. IoU is a metric that measures how well the predicted segmentation mask overlaps with the ground truth. 
In this work, we have used FCN8 model to create a segmentation model using camvid dataset. 

![download](https://github.com/priyanshusingh-collab/Image-Segmentation-using-FCN8-Architecture/assets/58718943/8624d7d0-8851-4ef2-b932-e22aebd3a265)

![download (1)](https://github.com/priyanshusingh-collab/Image-Segmentation-using-FCN8-Architecture/assets/58718943/9b7c8547-5575-4498-8a16-bfe6aadfed09)

![download (2)](https://github.com/priyanshusingh-collab/Image-Segmentation-using-FCN8-Architecture/assets/58718943/afd77f4b-fdbb-4545-840a-45fa49fd7e57)

