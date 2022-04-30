# DeepDream: What I Dreamt While At College

I experienced various vivid dream during college. [Inceptionism Algorithm](https://ai.googleblog.com/2015/06/inceptionism-going-deeper-into-neural.html) allows me to share my dream with you visually. Let's take a look!

![alt-text](https://github.com/mnguyen0226/deepdream_college/blob/main/results/hokiebird.jpg)

## 1. Gallery


## 2. Explanation
VGG11, VGG16, VGG19, ResNet50, ResNet101, ResNet152 trained from scratch on [MIT Indoor Scene](https://www.kaggle.com/datasets/itsahmad/indoor-scenes-cvpr-2019) dataset.

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

## 4. Inspiration
[Google AI Blog - "Inceptionism: Going Deeper into Neural Networks"](https://ai.googleblog.com/2015/06/inceptionism-going-deeper-into-neural.html)

[Aleska Gordic's repository](https://github.com/gordicaleksa/pytorch-deepdream)

## 5. Report
