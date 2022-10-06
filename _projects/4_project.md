---
layout: page
title:  Arrhythmia prediction Using Convolutional Neural Network
description:
img:
importance: 3
category: fun
---

Classifies 7 different ECG arrhythmia beats (PVC, PAB, RBB, LBB,APC, VFW, VEB) and normal heart beats You can directly download Weights from https://drive.google.com/drive/folders/1qHqgoMhgqCIkqETtjKFYIAHoaoMDvunE?usp=sharing

In my project, I have used socket only to receive data from Raspberry pi. ECG Module is used with raspberry pi, which directy sends data via Socket. Received data is plotted against time series using Matplotlib. If you have 2d image of ECG signal then you can direct reisze to 128 x 128 and directly feed to self.predict, which returns one of the possible beats.