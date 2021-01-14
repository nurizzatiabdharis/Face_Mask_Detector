# Face Mask Detector with OpenCV, Keras/TensorFlow

Version :
- Python : 3.8.5
- Numpy : 1.19.3

Installation :
- Anaconda 
- Jupyter Notebook
- Tensorflow
- opencv

Face mask dataset source : 
- https://arxiv.org/abs/2008.08016
- https://github.com/cabani/MaskedFace-Net 

OpenCV :
- haarcascade_frontalface_default.xml 
  Link : https://github.com/opencv/opencv/tree/master/data/haarcascades 


**Web break our project into two distinct phases, each with its own respective sub-steps :** 
- ***Phase 1 : Training*** : Here we’ll focus on loading our face mask detection dataset from disk, training a model (using Keras/TensorFlow) on this dataset, and then serializing the face mask detector to disk 

- ***Phase 2 : Deployment*** : Once the face mask detector is trained, we can then move on to loading the mask detector, performing face detection, and then classifying each face as No_mask or Face_mask
