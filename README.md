# Markerless Based AR #

### Introduction ###

This code repository demonstrated the augmented reality by natural features (keypoints in planar). 

### Requirements ###

1. OS Platform: Windows
2. [OpenCV](http://opencv.org/): The version should be below 3.0, because the 2.X APIs are different from 3.X somehow. Note that the OpenCV should be compliled with GL_SUPPORT (for rendering object mesh). 
3. Before you can run the code project, you should configure the correct pathes of includes, libs and dlls for aforementioned third dependencies.

### Installation ###

1. Clone the MarkerlessBasedAR repository

	```
	git clone https://github.com/imbinwang/MarkerlessBasedAR.git
	```

2. We'll call the directory that you cloned MarkerlessBasedAR into MarkerlessBasedAR_ROOT. You should print the image file `MarkerlessBasedAR_ROOT/data/PyramidPattern.jpg` and calibrate your camera in advance. 

3. Modify camera paramters in the file `MarkerlessBasedAR_ROOT/src/main.cpp`

	```
	// Change this calibration to yours:
	CameraCalibration calibration(832.35442338182474f,  832.35442338182474f, 319.50000000000000f, 239.50000000000000f);
	```

4. Run `MarkerlessBasedAR_ROOT/MarkerlessBasedAR.exe MarkerlessBasedAR_ROOT/data/PyramidPattern.jpg`.


