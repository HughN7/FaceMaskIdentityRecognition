# **FaceMaskIdentityRecognition**
- An investigation into recognizing individuals whilst still wearing a mask. 

## GitHub:
- Github contains source code for the jupyter notebooks, website, and demo video.
- https://github.com/HughN7/FaceMaskIdentityRecognition

## Code Structure:
- Jupyter Notebooks for models
- HTML for webpage

## Demo Instructions:
- Refer to link: https://drive.google.com/drive/folders/1xPhQqDeVPCzEsdDdQ2Dvq1yV-jJqNcZR?usp=sharing
- Uploading files to Github resulted in some errors due to size. 

## Frame Script:
- 'LabelVideoFramesScript.ipynb' is a google colaboratory script. 
  - Accepts a single video with a couple settings within the file that can be modified
  - Video should be the target user facing the camera. 
  - Outputs zip file containing frames + labels in YOLO format. 
    - Use tool such as roboflow to convert to PascalVoc if necessary. 
  - Options to capture whole face, half face, eye region and even convert into Local Binary Pattern images if necessary. 
