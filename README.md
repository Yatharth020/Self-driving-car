# Self-driving-car
Predicting the steering angle degree in radians from a sequential input image,following an end to end model using the NVIDIA model
This is an implementation of the research paper published by Nvidia a couple of years ago, with lots of changes. We will use a Convolution Neural Network architecture to train our model. We trained a convolutional neural network (CNN) to map raw pixels from a single front-facing camera directly to steering commands. This end-to-end approach proved surprisingly powerful. With minimum training data from humans the sys-tem learns to drive in traffic on local roads with or without lane markings and on highways. It also operates in areas with unclear visual guidance such as in parking lots and on unpaved roads. The system automatically learns internal representations of the necessary processing steps such as detecting useful road features with only the human steering angle as the training signal. We never explicitly trained it to detect, for example, the outline of roads. Compared to explicit decomposition of the problem, such as lane marking detection, path planning, and control, our end-to-end system optimizes all processing steps simultaneously. We argue that this will eventually lead to better performance and smaller systems. Better performance will result because the internal components self-optimize to maximize overall system performance, instead of optimizing human-selected intermediate criteria, e. g., lane detection. Such criteria understandably are selected for ease of human interpretation which doesn’t automatically guarantee maximum system performance. Smaller networks are possible because the system learns to solve the problem with the minimal number of processing steps. The system operates at 30 frames per second (FPS).

<img src = https://github.com/yatscool007/Self-driving-car/blob/master/gif.gif>

## Architecture followed 

<img src = https://github.com/yatscool007/Self-driving-car/blob/master/Images/Architecture.PNG>

## Training the model

<img src = https://github.com/yatscool007/Self-driving-car/blob/master/Images/training.PNG>
