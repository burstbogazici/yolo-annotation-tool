# Yolo-Annotation-Tool-New

This is new yolo annotation tool which is added new features. I have posted three blogs for how to train yolov2 and v3 using our custom images.


Do steps:

Before starting annotation, put image folder into the Images folder. Let my image folder name be `pics` Project folder shold be like this:
```
-main.py
-process.py
-cklasses.txt
-Images/
  -pics/
    -<image1>.png
    -<image2>.png
    -<image3>.png
    -...
-Labels/
```

Run below code with Python3
```
main.py
```

After running main.py, specify the image folder name that you put into `Images` folder. Just type `pics` into the Image Dir text box/

Before annotating bounding bozes choose which class to annotate.

After finishing annotating all images

```
run process.py
```

The dataset is ready for yolo training.
