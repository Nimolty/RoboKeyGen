# RoboKeyGen
This is an official code for ICRA 2024 paper "RoboKeyGen: Robot Pose and Joint Angles Estimation via Diffusion-based 3D Keypoint Generation".

[\[PDF\]](https://arxiv.org/pdf/2403.18259) [\[Video\]](https://www.youtube.com/watch?v=oD1pSinGJqM) [\[Webpage\]](https://nimolty.github.io/Robokeygen/)

# Code Release Schedule
- [ ] Installation
- [ ] Dataset Release and Pretrained Model Release
- [ ] Training Code Release
- [ ] Inference Code Release

# Dataset Release
We have created a huge synthetic training dataset SimRGBD-Franka (~hundreds of GB). For downloading conveniently, we divide the whole dataset into six parts. color.zip includes all the color images, mask.zip includes all the mask images, ir.zip includes all the ir images, depth_60.zip includes all the ground truth depth images, simDepthImage.zip includes all the simulated depth images via stereo matching in blender, and meta.zip includes all the meta information (robot joint angles, robot pose, ground truth keypoints).
