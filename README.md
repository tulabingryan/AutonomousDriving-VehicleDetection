# Vehicle Detection
[![Udacity - Self-Driving Car NanoDegree](https://s3.amazonaws.com/udacity-sdc/github/shield-carnd.svg)](http://www.udacity.com/drive)


## Main Goal
  - Write a software pipeline to detect vehicles in a video

## Steps
Steps of this project are the following:
* Perform a Histogram of Oriented Gradients (HOG) feature extraction on a labeled training set of images and train a classifier Linear SVM classifier
* Apply a color transform and append binned color features, as well as histograms of color, to HOG feature vector. 
* Note: for first two steps features are normalized and selection for training and testing are done in random.
* Implement a sliding-window technique and use trained classifier to search for vehicles in images.
* Run pipeline on a video stream and create a heat map of recurring detections frame by frame to reject outliers and follow detected vehicles.
* Estimate a bounding box for vehicles detected.

Links to the labeled data for [vehicle](https://s3.amazonaws.com/udacity-sdc/Vehicle_Tracking/vehicles.zip) and [non-vehicle](https://s3.amazonaws.com/udacity-sdc/Vehicle_Tracking/non-vehicles.zip) examples to train the classifier.  These example images come from a combination of the [GTI vehicle image database](http://www.gti.ssr.upm.es/data/Vehicle_database.html), the [KITTI vision benchmark suite](http://www.cvlibs.net/datasets/kitti/), and examples extracted from the project video itself.   Recently released [Udacity labeled dataset](https://github.com/udacity/self-driving-car/tree/master/annotations) to augment training data are available.

Some example images for testing the pipeline on single frames are located in the `test_images` folder.  Saved examples of the output from each stage of the pipeline are in the folder called `ouput_images`. 

**As an optional challenge** Do simultaneous lane-finding and vehicle detection!

**If you're feeling ambitious** Implement this project on a new video!
