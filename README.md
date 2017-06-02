# darkflow-docker
A docker image including tensorflow and darkflow, a tensorflow version of darknet.

Darknet is an open source neural network framework written in C and CUDA made by Joseph Redmon (https://pjreddie.com/darknet/). It is used to run an object detection network called YOLO (you only look once, https://pjreddie.com/darknet/yolo/).
Darkflow is a Tensorflow version of Darknet, made by Th. Thrieu (https://github.com/thtrieu/darkflow).

This image mixes up the tensorflow image (https://hub.docker.com/r/tensorflow/tensorflow/) with darkflow, and provide a demo notebook to test tiny-yolo classification.

To run the image: docker run -it -p 8888:8888 davvdg/darkflow-docker. Copy past the url displayed in your console to your brower to start the ipython notebook and enjoy !
