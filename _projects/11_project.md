---
layout: page
title: Freeview Rendering
description: It allows generating directly the novel images with different views using the sparse images along with sparse point cloud, skipping the manual modeling stage. It doesn't require dense and accurate modeling.
img: assets/img/freeview_rendering/IMG_1945.jpg
importance: 4
category: work
---


It allows generating directly the novel images with different views using the sparse images along with sparse point cloud, skipping the manual modeling stage. It doesn't require dense and accurate modeling.<br>
<p style="font-size:30px">Pipelines:</p>
- Creates sparse point cloud for individual images
- Creates full mesh with the available point cloud.
- During rendering, it uses geometric information of each image to view the different scenes.
- The geometry of each image provides information to combine different possible images for a new perspective view at different angles.
- Since the new view is a combination of different images, it uses the blending technique to equalize the lighting, shadow, color, saturation, etc, to make it uniform and realistic.

<center>
<p style="font-size:30px">Watch some demos (Walkthrough)</p>
<video style="width:40%; height:auto;" controls loop="loop">
<source src="https://drive.google.com/uc?export=download&id=1z6RYLVyvQAhDR7sCIXWqmkfKfcqAtxjv" type="video/mp4">
</video>
<video style="width:40%; height:auto;" controls loop="loop">
<source src="https://drive.google.com/uc?export=download&id=1ChIMQ4DfAYOcdRQG8eZiKw-55BMOJN7u" type="video/mp4">
</video>
</center>

