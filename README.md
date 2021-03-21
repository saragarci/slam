# Landmark Detection & Robot Tracking (SLAM)

This project implements SLAM (Simultaneous Localization and Mapping) for a 2 dimensional world. Robot sensor measurements and movement are used to create a map of an environment from only sensor and motion data gathered by a robot, over time.

SLAM gives a way to track the location of a robot in the world in real-time and identify the locations of landmarks such as buildings, trees, rocks, and other world features. This is an active area of research in the fields of robotics and autonomous systems. 

Below is an example of a 2D robot world with landmarks (purple x's) and the robot (a red 'o') located and found using *only* sensor and motion data collected by that robot.

<p align="center">
  <img src="./images/robot_world.png" width=50% height=50% />
</p>

This project is broken down into four main notebooks:

* Notebook 1: Robot Moving and Sensing
* Notebook 2: Omega and Xi, Constraints
* Notebook 3: Landmark Detection and Tracking

## Local Environment Instructions

1. Clone the repository, and navigate to the downloaded folder.
```
git clone https://github.com/udacity/P3_Implement_SLAM.git
cd P3_Implement_SLAM
```

2. Create (and activate) a new environment, named `cv-nd` with Python 3.6. If prompted to proceed with the install `(Proceed [y]/n)` type y.

	- __Linux__ or __Mac__: 
	```
	conda create -n cv-nd python=3.6
	source activate cv-nd
	```
	- __Windows__: 
	```
	conda create --name cv-nd python=3.6
	activate cv-nd
	```
	
	At this point your command line should look something like: `(cv-nd) <User>:P3_Implement_SLAM <user>$`. The `(cv-nd)` indicates that your environment has been activated, and you can proceed with further package installations.

6. Install a few required pip packages, which are specified in the requirements text file (including OpenCV).
```
pip install -r requirements.txt
```


## Notebooks

1. Navigate back to the repo. (Also, your source environment should still be activated at this point.)
```shell
cd
cd P3_Implement_SLAM
```

2. Open the directory of notebooks, using the below command. You'll see all of the project files appear in your local environment; open the first notebook and follow the instructions.
```shell
jupyter notebook
```

3. Once you open any of the project notebooks, make sure you are in the correct `cv-nd` environment by clicking `Kernel > Change Kernel > cv-nd`.

## Credits

### Resources

[Starting project](https://github.com/udacity/P1_Facial_Keypoints). 


### Contributors

* [Sara Garci](s@saragarci.com)
* [Computer Vision Nanodegree](https://www.udacity.com/course/computer-vision-nanodegree--nd891)

## License

© Copyright 2021 by Sara Garci. All rights reserved.
