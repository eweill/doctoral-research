# DAC Challenge (System Design Contest)

The DAC Challenge features embedded system implementation of neural network based object detection for drones.  The provided dataset includes 98 classes including boats, buildings, cars, persons, etc.  The challenge is to create a neural network based solution maximizing the mAP over the entire dataset as well as running the system in "real-time" (20fps+) on a Jetson TX2.  As the target platform is an embedded device with a GPU that contains a smaller amount of cores (compared to traditional desktop accelerators), the neural network needs to be as small as possible (as little parameters as possible).  Challenge information can be found [here](http://www.cse.cuhk.edu.hk/~byu/2018-DAC-HDC/index.html).

Assuming the Tensorflow Object Detection API has already been setup (either on a Desktop or the Palmetto Cluster) for training, the following steps should be completed to create a training pipeline.

