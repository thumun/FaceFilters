# Face Filters 

This is our (Neha and Yamin's) final assignment for Computer Vision (CIS5810). We created a program where you can upload images, upload videos, or use webcam to try out our various filters. We have both filters that work by associating specific filters with the proper facial keypoints (for example, sunglasses with the area around one's eyes) as well as post-processing filters which apply affects to an entire image or frame. 

## How to Run 
First, pull the repo to your own system. 

Then, go to the ui.ipynb file. Make sure to choose a python kernel and then run all the cells. 

This should open a new window where you can toggle/adjust the UI in order to upload a photo, a video, or a webcam as well as to add filters and post processing effects to them. 

You can then save the resulting image/video or snapshot (in the case of a webcam) to your local systen. 

## Implemented Face Filters (and corresponding keypoints)
<img src ="https://github.com/user-attachments/assets/e073fde2-2750-4aae-87d8-e5c5e0cd44fe" width=300/>

- Hat: (36, 42) and (42, 48) 
- Glasses: (36,42) and (42, 48)
- Mustache: (48, 51) and (52, 55)
- Tie: (6, 8) and (8,9) and shifted down to be in the ‘tie area’


## Implemented Post Process Effects 
- Gaussian Blur 
- Edge Detection 
- Sepia 
- Filmgrain 
- Pixelate 
- Negative 
- Dither
- Kuwahara (Painterly) 
- Bitmap 
- Blending with a static image 
- Broken VCR 


## Demo Video 
https://drive.google.com/file/d/1nyJ3fYtAd-0Nc8-p1z3lIcPCry2BYF8V/view?usp=sharing

## Slides with more Information 
https://docs.google.com/presentation/d/1cApImXeQelXSxFUAkGBn4GYGo6EUSvbKqmWm9BXNl7o/edit?usp=sharing

## Attribution 
- Kuwahara Filter was created with the help of: https://github.com/adussault/python-kuwahara/blob/master/Kuwahara.py#L96 and https://en.wikipedia.org/wiki/Kuwahara_filter# 
- Dither pseudocode: https://en.wikipedia.org/wiki/Floyd%E2%80%93Steinberg_dithering  
- Edge Detection was made with the help of homework 2 from CIS5810
- Facial Keypoints Model: https://github.com/italojs/facial-landmarks-recognition/tree/master 
- Facial Keypoints Code Inspiration: https://github.com/iamirmasoud/facial_keypoint_detection 
