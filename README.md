# Real-Time-Face-Detection

It is a basic example of OpenCV's deep neural network (DNN) module for face detection in real-time using a pre-trained model. 

1) Initially starts with importing libraries and setting up the camera window.
2) Setting some model parameters (You can change them accordingly)
then implementing the Face detection with a trained model taken from a pre-trained face detection model from two files: deploy.prototxt (which defines the model architecture) and res10_300x300_ssd_iter_140000_fp16.caffemodel (which contains the trained weights).
3) Along with the bounding box, it also displays the Confidence percent.
4) Finally, it releases the video source and closes the OpenCV window when the ESC key is pressed.
Note: The script uses the '27' key (ESC key) as the exit condition from the main loop. Pressing the ESC key will terminate the script and close the window.
