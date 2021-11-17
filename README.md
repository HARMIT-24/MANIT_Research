# @author HM
# created on Jun 2
# dataset author HM
# Place of origin Bhopal
Run the program using command:
cd folder_path\yolov5-master
python detect.py [-h] [--weights WEIGHTS [WEIGHTS ...]] [--source SOURCE] [--img-size IMG_SIZE] [--conf-thres CONF_THRES] [--iou-thres IOU_THRES] [--device DEVICE] [--view-img][--save-txt] [--save-conf] [--nosave] [--agnostic-nms] [--augment] [--update] [--project PROJECT] [--name NAME] [--exist-ok]

The weights learnt from Coconut are in models/best.pt and models/last.pt
The weights are also stored as yolo5s.pt alongside the detect.py file for convinience and easy running.
# Alternatively load the whole folder in say Raspberry Pi and run the detect.py script as it is, mannually.
# The default port for webcam is specified as 0
