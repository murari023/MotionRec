# MotionRec
This repository contains a Keras implementation of the paper 'MotionRec: A Unified Deep Framework for Moving Object Recognition' accepted in WACV 2020. To the best of our knowledge, this is a first attempt for simultaneous localization and classification of moving objects in a video, i.e. moving object recognition (MOR) in a single-stage deep learning framework.

# Source Code Available Here
https://github.com/lav-kush/MotionRec

# Description
Due to lack of available benchmark datasets with labelled bounding boxes for MOR, we created a new set of ground truths by annotating 42,614 objects (14,814 cars and 27,800 person) in 24,923 video frames from CDnet 2014 dataset. We selected 16 video sequences having
21,717 frames and 38,827 objects (13,442 cars and 25,385 person) for training. For testing, 3 video sequences with 3,206 frame and 3,787 objects (1,372 cars and 2,415 person) were chosen. We created axis-aligned bounding box annotations for moving object instances in all the
frames.

# Paper
[MotionRec: A Unified Deep Framework for Moving Object Recognition](http://openaccess.thecvf.com/content_WACV_2020/html/Mandal_MotionRec_A_Unified_Deep_Framework_for_Moving_Object_Recognition_WACV_2020_paper.html)

# BibTex
@InProceedings{Mandal_2020_WACV,
author = {Mandal, Murari and Kumar, Lav Kush and Saran, Mahipal Singh and vipparthi, Santosh Kumar},
title = {MotionRec: A Unified Deep Framework for Moving Object Recognition},
booktitle = {The IEEE Winter Conference on Applications of Computer Vision (WACV)},
month = {March},
year = {2020}
}

# Dataset-Link
https://drive.google.com/open?id=16hC3S0Vuz9ZNC2sxI7UuONiBtkA8S_lA

Contact: Murari Mandal(murarimandal.cv@gmail.com)

# Sample Results
![MotionRec](/qualitative_results_400x600_25fps.gif)
