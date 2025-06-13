# YOLO-MIO-TCD: Traffic Object Detection
This project uses the YOLOv8 object detection model trained on the MIO-TCD dataset to detect various types of vehicles in traffic surveillance footage. It's built for smart traffic management systems and supports both classification and localization of traffic objects.

## Contents
- Trained YOLOv8 models (`yolov8n.pt`, `yolo11n.pt`)
- Dataset folders: `MIO-TCD Classification`, `MIO-TCD Localization`
- Training and inference scripts

## Usage
- Train: `python yolo_train.py`
- Inference: `python yolo.py --weights yolov8n.pt --source path/to/image_or_video`

## Credits
- Ultralytics YOLOv8
- MIO-TCD Dataset

License: MIT
