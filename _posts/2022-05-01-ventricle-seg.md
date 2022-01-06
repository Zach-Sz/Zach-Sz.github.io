---
title: Deep Learning Ventricle Segmentation
author: Zach
layout: post
---

This project was a part of my Master's research where the goal was to create an automatic deep learning segmentation approach which performed quickly and provided accurate segmentation results. We used the U-Net model as our baseline which is useful for small datasets like our own and well-suited for 3D ultrasound data. Some of our earlier preliminary work can be seen in our conference paper [here](https://doi.org/10.1117/12.2581749) which looked into 2D multiplane models for solving our problem.

We later published a journal paper describing a fully automated method that exceeds the SPIE work and current state of the art work for ventricle segmentation. This work uses a 3D U-Net ensemble and can predict results in ~5 seconds. This work is described [here](https://doi.org/10.1002/mp.15432) with a link to the github repository [here](https://github.com/Zach-Sz/3D-U-Net-Ensemble-for-3D-US-Images) that will be updated as the code is ready.
