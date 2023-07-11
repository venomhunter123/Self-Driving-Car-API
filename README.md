# Self-Driving-Car-API
Artificial intelligence algorithms enable self-driving cars with Detecting Lane Lines.

Table of Contents

P1 - Detecting Lane Lines (basic)
Summary: Detected highway lane lines on a video stream. Used OpencV image analysis techniques to identify lines, including Hough Transforms and Canny edge detection.
Keywords: Computer Vision

P2 - Traffic Sign Classification
Summary: Built and trained a deep neural network to classify traffic signs, using TensorFlow. Experimented with different network architectures. Performed image pre-processing and validation to guard against overfitting.
Keywords: Deep Learning, TensorFlow, Computer Vision

P3 - Behavioral Cloning
Summary: Built and trained a convolutional neural network for end-to-end driving in a simulator, using TensorFlow and Keras. Used optimization techniques such as regularization and dropout to generalize the network for driving on multiple tracks.
Keywords: Deep Learning, Keras, Convolutional Neural Networks

P4 - Advanced Lane Finding
Summary: Built an advanced lane-finding algorithm using distortion correction, image rectification, color transforms, and gradient thresholding. Identified lane curvature and vehicle displacement. Overcame environmental challenges such as shadows and pavement changes.
Keywords: Computer Vision, OpenCV

P5 - Vehicle Detection and Tracking
Summary: Created a vehicle detection and tracking pipeline with OpenCV, histogram of oriented gradients (HOG), and support vector machines (SVM). Implemented the same pipeline using a deep network to perform detection. Optimized and evaluated the model on video data from a automotive camera taken during highway driving.
Keywords: Computer Vision, Deep Learning, OpenCV

P6 - Extended Kalman Filter
Summary: Implement the extended Kalman filter in C++. Simulated lidar and radar measurements are used to detect a bicycle that travels around your vehicle. Kalman filter, lidar measurements and radar measurements are used to track the bicycle's position and velocity.
Keywords: C++, Kalman Filter

P7 - Unscented Kalman Filter
Summary: Utilize an Unscented Kalman Filter to estimate the state of a moving object of interest with noisy lidar and radar measurements. Kalman filter, lidar measurements and radar measurements are used to track the bicycle's position and velocity.
Keywords: C++, Kalman Filter

P8 - Kidnapped Vehicle
Summary: Your robot has been kidnapped and transported to a new location! Luckily it has a map of this location, a (noisy) GPS estimate of its initial location, and lots of (noisy) sensor and control data. In this project you will implement a 2 dimensional particle filter in C++. Your particle filter will be given a map and some initial localization information (analogous to what a GPS would provide). At each time step your filter will also get observation and control data.
Keywords: C++, Particle Filter

P9 - PID Control
Summary: Implement a PID controller for keeping the car on track by appropriately adjusting the steering angle.
Keywords: C++, PID Controller

P10 - MPC Control
Summary: Implement an MPC controller for keeping the car on track by appropriately adjusting the steering angle. Differently from previously implemented PID controller, MPC controller has the ability to anticipate future events and can take control actions accordingly. Indeed, future time steps are taking into account while optimizing current time slot.
Keywords: C++, MPC Controller

P11 - Path Planning
Summary: The goal in this project is to build a path planner that is able to create smooth, safe trajectories for the car to follow. The highway track has other vehicles, all going different speeds, but approximately obeying the 50 MPH speed limit. The car transmits its location, along with its sensor fusion data, which estimates the location of all the vehicles on the same side of the road.
Keywords: C++, Path Planning

P12 - Road Segmentation
Summary: Implement the road segmentation using a fully-convolutional network.
Keywords: Python, TensorFlow, Semantic Segmentation
