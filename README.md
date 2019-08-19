# SLAM/VO paper summary

This repo is the zoo for SLAM(Simultaneous localization and mapping) and VO. 

Thanks to the breakthrough in deep nerual net, many SLAM systems embrace CNN(convolution neural network) in their system. 
We also collect some papers about plane&object detection, depth pridiction and semantic segmentation.

## Monocular SLAM

* `CVPR2019` CodeSLAM — Learning a Compact, Optimisable Representation for Dense Visual SLAM [(link)](https://arxiv.org/pdf/1804.00874.pdf)
  `depth pridiction` `deep net`
  M Bloesch, J Czarnowski, R Clark, S Leutenegger, A J. Davison
  Imperial College London, UK

* `CVPR2019`An Efficient Schmidt-EKF for 3D Visual-Inertial SLAM [(link)](https://arxiv.org/abs/1903.08636)
  `indoor`
* `CVPR2017` CNN-SLAM: Real-time dense monocular SLAM with learned depth prediction [(link)](https://arxiv.org/abs/1704.03489) | [(github)](https://github.com/iitmcvg/CNN_SLAM) 
  `depth prediction` `deep net` `semantic segmentation`
  Keisuke Tateno, Federico Tombari, Iro Laina, Nassir Navab
  TU Munich
  * Estimating the absolute scale of the reconstruction. obtaining dense depths along texture-less regions and dealing with pure rotational motions
  * privileges depth prediction in image locations where monocular SLAM approaches tend to fail. 

## Stereo SLAM

## Visual Odemeter(VO)

# Related work

## 3D plane/object detection

* `CVPR2019` PlaneRCNN: 3D Plane Detection and Reconstruction from a Single Image

* `CVPR2019` Stereo R-CNN based 3D Object Detection for Autonomous Driving [(link)](https://arxiv.org/abs/1902.09738) | [(github)](https://arxiv.org/abs/1902.09738) 
  `Object detection` `Stereo` `3D`
* `CVPR2019` 

## Depth and Ego motion estimation

* `CVPR2019` [Learning to Adapt for Stereo](https://arxiv.org/abs/1904.02957)  | [github](https://github.com/CVLAB-Unibo/Learning2AdaptForStereo)	
  Alessio Tonioni, Oscar Rahnama, Thomas Joy, Luigi Di Stefano, Thalaiyasingam Ajanthan, Philip H. S. Torr
  University of Oxford

* unsupervised adaptation to estimate depth.

## Auto-driving

# Datasets

* KITTI: [http://www.cvlibs.net/](http://www.cvlibs.net/)
  `outdoor` `driving` 