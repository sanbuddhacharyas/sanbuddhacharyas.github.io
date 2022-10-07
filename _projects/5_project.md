---
layout: page
title: Agro-Doctor
description: AGRO-DOCTOR is an agricultural robot that monitors our field, recognizes environmental variables and is intelligent enough to diagnose health condition of plants with Artificial intelligence (AI). 
img:
importance: 3
category: Competition
---

<b>Abstract:</b>
AGRO-DOCTOR is an agricultural robot that monitors our field, recognizes environmental variables and is intelligent enough to diagnose health condition of plants with Artificial intelligence (AI). It
identifies the plants with the help of object detection algorithm and automatically navigates to it. The health condition of the plant is identified with images of leaf. The robot has pH and soil humidity
sensor which measures acidity and water contain in soil. According to the health condition and soil status, it sprays the fertilizers and pesticides in required amount. It keeps health record of each individual
plants and analysis it for better health condition. The data is used by different farmers to grow similar types of crops, which reduces risk in farming.

<b>Objectives:</b>
- To minimize limitations and problems of traditional farming.
- To make agriculture smarter, efficient and computerized.

<center>
<p style="font-size:20px"> <b>Demo of our robot. </b></p>
</center>

<div class="myvideo">
   <center>
   <video  style="display:block; width:35%; height:auto;" autoplay controls loop="loop">
       <source src="https://drive.google.com/uc?export=download&id=1eq1lzGX56pLSunCvIJOSG7jsRw-dNmWq" type="video/mp4" />

   </video>
   </center>
</div>
<br />

<b>Proposed Model</b>
<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.html path="assets/img/agro_doctor/Agro_doctor_block_diagram.png" title="block_diagram" class="img-fluid rounded z-depth-1" %}
    </div>
</div>

<b>I. Introduction:</b> <br>
Nepal is an agricultural country. But due to of laborious task,
number of farmers are decreasing. Technology has touched
every sector till date either it’s from building smartphones to
satellites so, we came with the same concept-note of technology
in Agriculture “AGRO-DOCTOR, an agricultural robot” for
making agriculture smarter, efficient and computerized.

<b>Stereo Camera:</b>
A stereo camera is two
cameras of the same type
and specification set on a
straight line against either
the vertical or horizontal
plane. The resulting “disparity map” is used to
determine the distance of
objects from camera.
<div class="col-sm mt-3 mt-md-0">
    {% include figure.html path="assets/img/agro_doctor/stereo_camera.png" title="block_diagram" class="img-fluid rounded z-depth-1" %}
</div>


<b>Working of Robotic Arm</b>
<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.html path="assets/img/agro_doctor/working_robotic_arm.png" title="block_diagram" class="img-fluid rounded z-depth-1" %}
    </div>
</div>

<div class="col-sm mt-3 mt-md-0">
    {% include figure.html path="assets/img/agro_doctor/pid_control.png" title="block_diagram" class="img-fluid rounded z-depth-1" %}
</div>


<b>III. Methodology & System Setup</b>

<div class="col-sm mt-3 mt-md-0">
    {% include figure.html path="assets/img/agro_doctor/agrodoctor-working.png" title="block_diagram" class="img-fluid rounded z-depth-1" %}
</div>

<b>YOLOV2</b>
YOLO is an extremely
fast real time multi object
detection algorithm. The
algorithm applies a neural
network to an entire
image.
The
network
divides the image into an
S x S grid and comes up
with bounding boxes,
which are boxes drawn
around images and predicted probabilities for each of these
regions.

<div class="col-sm mt-3 mt-md-0">
    {% include figure.html path="assets/img/agro_doctor/yolo_working.png" title="block_diagram" class="img-fluid rounded z-depth-1" %}
</div>
<div class="col-sm mt-3 mt-md-0">
    {% include figure.html path="assets/img/agro_doctor/classification_architecture.png" title="block_diagram" class="img-fluid rounded z-depth-1" %}
</div>

Stereo vision camera is used to measure distance between robot
and plant. After measurement YoLov2 model is used to detect
tomato plants. Leaves are extracted from image of tomato plant
and finally Alexnet CNN model is used for tomato plant disease
classification.


<center>
<p style="font-size:20px"> <b>Hardwork Pay's off  </b></p>
</center>
<center>
<p style="font-size:20px"> <b>Winner of LOCUS 2019 Instrumentation. Thank you everyone. </b></p>
</center>

<div class="col-sm mt-3 mt-md-0">
    {% include figure.html path="assets/img/agro_doctor/THE_TEAM.jpg" title="block_diagram" class="img-fluid rounded z-depth-1" %}
</div>