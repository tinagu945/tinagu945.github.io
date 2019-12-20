---
layout: archive
title: "Projects"
permalink: /projects/
author_profile: true
---

# Software Engineering Internship
## Megvii (Face++)
### Mentor: Xinyu Zhou
### Beijing, 12/2017 - 03/2018
In sophomore year I took a gap semester to intern at [Megvii](https://megvii.com/en), where I got the chance to undertake an entire project on my own: Fastlabel. It aims to use Active Learning to speed up dataset labelling. The models are trained constantly by labeled data in the pool, intervened by unlabeled batches requiring inference. The inferred batches will then be sent to the frontend interface to let the human labelers correct the wrong predictions, and after the batch becomes completely correct, it will be merged into the training dataset. As the test accuracy increases, labelers need less time to check the predictions, and thus the labeling efficiency gets improved significantly. As a result, MNIST annotation could be completed within 90 minutes, using 8 CPUs. The project was handed over to full-time employees for further development. 

## Uber ATG
### Mentor: Tashwin Khurana
### Pittsburgh, 05/2018 - 08/2018
The Core Map Team of [Uber Advanced Technologies Group](https://www.uber.com/us/en/atg/) was responsible for the core algorithm for map production for Uber's self-driving Vehicles. However, at that time they didn’t have an official way to assess their maps’ quality. So within 3 months, I built up a AB Testing Pipeline for map comparison. It triggered the map production pipeline with 2 different software context (A and B), allowed users to define their own metrics, and finally generate a webpage report about the comparisons.
