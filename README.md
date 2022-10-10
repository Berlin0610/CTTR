# Compact Temporal Trajectory Representation for Talking Face Video Compression

## Bolin Chen&dagger;, Zhao Wang&sect;, Binzhe Li&dagger;, Shiqi Wang&dagger; and Yan Ye&sect;

### &dagger; City University of Hong Kong and &sect; Alibaba Group

#### The first two authors (Bolin Chen and Zhao Wang) contributed equally to this work

## Abstract

In this paper, we propose to compactly represent the nonlinear dynamics along the temporal trajectories for talking face video compression. More specifically, by projecting the frame into the high dimensional space, the temporal trajectories of talking face frames, which are complex, non-linear and difficult to extrapolate, are implicitly modelled in an end-to-end inference framework based upon very compact feature representation. As such, the proposed framework can accommodate ultra-low bandwidth video communication and guarantee the quality of the reconstructed videos. The proposed compression scheme is also robust and consistent against large head-pose motions, due to the delicately designed dynamic reference refresh and temporal stabilization mechanisms. Experimental results demonstrate that compared with the state-of-the-art video coding standard Versatile Video Coding (VVC) as well as the latest generative compression schemes, our proposed scheme is superior in terms of both objective and subjective quality assessment.

## Example Results (Similar Bitrate)

### For better visual comparison, please download the videos (mp4) from the "video" file.

### Example 1

![show](https://github.com/Berlin0610/CFTE2.0/blob/main/video/1.gif) 


### Example 2

![show](https://github.com/Berlin0610/CFTE2.0/blob/main/video/2.gif) 



## Code

Our previous training and inference code refers to CFTE published in DCC2022: https://github.com/alibaba-edu/temporal-evolution-inference-with-compact-feature-representation-for-talking-face-video-compression

The latest code will be announced soon. If necessary, please contact Mr. CHEN Bolin (email: bolinchen3-c@my.cityu.edu.hk) and we will help to test your data for academic development.
