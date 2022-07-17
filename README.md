# Detect Disease On Coffee Leaves Using YOLOv4
---

## Download data from roboflow as YOLO darknet format
<pre>
!pip install roboflow

from roboflow import Roboflow
rf = Roboflow(api_key="mUdJjmR80LZIZmA8wAfq")
project = rf.workspace("nguyen-phu-vinh").project("coffee-leaves-hzi6b")
dataset = project.version(1).download("darknet")
</pre>

## Data

<img src='storage/data.png' style='display: block; margin-left: auto; margin-right:auto; width: 70%'>

### Class 0:
<img src='storage/vidusauvebua.jpg' style='display: block; margin-left: auto; margin-right:auto; width: 40%'>

### Class 1:
<img src='storage/viduphantrang.jpg' style='display: block; margin-left: auto; margin-right:auto; width: 40%'>

### Class 2:
<img src='storage/vidurisat.jpg' style='display: block; margin-left: auto; margin-right:auto; width: 40%'>

### Class 3:
<img src='storage/vidudomrong.jpg' style='display: block; margin-left: auto; margin-right:auto; width: 40%'>

## Result
<img src='storage/chart.png' style='display: block; margin-left: auto; margin-right:auto; width: 40%'>
<img src='storage/result.png' style='display: block; margin-left: auto; margin-right:auto; width: 40%'>
