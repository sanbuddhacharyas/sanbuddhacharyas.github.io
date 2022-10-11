---
layout: page
title: AI Chess Playing robot
description: Built a robot to play chess physically with a human. Each move is generated using the alpha-beta pruning algorithm. Computer vision is used for the detection of the board position.
img: assets/img/chess_game/cover_pic.png
importance: 3
category: Competition
---

<p style="font-size:25px"> <b>My Contribution: </b></p>


<p style="font-size:20px"> <b>Chess Board Tracker</b> (Computer Vision)</p>

Implemented the haar cascade algorithm to find the corners of squares. Used image subtraction and
blob detection algorithms to find the initial and final position of the pieces. Performed image filtering to remove noises like shadow and lighting. Used hand detection to signal the move completion.<br>
<b>Technologies used:</b> Mobile Camera, Haar cascade algorithm, Blob detection, Hand detection, Image
subtraction, OpenCV, Numpy, C++, SFML


<p style="font-size:20px"> <b>Chess Algorithm</b></p>

We used Alpha-beta pruning algorithm. Alpha-beta pruning is a technique for enormously reducing the size of your game tree. Currently using the negamax algorithm we are searching
every reply to every move in the tree. In the average chess position there
are about 30 legal moves, and let's say for sake of argument that our
program analyses 50,000 moves per second. Now, let's see how deep we
can search.

Please find full report here
<iframe src="/assets/pdf/OOP_CHESS_REPORT.pdf" width="100%" height="500px"> </iframe>
<br>
<center>
<p style="font-size:30px"> <b>YR-ARM Version-1. </b></p>
</center>

I combined the knowledge of chess board tracker and chess algorithm to built an AI chess playing Robot.<br>
Find the videos of the robot below. 
<div class="myvideo">
   <center>
   <video  style="display:block; width:35%; height:auto;" controls loop="loop">
       <source src="https://drive.google.com/uc?export=download&id=1ZI29-g1JQARcdBJR4ennNYavTX-hYLVI" type="video/mp4" />

   </video>
   </center>
</div>

<br />

<center>
<p style="font-size:30px"> <b>YR-ARM Version-2. </b></p>
</center>

<center>Being ready for the competition, Sirjana the innovation.</center>
<div class="myvideo">
   <center>
   <video  style="display:block; width:35%; height:auto;" controls loop="loop">
       <source src="https://drive.google.com/uc?export=download&id=1LYII8v4zfkDZ0o6YwMwyLIpP3EuMxrZd" type="video/mp4" />

   </video>
   </center>
</div>

<div class="myvideo">
   <center>
   <video  style="display:block; width:35%; height:auto;" controls loop="loop">
       <source src="https://drive.google.com/uc?export=download&id=1QTXsd3KQGfnrsR-QtBmMfEtYkqH8C6fK" type="video/mp4" />
   </video>
   </center>
</div>


<center>
<p style="font-size:20px"> <b>Hardwork Pay's off  </b></p>
</center>
<div class="col-sm mt-3 mt-md-0">
    {% include figure.html path="assets/img/chess_game/srijana.jpg" title="block_diagram" class="img-fluid rounded z-depth-1" %}
</div>
<center>
<p style="font-size:20px"> <b>Winner of Sirjana The Innovation </b></p>
</center>
<center>
<p style="font-size:20px"> <b>Thank you everyone.</b></p>
</center>

<div class="col-sm mt-3 mt-md-0">
    {% include figure.html path="assets/img/chess_game/winner.jpg" title="block_diagram" class="img-fluid rounded z-depth-1" %}
</div>
