# Facemask_Detection

Link to the dataset https://drive.google.com/drive/u/0/folders/1XDte2DL2Mf_hw4NsmGst7QtYoU7sMBVG

Two phases are involved in this project

Phase 1:
1. Load and Preprocess the data.
2. Build a classifier using CNN's with Tensorflow(that should be able to classify with best possible accuracy).

Phase 2:
1. Detect faces from video/image stream(haarcascade_frontalface_default.xml)
2. Extract face ROI from the above step
3. Apply each face ROI on trained classifier to determine 'with_mask' or 'without_mask' with confidence percentage.

# Installation and run
1. I have used Tensorflow-gpu 2.1.2 and python 3.7.
2. Download and unzip the dataset
3. Download this Repository via GIT or zip. if you download from zip then unzip that downloaded file.
4. Open 'Detection on video and images.ipynb' file and replace the paths of model file and cascadeclassifier file.
5. Test on webcam or give the image in which you want to detect Mask(Mentioned in code).
