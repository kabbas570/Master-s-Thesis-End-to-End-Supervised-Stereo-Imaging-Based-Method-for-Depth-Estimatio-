# Master-s-Thesis-End-to-End-Supervised-Stereo-Imaging-Based-Method-for-Depth-Estimation
Depth estimation is an ill-posed problem in computer vision, and solving this problem is very important for robot navigation and obstacle avoidance. This Master’s dissertation investigates a supervised end-to-end encoder-decoder network for accurate depth estimation and consolidates the idea the use of stereo images pair can significantly improve depth measurement performance. In the proposed architecture, two encoders and one decoder are employed where two encoders extract the features of stereo images and the decoder reconstructs the depth map. An attention module named, Spatial and Channel Attention Module (SCAM) is incorporated to combine and emphasize the most meaningful features.  
For better gradient propagation and faster convergence, the decoder module reuses the feature maps of encoders in two different ways: (1) through concatenation, and (2) element-wise addition using non-identity mapping. Extensive ablation studies are conducted to evaluate the effectiveness of the proposed architecture and its strategies. The experiments are conducted on three publicly available datasets: (i) RGB+D Scene Dataset, (ii) Cityscapes Dataset, and (iii) KITTI Dataset. The results demonstrate that the proposed architecture outperforms the existing state-of-the-art networks for most of the evaluation metrics reported for the depth estimation tasks. In addition, the end-to-end training and inference phases make the proposed method more feasible for real-time applications.
## Keywords: 
Depth Estimation, Stereo Images, Encoder-Decoder Architecture,Attention for CNNs, Skip Connections

# Results and Discussions

## 1. RGB+D Scene Dataset
![image](https://user-images.githubusercontent.com/56618776/126770089-aebeeaa1-271f-4c0d-aea5-6f7de7cbd411.png)
![image](https://user-images.githubusercontent.com/56618776/126770151-c347ffa8-1edb-4d39-8649-08a3264347af.png)

## 2. CityScapes Dataset
![image](https://user-images.githubusercontent.com/56618776/126769709-32179923-5766-4be8-8714-c3460c5d1803.png)
![image](https://user-images.githubusercontent.com/56618776/126769831-5f51ade6-e9aa-4c1f-91b5-4c54f93dbe96.png)

## 3. KITTI Dataset
![image](https://user-images.githubusercontent.com/56618776/126769919-8736d48f-6817-4cd9-b53a-ac2527246d2e.png)
![image](https://user-images.githubusercontent.com/56618776/126769964-a7122d7d-e6ff-488e-aa30-df273f975ca9.png)



