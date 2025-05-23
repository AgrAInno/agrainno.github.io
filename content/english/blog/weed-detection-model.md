---
title: "Our Advanced Weed Detection Model"
date: 2024-11-06T10:00:00+01:00
author: Chenghao Lu
image : "images/blog/maskrcnn_example.jpg"
bg_image: "images/feature-bg.jpg"
categories: ["Artificial Intelligence"]
tags: ["Advice","Technology"]
description: "this is meta description"
draft: false
type: "post"
---

Weeds significantly impact agricultural production, and traditional weed control methods often harm soil health and the environment. This study aims to develop deep learning-based segmentation models to identify weeds in potato fields captured by Unmanned Aerial Vehicle (UAV) orthophotos and to explore the effects of weeds on potato yield.

UAVs were used to collect RGB data from potato fields, flying at an altitude of 10 meters. The Real-ESRGAN Super-Resolution model was applied to enhance image resolution. We used the Segment Anything Model (SAM) for semi-automatic annotation, followed by training YOLOv8 and Mask R-CNN models for segmentation. Additionally, ANOVA and linear regression were used to analyze the effects of weed pressure and nitrogen fertilizer on yield outcomes.

Results showed high segmentation performance with mAP50 scores of 0.902 (YOLOv8) and 0.920 (Mask R-CNN), while the Real-ESRGAN-enhanced YOLOv8 achieved 0.909. Accuracy decreased to 0.86 when multiple weed types were present.

![model inference](/images/blog/maskrcnn_example.jpg)

🔗 [Read the full paper](https://www.biorxiv.org/content/10.1101/2024.08.13.607729v1.full)