# People_detection_using_YOLOV5

##Steps: 
- Clone and Install YOLOv5: Clone the YOLOv5 repository and install the required dependencies.
- Upload Files: Upload the data.yaml file and the zipped dataset containing train, test, and valid folders.
- Unzip Dataset: Unzip the dataset into the /content/dataset directory.
- Train the Base Model: Train the YOLOv5 model with the base resolution and without data augmentation.
- Validate and Extract Metrics for Base Model: Validate the base model and extract metrics from the results file.
- Results: Print and compare the precision, recall, mAP@0.5, and mAP@0.5:0.95 metrics for both models.
- Test and Display Results: Perform detection on the test images and display the detection results.
