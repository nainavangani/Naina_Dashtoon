# Naina_Dashtoon

For Dataset , download it from https://drive.google.com/drive/folders/1dG4GZ_v3EPRNqDb0DrGXhmfSjoR403G1?usp=drive_link
For saved weights for Fast Style Transfer implementation also, download from drive link.

Style Transfer Notebook :
This is an implementation of the Style Transfer Technique proposed by https://arxiv.org/abs/1508.06576
### Requirements
* torch
* torchvision
* PIL

Check out [Jupyter notebook](<./Style Transfer.ipynb>) for description of the style transfer technique.

Overall, this code combines deep learning and optimization techniques to create a stylized image that merges the content of one image with the artistic style of another. The style transfer is achieved by iteratively updating the pixels of an initial image to minimize a combined content and style loss. The result is a visually appealing image that inherits both the content and style characteristics of the input images.

Fast Style Transfer Notebook :
I tried to use a pre trained model and existing weights for the task. The model is trained on only 3 style images and performed well for them. It can convert any content image into an image with these 3 styles in it. 

Limitations:
Due to constraints in computational resources, I encountered challenges in constructing an improved model within the given timeframe. I dedicated the initial two days to comprehending the problem statement, extensively researching relevant literature and exploring various research papers. Unfortunately, the model I attempted to implement during the subsequent two days did not yield satisfactory results. However, it is worth noting that with access to superior GPUs, alternative models such as AdaIn, CAST, among others, could be effectively employed. These models exhibit enhanced performance across diverse style images and demonstrate adaptability in varying scenarios.
