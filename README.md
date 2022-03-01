# [Sports Person Classifier: Project Overview](https://github.com/KrutikaDesai02/SportsPersonClassifier)
* This is an end to end project on Image classification where our end goal is to build a website where you can drag and drop an image of a sport person and it will identify that sport person name.
* We have used Fatkun Chrome Tool to gather images and did data cleaning using Haar Cascade from OpenCV.

 ![](/images/virat1.png)
* We did feature eEngineering using Wavelet Transforms

 ![](/images/virat2.png)

* After cleaning the data tried support vector machine and tried couple of other models using GridSearchCV. Final ensembled model achieved SVM with linear kernel around 85% score.
*  Heat Map: 

 ![](/images/index.png)
 
* We will build a model first, hyper tune it, exported to a file, then we will run a python flask server and our website will make a call to that python flask server. 
* From our website we drop an image of Sport person to identify his/her name.

 ![](/images/virat5.png)
