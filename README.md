# slslam
This implementation performs Stereo Line-based SLAM (SLSLAM) of our work:
"Building a 3D Line-based Map Using a Stereo SLAM," currently in a revision
process of IEEE Transactions on Robotics.

Dependencies: Ceres-solver 1.7.0, OpenCV 2.4.10, Google Flags 2.1.0, Google
Logging 0.0.0, OpenGL, GLFW

All dependencies should be installed in your system beforehand.

This code has been tested only on 64-bit linux (Ubuntu 14.04) system.

First download the code:
$ git clone https://github.com/slslam/slslam.git

Then download a zipped dataset file from:
https://drive.google.com/file/d/0B3bB8rHbc3fWNGQ3YnhLczIwNG8/view?usp=sharing
and copy it to ${source_root_dir}.

$ unzip data.zip
$ mkdir build && cd build
$ cmake ..
$ make
