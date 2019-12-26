---
layout: archive
title: "Research"
permalink: /research/
author_profile: true
---


# Intermediate Level Adversarial Attack for Enhanced Transferability
### Qian Huang\*, Isay Katsman\*, Horace He\*, Zeqi Gu\*, Serge Belongie, Ser-Nam Lim (*: Equal contribution)
### Cornell University, 09/2018 - 03/2019
Neural networks are vulnerable to adversarial examples, malicious inputs crafted to fool trained models. Adversarial examples often exhibit black-box transfer, meaning that adversarial examples for one model can fool another model. However, adversarial examples are typically overfit to exploit the particular architecture and feature representation of a source model, resulting in sub-optimal black-box transfer attacks to other target models. We introduce the Intermediate Level Attack (ILA), which attempts to fine-tune an existing adversarial example for greater black-box transferability by increasing its perturbation on a pre-specified layer of the source model, improving upon state-of-the-art methods. We show that we can select a layer of the source model to perturb without any knowledge of the target models while achieving high transferability. Additionally, we provide some explanatory insights regarding our method and the effect of optimizing for adversarial examples using intermediate feature maps.

\[[Arxiv](https://arxiv.org/abs/1912.10154)\] \[[Code](https://github.com/richardaecn/dataset-granularity)\]

# Measuring Dataset Granularity
### Yin Cui\*, Zeqi Gu\*, Dhruv Mahajan, Laurens van der Maaten, Serge Belongie, Ser-Nam Lim (*: Equal contribution)
### Cornell University, 04/2018 - 11/2019
Despite the increasing visibility of fine-grained recognition in our field, “fine-grained” has thus far lacked a precise definition. In this work, building upon clustering theory, we pursue a framework for measuring dataset granularity. We argue that dataset granularity should depend not only on the data samples and their labels, but also on the distance function we choose. We propose an axiomatic framework to capture desired properties for a dataset granularity measure and provide examples of measures that satisfy these properties. We assess each measure via experiments on datasets with hierarchical labels of varying granularity. When measuring granularity in commonly used datasets with our measure, we find that certain datasets that are widely considered fine-grained in fact contain subsets of considerable size that are substantially more coarse-grained than datasets generally regarded as coarse-grained. We also investigate the interplay between dataset granularity with a variety of factors and find that fine-grained datasets are more difficult to learn from, more difficult to transfer to, more difficult to perform few-shot learning with, and more vulnerable to adversarial attacks.

\[[Arxiv](https://arxiv.org/abs/1907.10823)\] \[[Code](https://github.com/CUVL/Intermediate-Level-Attack)\]


# Creative Text Design Agent
### Mentors: Zhaowen Wang, Jose Echevarria 
### Adobe Research, 05/2019 - Present
Designing posters can be time-consuming, and the subtask of designing text bodies on it is no exception. Therefore, we propose a recommendation system called Creative Agent for Text Design that helps designers making decision more efficiently by suggesting diverse and plausible values for font face, color, size, position and line breaks. We made valuable attempts at solving the issue of long-tail distribution and subjectivity of ground truth of the dataset, and increasing the diversity of model predictions.

# Annotation Tool for iMat-Fashion Dataset 
### Advisor: Serge Belongie; Collaborators: Mengyun Shi, Menglin Jia, Fisher Yu, Wenqi Xian, Junwei Bai, etc.
### Cornell University, 09/2018 - 01/2019
Responsible for developing the annotation tool of the [Fashionpedia](https://fashionpedia.github.io/home/index.html) Dataset, which is currently the largest, most fine-grained machine learning dataset in fashion. I customized the annotation software from Scalabel of Berkeley DeepDrive to meet the specific needs of this dataset. Given an image with segmentation masks over each piece of the model's apparel, the labeler needs to annotate every subobject its attributes (e.g. styles, nickname, texture, etc.) and relations with other objects (e.g. is a button/sleeve of), and thus form a knowledge graph for the entire outfit. This dataset was the target benchmark of [FGVC6 Workshop at CVPR 2019](https://sites.google.com/view/fgvc6/home).
    
\[[Workshop slide](https://drive.google.com/file/d/1Ah5haDF6kFioQzy45-HKTsxZCqGwondf/view)\]

 


