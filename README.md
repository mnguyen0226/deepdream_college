# DeepDream: What I Dreamt While At College

I experienced various vivid dream during college. [Inceptionism Algorithm](https://ai.googleblog.com/2015/06/inceptionism-going-deeper-into-neural.html) allows me to share my dream with you visually. Let's take a look!

![alt-text](https://github.com/mnguyen0226/deepdream_college/blob/main/results/hokiebird.jpg)

## 1. Gallery
![alt-text](https://github.com/mnguyen0226/deepdream_college/blob/main/results/career.jpg)

![alt-text](https://github.com/mnguyen0226/deepdream_college/blob/main/results/VT.jpg)

**Other Images**
- [Meta](https://github.com/mnguyen0226/deepdream_college/tree/main/results/gallery/meta)
- [Google](https://github.com/mnguyen0226/deepdream_college/tree/main/results/gallery/google)
- [Amazon](https://github.com/mnguyen0226/deepdream_college/tree/main/results/gallery/amazon)
- [Apple](https://github.com/mnguyen0226/deepdream_college/tree/main/results/gallery/apple)
- [Tesla](https://github.com/mnguyen0226/deepdream_college/tree/main/results/gallery/tesla)
- [Twitter](https://github.com/mnguyen0226/deepdream_college/tree/main/results/gallery/twitter)
- [Drillfield](https://github.com/mnguyen0226/deepdream_college/tree/main/results/gallery/drillfield)
- [IEEE Club](https://github.com/mnguyen0226/deepdream_college/tree/main/results/gallery/ieee)
- [Hokie Bird](https://github.com/mnguyen0226/deepdream_college/tree/main/results/gallery/hokie_bird)
- [Lane Stadium](https://github.com/mnguyen0226/deepdream_college/tree/main/results/gallery/lane_stadium)
- [Robotic Lab](https://github.com/mnguyen0226/deepdream_college/tree/main/results/gallery/robotics)
- [Tailgate](https://github.com/mnguyen0226/deepdream_college/tree/main/results/gallery/taigate)
- [Torgersen Bridge](https://github.com/mnguyen0226/deepdream_college/tree/main/results/gallery/torg_bridge)
- [STAT 4984 Class](https://github.com/mnguyen0226/deepdream_college/tree/main/results/gallery/class)

**Architecture-specific Images**
- [ResNet-50](https://github.com/mnguyen0226/deepdream_college/tree/main/results/resnet50)
- [ResNet-101](https://github.com/mnguyen0226/deepdream_college/tree/main/results/resnet101)
- [ResNet-152](https://github.com/mnguyen0226/deepdream_college/tree/main/results/resnet152)
- [VGG-11](https://github.com/mnguyen0226/deepdream_college/tree/main/results/vgg11)
- [VGG-101](https://github.com/mnguyen0226/deepdream_college/tree/main/results/vgg16)
- [VGG-152](https://github.com/mnguyen0226/deepdream_college/tree/main/results/vgg19)

## 2. Explanation
VGG11, VGG16, VGG19, ResNet50, ResNet101, ResNet152 trained from scratch on [MIT Indoor Scene](https://www.kaggle.com/datasets/itsahmad/indoor-scenes-cvpr-2019) dataset.

![alt-text](https://github.com/mnguyen0226/deepdream_college/blob/main/results/dd_pipeline.png)

## 3. Reproduction
```python
python==3.8.5x
matplotlib
pytorch==1.8.1+cu111
opencv-contrib-python
opencv-python
```

**Training script**: src/notebooks/training

**DeepDream script**: src/notebooks/deepdream

**Note**: Due to the size of the trained model, I will attach the trained model in [here](https://drive.google.com/drive/folders/1Nrx2pYcL1b273R_4UTI8JEWsvyzi086u?usp=sharing).

## 4. Inspiration
[Google AI Blog - "Inceptionism: Going Deeper into Neural Networks"](https://ai.googleblog.com/2015/06/inceptionism-going-deeper-into-neural.html)

[Aleska Gordic's repository](https://github.com/gordicaleksa/pytorch-deepdream)

## 5. Report

[Proposal](https://github.com/mnguyen0226/deepdream_college/blob/main/docs/report.pdf)

[Final Report](https://github.com/mnguyen0226/deepdream_college/blob/main/docs/report.pdf)