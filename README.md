# Gender Detection Using OpenCV

We aimed to detect age and gender on camera. To make that happen, we use CNN architecture from deep learning and concatenate this model with OpenCV. CNN used for the machine's learn. We have choose CNN because it proved itself with the succeed in the Image Processing field in Deep Learning. Later we integrated it to the camera with help of the OpenCV.

## Dataset
This dataset consist of almost 2.3k data for per two class, men and women. Afterwards we generate some synthetic data, which  is why Keras's ImageDataGenerator used.

## Deep Learning
You may use the model previously produced by me or you may build yourself after run train.py. You can see the result of training from below image.

![plot](https://user-images.githubusercontent.com/81585804/168596708-90f8bc52-bd98-4b04-a8b4-f6837882ab37.png)


## OpenCV
Subsequently, in detect_gender_webcam.py we integrated our model to camera. Our model returns us the gender of the person.
