# Google-Colab-13
Social distance detector. 
- Load cv2, numpy and matplotlib.
- Read and show image.
- Resize image and create a blob.
- Get labels from Coco.names.
- Load Yolo3 model and run blob on model.
- Retrieve bounding boxes for persons identied in image.
- Calculate distance between persons and flag those not in social distance.
- Draw green bounding boxes for those in social distance and red for those not in social distance.
