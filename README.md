<h1 align="center">Face Mask Detection</h1>

<div align= "center">
  <h4>Face Mask Detection system built with OpenCV, Keras/TensorFlow using Deep Learning and Computer Vision concepts in order to detect face masks in static images as well as in real-time video streams.</h4>
</div>

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
![Python](https://img.shields.io/badge/python-v3.6+-blue.svg)
[![contributions welcome](https://img.shields.io/badge/contributions-welcome-brightgreen.svg?style=flat)](https://github.com/Devang-25/Face-Mask-Detection-Project/issues)
[![Forks](https://img.shields.io/github/forks/Devang-25/Face-Mask-Detection-Project.svg?logo=github)](https://github.com/Devang-25/Face-Mask-Detection-Project/network/members)
[![Stargazers](https://img.shields.io/github/stars/Devang-25/Face-Mask-Detection-Project.svg?logo=github)](https://github.com/Devang-25/Face-Mask-Detection-Project/stargazers)
[![Issues](https://img.shields.io/github/issues/Devang-25/Face-Mask-Detection-Project.svg?logo=github)](https://github.com/Devang-25/Face-Mask-Detection-Project/issues)
[![MIT License](https://img.shields.io/github/license/Devang-25/Face-Mask-Detection-Project.svg?style=flat-square)](https://github.com/Devang-25/Face-Mask-Detection-Project/blob/master/LICENSE)
[![LinkedIn](https://img.shields.io/badge/-LinkedIn-black.svg?style=flat-square&logo=linkedin&colorB=555)](https://www.linkedin.com/in/devang25/)


&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
![Live Demo](https://github.com/Devang-25/Face-Mask-Detection-Project/blob/master/Readme_images/Demo.gif)

# You can find me at:-
✅ [Linkedin](https://www.linkedin.com/in/devang25/)<br> 
✅ [Github](https://github.com/Devang-25/)<br>
✅ [Facebook](https://www.facebook.com/Olive.Devang25)<br>
✅ [Instagram](https://www.instagram.com/idevangsharma/)<br>
✅ [Twitter](https://twitter.com/Olive_Devang25)<br>
✅ [Youtube](https://www.youtube.com/channel/UCvLEQ7QRsLkjHqrtwfSIFIA)<br>


## :innocent: Motivation
In the present scenario due to Covid-19, there is no efficient face mask detection applications which are now in high demand for transportation means, densely populated areas, residential districts, large-scale manufacturers and other enterprises to ensure safety. Also, the absence of large datasets of __‘with_mask’__ images has made this task more cumbersome and challenging. 

 
## :hourglass: Project Demo
:movie_camera: [YouTube Demo Link](https://www.youtube.com/watch?v=8Wf4gdL0048)

:computer: [Devpost Link](https://devpost.com/software/face-mask-detection)


<p align="center"><img src="https://github.com/Devang-25/Face-Mask-Detection-Project/blob/master/Readme_images/Screen%20Shot%202020-05-14%20at%208.49.06%20PM.png" width="700" height="400"></p>


## :warning: Tech/framework used

- [OpenCV](https://opencv.org/)
- [Caffe-based face detector](https://caffe.berkeleyvision.org/)
- [Keras](https://keras.io/)
- [TensorFlow](https://www.tensorflow.org/)
- [MobileNetV2](https://arxiv.org/abs/1801.04381)

## :star: Features
Our face mask detector didn't uses any morphed masked images dataset. The model is accurate, and since we used the MobileNetV2 architecture, it’s also computationally efficient and thus making it easier to deploy the model to embedded systems (Raspberry Pi, Google Coral, etc.).

This system can therefore be used in real-time applications which require face-mask detection for safety purposes due to the outbreak of Covid-19. This project can be integrated with embedded systems for application in airports, railway stations, offices, schools, and public places to ensure that public safety guidelines are followed.

## :file_folder: Dataset
The dataset used can be downloaded here - [Click to Download](https://drive.google.com/drive/folders/1XDte2DL2Mf_hw4NsmGst7QtYoU7sMBVG?usp=sharing)

This dataset consists of __3835 images__ belonging to two classes:
*	__with_mask: 1916 images__
*	__without_mask: 1919 images__

The images used were real images of faces wearing masks. The images were collected from the following sources:

* __Bing Search API__ ([See Python script](https://github.com/Devang-25/Face-Mask-Detection-Project/blob/master/search.py))
* __Kaggle datasets__ 
* __RMFD dataset__ ([See here](https://github.com/X-zhangyang/Real-World-Masked-Face-Dataset))

## :key: Prerequisites

All the dependencies and required libraries are included in the file <code>requirements.txt</code> [See here](https://github.com/Devang-25/Face-Mask-Detection-Project/blob/master/requirements.txt)

## 🚀&nbsp; Installation
1. Clone the repo
```
$ git clone https://github.com/Devang-25/Face-Mask-Detection-Project.git
```

2. Change your directory to the cloned repo and create a Python virtual environment named 'test'
```
$ mkvirtualenv test
```

3. Now, run the following command in your Terminal/Command Prompt to install the libraries required
```
$ pip3 install -r requirements.txt
```

## :bulb: Working

1. Open terminal. Go into the cloned project directory folder and type the following command:
```
$ python3 train_mask_detector.py --dataset dataset
```

2. Now detect the face masks in images 
```
$ python3 detect_mask_image.py --image images/pic1.jpeg
```

3. Detection in real-time video streams
```
$ python3 detect_mask_video.py 
```
## :key: Results

#### Our model gave 93% accuracy for Face Mask Detection after training via <code>tensorflow-gpu==2.0.0</code>

![](https://github.com/Devang-25/Face-Mask-Detection-Project/blob/master/Readme_images/Screenshot%202020-06-01%20at%209.48.27%20PM.png)

#### We got the following accuracy/loss training curve plot
![](https://github.com/Devang-25/Face-Mask-Detection-Project/blob/master/plot.png)

## :clap: And it's done!
Feel free to mail me for any doubts/query 
:email: devshu25@gmail.com

## :handshake: Contribution
Feel free to **file a new issue** with a respective title and description on the the [Face-Mask-Detection](https://github.com/Devang-25/Face-Mask-Detection-Project/issues) repository. If you already found a solution to your problem, **I would love to review your pull request**! 

## :heart: Owner
Made with :heart:&nbsp;  by [Devang Sharma](https://github.com/Devang-25)<br>
Guidance Taken From Chandrika Deb

## :+1: Credits
* [https://www.pyimagesearch.com/](https://www.pyimagesearch.com/)
* [https://www.tensorflow.org/tutorials/images/transfer_learning](https://www.tensorflow.org/tutorials/images/transfer_learning)

## :eyes: License
MIT © [Devang Sharma](https://github.com/Devang-25/Face-Mask-Detection-Project/blob/master/LICENSE)
