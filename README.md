# Autonomous_Driving_Using_YOLO

class	AP in YOLOv4	AP in YOLOv3	TP&FP in YOLOv4	TP&FP in YOLOv3
**car	ap** = 73.09%	ap = 69.30%	TP = 15977, FP = 5767	TP = 15037, FP = 6829
**truck	ap** = 61.61%	ap = 51.89%	TP = 573, FP = 232	TP = 469, FP = 244
**pedestrian	ap** = 42.53%	ap = 24.20%	TP = 2192, FP = 1392	TP = 1213, FP = 1242
**bicyclist	ap** = 41.32%	ap = 15.66%	TP = 93, FP = 63	TP = 51, FP = 94
**light	ap** = 51.58%	ap = 42.93%	TP = 2298, FP = 739	TP = 1793, FP = 706
**Conclusion**: More significant improvement in low AP classes.

YOLOv4	YOLOv3
mean average precision (mAP@0.50) = 54.02 %	mean average precision (mAP@0.50) = 40.80 %


**car:** with 101314 labels
**truck:** with 6313 labels
**pedestrian:** with 10637 labels
**bicyclist:** with 1442 labels
**light:** with 12700 labels
Training Log
YOLOv4	YOLOv3
chart 2	chart
**Conclusion:** The speed of convergence in YOLOv4 is much faster than that in YOLOv3

Weights
YOLOv4	YOLOv3
yolov4-obj_10000.weights	yolov3-obj_10000.weights
How To Use
Use with YOLOv4 AlexeyAB
Environment
VM: Google Colaboratory
GPU: NVIDIA T4 Tensor GPU
NVIDIA-SMI 470.42.01 Driver Version: 460.32.03 CUDA Version: 11.2
nvcc: NVIDIA (R) Cuda compiler driver
Cuda compilation tools, release 11.0, V11.0.221
Build cuda_11.0_bu.TC445_37.28845127_0

YOLOv4	YOLOv3
Quality: 1080p	AVG FPS = 14.6	AVG FPS = 16.1
Quality: 720p	AVG FPS = 33.1	AVG FPS = 33.0
Quality: 360p	AVG FPS = 45.2	AVG FPS = 43.4
mAP	54.02 %	40.80 %
YouTube Link of Video Demo
YOLOv4	YOLOv3
Quality: 1080p	Click Me	Click Me
Quality: 720p	Click Me	Click Me
Quality: 360p	Click Me	Click Me
mAP	54.02 %	40.80 %

References
YOLOv4: Optimal Speed and Accuracy of Object Detection: https://arxiv.org/pdf/2004.10934
Training data from: https://www.kaggle.com/alincijov/self-driving-cars
Tesing data from: https://youtu.be/z1obnaqPgMA
