# object-detection

If you have been keeping up with the advancements in the area of object detection, you might have got used to hearing this word 'YOLO'. It has kind of become a buzzword.

How to use YOLO with Opencv?
We will focus in this tutorial on how to use YOLO with Opencv. This is the best approach for beginners, to get quickly the algorythm working without doing complex installations.

Opencv: also opencv has a deep learning framework that works with YOLO. Just make sure you have opencv 3.4.2 at least.
Advantage: it works without needing to install anything except opencv.
Disadvantage: it only works with CPU, so you can’t get really high speed to process videos in real time.


Installing dependenciesFollowing things are needed to execute the code we will be writing.
>>Python 3
>>Numpy
>>OpenCV Python bindings

Command line argumentsThe script requires four input arguments.
    --input image
    --YOLO config file
    --pre-trained YOLO weights
    --text file containing class names
    
    
    You can also download the pre-trained weights in Terminal by typingwget https://pjreddie.com/media/files/yolov3.weights
    
    Run the script by typing
    $ python obj.py --image (image) --config (cfg file ) --weights (pretrained weight) --classes (txt file)
    
    
