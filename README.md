# **FaceMaskIdentityRecognition**
- An investigation into recognizing individuals whilst still wearing a mask. 

## GitHub:
- Github contains source code for the jupyter notebooks, website, and demo video.
- https://github.com/HughN7/FaceMaskIdentityRecognition

## Code Structure:
- Jupyter Notebooks for models
- HTML for webpage

## Demo Instructions:
- Demo link (no download): https://drive.google.com/drive/folders/1xPhQqDeVPCzEsdDdQ2Dvq1yV-jJqNcZR?usp=sharing

To do it manually:
- Download "IdentityRecognitionDemo" folder from this repository
- Download the two larger weights:
  - https://drive.google.com/file/d/1FlupFAxX8tfSRzPLyTcQtuP2XPZPFyX8/view?usp=sharing
  - https://drive.google.com/file/d/1HENJ5krAr2RxCXKJWcQGEpwqpcR7Opd3/view?usp=sharing
- Place weights into "IdentityRecognitionDemo" folder
- Upload entire folder onto Google Drive. Do not nest folder under any other folders in Google Drive. 
- Enter the folder and open IdentityRecognitionDemo.ipynb in Colaboratory
- Run the Notebook

## Frame Script:
- 'LabelVideoFramesScript.ipynb' is a google colaboratory script. 
  - Accepts a single video with a couple settings within the file that can be modified
  - Video should be the target user facing the camera. 
  - Outputs zip file containing frames + labels in YOLOv3 format. 
    - Use tool such as roboflow to convert to PascalVoc if necessary. 
  - **To use this, you will need to modify it to point to the location of your stored video file**
  - Script has Options to:
    - Capture whole face, 
    - Half face, 
    - Eye region 
    - Convert into Local Binary Pattern images
    - Option to only parse video into frames (for other models such as resnet)
