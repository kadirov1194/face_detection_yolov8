# face_detection_yolov8
Face_detection_yolov8_ultralytics

1. Install ultralytics  
pip install ultralytics

2. Set dataset.yaml file with correct path


3. import ultralytics
   ultralytics.checks()


4. Train the model
!yolo task=detect mode=train model=yolov8s.pt data=/content/drive/MyDrive/face_detection/dataset.yaml epochs=25 imgsz=640 batch=8 project=/content/drive/MyDrive/face_detection/training_results name=face


5. Results

![photo_2023-03-02_10-41-51](https://user-images.githubusercontent.com/112945491/228190279-6913ca56-fbef-42ac-949f-6e851bed7a13.jpg)
