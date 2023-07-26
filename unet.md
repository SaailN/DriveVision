## Semantic Segemenatation using U-Net model

- The UNet architecture is a deep learning model specifically designed for image segmentation tasks. 
- It is widely used in various applications, such as medical image segmentation, satellite image analysis, and object detection in autonomous vehicles, due to its ability to handle high-resolution images and produce accurate segmentation maps. 
- UNet is well-suited for multi-class image segmentation tasks.


## U-Net Architecture

![U-NET model](/media/unet.png)

Main components of U-Net Architecture are
- Encoder (Contracting path)
- Decoder (Expanding Path)
- Skip connections 

 The UNet architecture consists of a contracting path and an expanding path, which are connected by skip connections. The contracting path is used to extract features from the input image, and the expanding path is used for upsampling the feature maps and generating the final segmentation map. In contrast, FCN consists of a single encoder-decoder structure, where the encoder is a sequence of convolutional and max pooling layers that downsample the input image and extract features, and the decoder is a sequence of convolutional and upsampling layers that upsample the feature maps and generate the final segmentation map.




## References:
 
 [U-Net Resreach paper](https://arxiv.org/pdf/1505.04597.pdf)

 [U-Net paper walk through](https://www.youtube.com/watch?v=oLvmLJkmXuc)

 [U-Net Architecture For Image Segmentation](/https://blog.paperspace.com/unet-architecture-image-segmentation/)
