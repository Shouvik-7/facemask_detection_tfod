# facemask_detection_tfod

![pred_mask](https://user-images.githubusercontent.com/64649488/138548145-a0a4cf64-fe85-4ce4-957c-8e7c2870dd66.gif)

Model: ssd_mobilenet_v2_fpnlite_640x640_coco17_tpu-8
graphical image annotation tool: labelImg

## Training 
1. Setup tfod -> https://tensorflow-object-detection-api-tutorial.readthedocs.io/en/latest/install.html
2. Copy labelled dataset into Tensorflow/workspace/images/train and test folders
3. training.ipynb 

## Detection
run detect.py for face mask detection through webcam
