---
layout: page
title: Automatic_UV_Wrapping_Tool
description: Wrapping the best appropriate texture from all possible images to a 3D mesh mitigating the modeler's burden for searching, cropping (using Photoshop), or aligning the image with a 2D UV map.
img: assets/img/uv_mapping.jpeg
importance: 4
category: work
---

Wrapping the best appropriate texture from all possible images to a 3D mesh mitigating the modeler's
burden for searching, cropping (using Photoshop), or aligning the image with a 2D UV map.<br>

<b>Technologies used:</b> Image segmentation, Image Classification, Homographic transformations, Image
painting, Image blending, Linux, Python, Open3D, OpenCV, Tensorflow, Scikit-Learn, Meshlab<br>

<p style="font-size:30px">UV wrapping Assitant features:</p>
- It suggests the best appropriate texture from all possible images to wrap a mesh so the modeler doesn't need to take burned for searching, cropping (using photoshop), or aligning the image with a 2D UV map. Therefore, it can save most of the time for the modeler.
- The suggestions are recommended to the users only if the confidence of texture wrapping to a mesh is high. It helps to reduce the human interaction to correct the fault.
- If the suggested texture is slightly misaligned then it has features to rearrange the texture but if there is much work to be done in the suggestions then users have the option to ignore the suggestions. We can set the confidence threshold high to avoid this problem.

<center>
<p style="font-size:20px"> <b>Demonstration of UV wrapping tool </b></p>
</center>

<center>
<video width="320" height="240" controls>
<source src="https://drive.google.com/uc?export=download&id=1I0SO6lD1Xb2nMn3XbHVoU9bV25Xxp92O" type="video/mp4">
</video>

