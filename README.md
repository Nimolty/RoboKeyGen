# RoboKeyGen
This is an official code for ICRA 2024 paper "RoboKeyGen: Robot Pose and Joint Angles Estimation via Diffusion-based 3D Keypoint Generation".

[\[PDF\]](https://arxiv.org/pdf/2403.18259) [\[Video\]](https://www.youtube.com/watch?v=oD1pSinGJqM) [\[Webpage\]](https://nimolty.github.io/Robokeygen/)

# Code Release Schedule
- [ ] Installation
- [x] Dataset Release and Pretrained Model Release
- [ ] Training Code Release
- [ ] Inference Code Release

# Installation


# Dataset and Pretrained Model Checkpoints Release
## Synthetic Training Dataset SimRGBD-Franka
We have created a huge synthetic training dataset SimRGBD-Franka (~hundreds of GB). For downloading conveniently, we divide the whole dataset into six parts: *color.zip, mask.zip, ir.zip, depth_60.zip, simDepthImage.zip, and meta.zip*. We could download the dataset from the webpage [website](https://mirrors.pku.edu.cn/dl-release/SGTAPose_CVPR2023) You can download any kind of data as you want.

## Diffusion Model Training Dataset
Our diffusion model predicts 3D keypoints conditioned on 2D keypoints, without using any RGB, Depth information. Therefore, we have created a hugh training dataset only containing meta information to train the diffusion model. We can download the dataset from the [link](https://disk.pku.edu.cn/anyshare/en-us/link/AA3B25DC9F034F45AAA9DA8F231BEE8989/D1F4283611FF4B3E9B87CC68741DE68D/7CCC46B030684B41A7CF8E7AA9749E93?_tb=none) with password *irGq*.

## Real-world Testing Dataset RealSense-Franka and AzureKinect-Franka
To download the real-world testing dataset, RealSense-Franka and AzureKinect-Franka. We can download the file *Real_Test_0613.tar.gz* from the webpage [website](https://mirrors.pku.edu.cn/dl-release/SGTAPose_CVPR2023). After extracting this file, we can find 12 folders containing 12 different scenes. We have selected 9 out of 12 scenes as the final testing scenes according to the quality of annotation. The folders *1_D415_front_0, 2_D415_front_1, 6_D415_left_1, 12_D415_right_1* constitutes RealSense-Franka, and the folders *3_kinect_front_0, 4_kinect_front_1, 8_kinect_left_1, 9_kinect_left_0, 10_kinect_right_1* constitutes AzureKinect-Franka. 

## Pretrained Model Checkpoints
We can download the pretrained checkpoints from the [link](https://disk.pku.edu.cn/anyshare/en-us/link/AA9B442792675948E7BAB811DFC5713E1B?_tb=none&expires_at=1970-01-01T08%3A00%3A00%2B08%3A00&item_type=folder&password_required=true&title=RoboKeyGen_ckpt&type=anonymous) with password *b2MV*.
