# Framework

The workflow of our proposed method. 
![image](https://github.com/goloooo777/flip-learning/blob/main/images/framework.png)

# Environment

Python  
Pytorch  
OpenCV  
Gym  

# Usage

Code will be released soon.

# Results

1. Two testing cases of multi-agent erasing (stage 2). The blue bbox contains the nodule to be segmented. The red and green bboxes are two agents. They traverse the superpixels with actions including 1) erasing (solid yellow bbox) and 2) passing (hollow yellow bbox).

* Case1  
![image](https://github.com/goloooo777/flip-learning/blob/main/images/1_image.gif) 

* Case2  
![image](https://github.com/goloooo777/flip-learning/blob/main/images/2_image.gif)

2. Case of classification tag flipping. The left figure shows the original image with the tag 'Nodule' and the erasing process. The middle one visualizes the erasing curve including erasing area, classification score of nodule and DICE in each step. The last figure shows the image after tag flipping (i.e., with tag 'Normal tissue'). 
![image](https://github.com/goloooo777/flip-learning/blob/main/images/tag_flipping.gif)


