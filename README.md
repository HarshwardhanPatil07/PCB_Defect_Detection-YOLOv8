# PCB_Defect_Detection-YOLOv8
PCB (Printed Circuit Board) defect detection is a critical aspect of electronics manufacturing to ensure the quality and reliability of electronic products. Detecting defects in PCBs helps prevent issues such as electrical failures, malfunctioning devices, and costly recalls. 
#Set Up Your Development Environment:
# Installation
Ensure you have Python and relevant libraries (PyTorch, OpenCV, etc.) installed.
Install YOLOv8 from the official repository: https://github.com/ultralytics/yolov5 or you can simply run this command
```bash
pip install ultralytics
```
For Dataset here I have used Roboflow uploaded dataset

# Training
Use YOLOv8 to train your model on the annotated dataset.
<a href="https://colab.research.google.com/drive/1shdXGWP7YIF5FMhe3j6DJqxyTw_9E22Z?usp=drive_link">Google Collab Link</a> is provided for the same. Evaluate the model's performance using metrics such as precision, recall, and mean average precision (mAP).

# Dataset

You can use Dataset with <a href="https://roboflow.com/">Roboflow</a> to make custom Annotations in your Dataset
