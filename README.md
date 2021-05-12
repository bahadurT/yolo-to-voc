# Convert-YOLO-to-PascalVOC

Last Page Update: 12-05-2021

A python script to convert YOLO into Pascal VOC 2012 format. It generates xml annotation file in PASCAL VOC format for Object Detection.



## Notes
 
 * Make sure you have the dependencies listed on yolo_to_voc.py. 
 
 * Update root path (where this script lies) in line 46. ``ROOT = 'data'``. 
 
 * Let's say that you have a custom dataset, which is not included in COCO. eg ship. Add its name to ``YOLO_CLASSES=()``, in the first position.
 
 * Remove images that are already in /data/images, /data/labels and /data/xml.
 
 * Put all your images at /data/images folder.
 
 * Put corresponding annotations (.txt files) to /data/labels
 
 
##  Prerequisites (my environment)

* Python 3.8.3

* Numpy

* Opencv 

 
 ## Usage
 
 Please to run this script use the command below :
 
```
python3 yolo_to_voc.py
```
 
 or 
 
```
python yolo_to_voc.py

```
