**ORB + SIFT Image Analysis**

This project demonstrates feature detection and matching using ORB (Oriented FAST and Rotated BRIEF) and SIFT (Scale-Invariant Feature Transform) in computer vision. 

**Overview**

Feature detection and description are fundamental tasks in computer vision applications such as:
- Image matching
- Object recognition
- Image stitching
- 3D reconstruction
- Visual SLAM

This project:
- Detects keypoints using ORB and SIFT
- Extracts feature descriptors
- Matches features between images
- Visualizes and compares results

**Algorithms Used**
1) SIFT (Scale-Invariant Feature Transform)
- Detects scale- and rotation-invariant keypoints
- Highly accurate
- Computationally intensive
- Uses floating-point descriptors

2) ORB (Oriented FAST and Rotated BRIEF)
- Fast and efficient
- Suitable for real-time applications
- Uses binary descriptors
- Less computationally expensive than SIFT

## **Requirements**
pip install -r requirements.txt
