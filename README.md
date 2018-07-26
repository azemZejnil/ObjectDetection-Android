<div align="center">
<img style="float:left;" width="250" height="auto" src="https://github.com/azemZejnil/ObjectDetection-Android/blob/master/docs/imgs/Screenshot_20180725-101017.png">
<img style="float:left;" width="250" height="auto" src="https://github.com/azemZejnil/ObjectDetection-Android/blob/master/docs/imgs/Screenshot_20180725-101057.png">
<img style="float:left;" width="250" height="auto" src="https://github.com/azemZejnil/ObjectDetection-Android/blob/master/docs/imgs/Screenshot_20180725-101258.png">
</div>
<br>

# Tensorflow's object detection model.

<br>
Tensorflow model trained to detect two kinds of object: Car (Mercedes benz, A class 2000 and not to be confused, it is only type of car that can be recognized by this model.) and banana.

<br>

### About Tensorflow

TensorFlow is a multipurpose machine learning framework. Object detection is just one of many amazing possibilities from this framework.
<br>
Read more here:
<br>
https://www.tensorflow.org/

<br>

### Versioning

For some reason, back when I trained this model, Tensorflow 1.8 version has had some difficulties with 
successful training of object detection models and it was advised to use 1.7
<br>
I used 3.6 python and Pillow library for images manipulation.

<br>

### Formating and usage in Android app

There is Google's official repository on Tensorflow:
<br>
https://github.com/tensorflow
<br>
There you can find directions for usage of any of the Tensorflow trained models.
<br>
In Android application, we can use both .pb and .tflite files. 
After the training is finished their size is usually about 50mb, but both formats size can be 
significantly lowered by running the provided scripts for that matter. 

<br>

### Training

For the training purpose, you need to provide 
###### images and
###### labels.


