
# yolov8-object-tracking

### Features
- Object Tracks
- Different Color for every track
- Video/Image/WebCam/External Camera/IP Stream Supported


### Steps to run Code

- Clone the repository
```
git clone https://github.com/noorkhokhar99/yolov8-object-tracking.git
```

- Goto cloned folder
```
cd yolov8-object-tracking
```

- Install the ultralytics package
```
pip install ultralytics==8.0.0
```

- Do Tracking with mentioned command below
```
#video file
python yolo/v8/detect/detect_and_trk.py  model=yolov8m.pt source="test.mp4" model=yolov8m.pt show=True

#imagefile
python yolo/v8/detect/detect_and_trk.py model=yolov8m.pt source="path to image" model=yolov8m.pt

#Webcam
ppython yolo/v8/detect/detect_and_trk.py model=yolov8m.pt source=0 model=yolov8m.pt show=True

#External Camera
python yolo/v8/detect/detect_and_trk.py model=yolov8m.pt source=1 model=yolov8m.pt show=True
```

- Output file will be created in the working-dir/runs/detect/obj-tracking with original filename


### Results
<table>
  <tr>
    <td>YOLOv8s Object Tracking</td>
  </tr>
  <tr>
    <td><img src="https://github.com/noorkhokhar99/yolov8-object-tracking/blob/main/Blue%20%26%20Yellow%20Professional%20Future%20Technology%20Presentation%20(1).png"></td>
  </tr>
 </table>

### References
- https://github.com/abewley/sort
- https://github.com/ultralytics/ultralytics



If you find my videos useful,  I would love your support on Pyresearch: https://www.youtube.com/c/Pyresearch
