# Face_detection


You can perform fast, accurate face detection with OpenCV using a pre-trained deep learning face detector model shipped with the library.

You may already know that OpenCV ships out-of-the-box with pre-trained Haar cascades that can be used for face detection…

…but I’m willing to bet that you don’t know about the “hidden” deep learning-based face detector that has been part of OpenCV since OpenCV 3.3.

When using OpenCV’s deep neural network module with Caffe models, you’ll need two sets of files:

The .prototxt file(s) which define the model architecture (i.e., the layers themselves)
The .caffemodel file which contains the weights for the actual layers
Both files are required when using models trained using Caffe for deep learning.

However, you’ll only find the prototxt files here in the GitHub repo.



