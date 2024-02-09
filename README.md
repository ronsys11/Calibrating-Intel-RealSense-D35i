# Calibrating-Intel-RealSense-D35i

## Usage
Use the camera to capture approximately 40 images of a checkerboard from several angles.
python Zhang_calibration.py --dir (path to the folder containing checkerboard images) --square_size 0.025 --width 9 --height 8 --visualize true

## Dependencies
* Python - Tested on 3.10
* NumPy - Tested on 1.22.2
* OpenCV - Tested on 4.7.0.68

## Sample Input and Result
![image](https://github.com/ronsys11/Calibrating-Intel-RealSense-D35i/assets/84351843/5029f9b2-9ccf-446a-b656-447702ae43af) <br />
![image](https://github.com/ronsys11/Calibrating-Intel-RealSense-D35i/assets/84351843/b89e77fa-cb07-4392-96fd-dd3327f41d5f)
* Calibration Matrix : <br />
[[906.86475543   0.         658.72602611] <br />
[  0.         910.6299184  352.12353876] <br />
[  0.           0.           1.        ]] <br />

 * Distortion Coefficients : [[ 8.38183773e-02  2.82077206e-01 -7.30450167e-04  1.36415171e-03  -1.56229813e+00]]


