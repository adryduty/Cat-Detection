# computer-vision-cat-project

In this project I trained a yolov5s for detecting my cat in my house. In order to distinguish among it and other objects (e.g. peluche cat, shoes, ...)
I built a training set with different images (154 images). You can find all the files you need in this repo:

* The three colab files (preprocessing, training and execution);
* label_154.csv which is a csv file with the labels (of the bounding boxes) of all the 154 used images; 
* best.pt which is the file of the weights (so that you can just run the third file with these weights if you want).
