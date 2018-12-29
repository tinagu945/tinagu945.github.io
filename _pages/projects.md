---
layout: archive
title: "Projects"
permalink: /projects/
author_profile: true
---

## Internship
### Megvii (Face++). Software Engineer & Researcher
At the beginning of 2018, I took a gap semester to intern at Face++, who has been the champion of COCO contest for 2 years. In such an ambitious startup I got the chance to undertake an entire project on my own: Fastlabel. It aims to use Semi-Supervised Learning to speed up training dataset labelling. Firstly it fetches labeled data from database, feed it to the training model constantly. Meanwhile, the training model is also used for inferencing new data without labels, and after inference, multi-processing will show the images guessed by the model to the human labelers on webpage, and the users will correct some minor mistakes of the results, and submit the batches as labelled data for the next round of training. 
<br/>
Just entering Computer Science for a year, I needed to learn basically everything from scratch to become almost a full-stack. After 3 months of hard work, I finally finished the bare bone of it and had a demo to managers to show that with Fastlabel, I can finish labeling MNIST within 90 minutes, using 8 CPUs. Then I learned Design Pattern to decouple the entire software into SDK for future commercialization. 

### Uber ATG, Software Engineer
In May 2018, I came to the Core Map Team of Uber Advanced Technologies Group, which was responsible for the core algorithm for map production for Uber's Self-Driving Vehicles. However, at that time they didn’t have a official way to assess their maps’ quality. So within 3 months, I built up a AB Testing Pipeline for map comparison. It triggered the map production pipeline with 2 different software context (A and B), allowed users to define their own metrics, and finally generate a webpage report. To improve based on midterm feedbacks from my Manager Tashwin, I paid attention to details and pushed myself to be as responsible as possible.
