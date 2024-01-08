# 6DMG: A 6D Motion Gesture Dataset

This repository contains the dataset, associated codes, and the PDF copy for the work in the following paper:

M. Chen, G. AlRegib, B. Juang, 6DMG: A New 6D Motion Gesture Database, Proceedings of the Second ACM Multimedia Systems Conference (MMSys), Chapel Hill, NC, USA, February 22-24, 2012.


## Introduction

Motion-based control is gaining popularity, and motion gestures form a complementary modality in human-computer interactions. To achieve more robust userindependent motion gesture recognition in a manner analogous to automatic speech recognition, we need a deeper understanding of the motions in gesture, which arouses the need for a 6D motion gesture database. Presented database contains comprehensive motion data, including the position, orientation, acceleration, and angular speed, for a set of common motion gestures performed by different users. This motion gesture database can be a useful platform for researchers and developers to build their recognition algorithms as well as a common test bench for performance comparisons.


## Dataset Link

Download the database files from Zenodo: https://zenodo.org/records/10471794

### 6DMG Dataset

Description:
Contain 28 participants (21 right-handed and 7 left-handed, 22 male and 6 female)
Last update (Apr. 25. 2011)


### 6DMG loader

Description:
6DMG loader shows how to load gestures from 6DMG database into the C++ struct.  It is a good start point to wrap 6DMG into other applications.  The code should work on major compilers, but is only tested on VS2008. 


### 6DMG viewer

Description:
6DMG viewer loads gestures and render the motion on screen.  To compile the source code of 6DMG viewer, you have to install Ogre SDK first.  See the [wiki](http://wiki.ogre3d.org/Installing+the+Ogre+SDK) for “how to”. 


### Technical Paper

The details about how the motion tracking and gesture recording are done.  This work was first presented as a 2-page abstract poster in the workshop on Gesture Recognition in CVPR11.  It will be appeared as a dataset paper in MMSys12.
