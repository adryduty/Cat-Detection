# computer-vision-cat-project

In this project I trained a yolov5s for detecting my cat in my house. In order to distinguish among it and other objects (e.g. peluche cat, shoes, ...)
I built a training set with different images (234 images). You can find all the files you need in this repo:

* The three colab files (preprocessing, training and execution);
* label_dataframe.csv which is a csv file with the labels (of the bounding boxes) of all the 234 used images  
* best.pt which is the file of the weights (so that you can just run the third file with these weights if you want).

ATTENTION: for privacy reasons I decided to not load also the zip file with the pictures and the labels together (you have just the labels in the csv file). If you want to have access to it, just send me a message on Linkedin (https://www.linkedin.com/in/adriano-ettari-b8741b21b).

