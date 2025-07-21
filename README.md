# MSTLD-dataset
The MSTLD is dataset covers a very wide range of scenarios, especially focusing on the operational complexity of power transmission lines and safety-critical scenarios, filling the gap in existing datasets. 
# Introduction to Dataset Characteristics 

Accurate detection and segmentation of power lines from images are critical for ensuring the safe and stable operation of power grids. 
However, existing transmission line datasets lack complex and diverse scenarios, hindering the development of data-driven safety inspection methods.
To address this, we present the Real-time Multi-scenario Power Line Dataset (MSTLD: ), a novel dataset containing 4000 images focusing on safety-critical complex scenarios such as nighttime and extreme weather conditions.
MSTLD:  is derived from 10,000 raw frames randomly captured by cameras mounted on transmission towers. 
Invalid images were first filtered out, and the proportion of challenging scenarios (e.g., extreme weather and low-light conditions) was increased to render the dataset highly challenging.
An adaptive cropping method based on Mask-RCNN was then proposed to retain power line features while reducing background noise and redundant information. 
To achieve high-quality annotations with reduced time costs, a hybrid annotation strategy combining adaptive histogram equalization, multi-scale labeling, and fine-tuned U-Net pre-annotation was developed. 


The dataset covers multiple scenarios, and several groups of representative scenarios along with their corresponding annotation information are shown in the figure.
![标注数据集](https://github.com/user-attachments/assets/2e66e21c-12a4-47c1-b873-ae9960ac4051)
