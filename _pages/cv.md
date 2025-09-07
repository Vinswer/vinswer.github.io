---
layout: archive
title: "CV"
permalink: /cv/
author_profile: true
redirect_from:
  - /resume
---

{% include base_path %}

Education
======
* M.S. in  Bioinformatics , Wageningen University & Research, 2025
* B.S. in  Animal Science, South China Agricultural University, 2021

Project experience
======
* Summer 2025: Deep Learning-Based Multiclass Cancer Classification from Histopathology 
Images
  * Medical image preprocessing: Implemented color normalization and H&E staining separation algorithms using 
Python based on the PatchCamelyon dataset to address histopathology image variations
  * Deep Learning Model Development: Developed multi-class cancer classification models using PyTorch with 
medical-specific architectures, including enhanced ResNet50, EfficientNet, and attention mechanisms. Integrated 
statistical evaluation of training, validation, and performance metrics (AUC, sensitivity, specificity).
  * Model Interpretation: Applied Grad-CAM visualization to generate heatmaps highlighting discriminative regions, 
enabling pathologists to interpret and validate results.

* Spring 2024: Master thesis **Automatic estimate chicken pose using Python pipeline**
  * Data pre-processing: Python and C++ were used to write scripts for video frame extraction and batch process largescale farm monitoring video data 
  * Deep learning model development: CVAT was used for image annotation and trained key point detection models 
based on the YOLOv8 architecture, achieving 99.5% accuracy in poultry posture recognition tasks, with complete 
experience from data annotation to model deployment 
  * Extracedt chicken posture features (e.g. body tilt) from the key point coordinates output by YOLO, which can 
successfully identify abnormal behavior of lameness
  * Supervisor: Dr. Marjaneh Taghavi, Dr. Istvan Fodor & Dr. Malou van der Sluis

* Spring 2025: Internship at Lely **Use Few-Shot Learning to identify cows**
  * Developed and implemented an image-based deep learning model, achieving 79.9% accuracy and 96.1% Top-5 
accuracy in a farm with 40 cows under limited labeled data conditions (only 10 images per cow)
  * Optimized model performance by fine-tuning hyperparameters to strike a balance between accuracy and 
computational efficiency.
  * Combined image features and spatial coordinate information, the machine learning model optimized the Few-Shot 
Learning prediction results, increasing the final recognition accuracy to 86.4%
  * Worked in the machine vision team
  
Skills
======
* Programming language: Python, R, shell for Linux, C++
* Data analysis: R, Python
* Modelling: Statistical models, Network models, Machine learning models (Decision Trees and Random Forests, 
Support vector machines, Clustering and k-means, Hidden Markov Models, Neural Networks), Deep learning 
model (CNN, ResNet, Transformer)
* Bioinformatics analysis: Sequence alignment, phylogenetic tree construction, differential gene expression analysis, 
GO/KEGG functional enrichment analysis

Publications
======
  <ul>{% for post in site.publications reversed %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>
  
Talks
======
  <ul>{% for post in site.talks reversed %}
    {% include archive-single-talk-cv.html  %}
  {% endfor %}</ul>
  
Teaching
======
  <ul>{% for post in site.teaching reversed %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>
  
Service and leadership
======
* Guided by an interdisciplinary thesis committee spanning computer vision, animal behavior, and statistics, this experience enhanced my cross-disciplinary communication skills and integrated diverse perspectives into my research.

* During my internship, I collaborated with software and hardware engineers on an artificial intelligence project. Effective teamwork and cross-disciplinary communication were essential for integrating algorithms into practical systems.

* I possess experience working within multicultural and multidisciplinary teams, capable of synthesizing diverse expertise to achieve shared R&D objectives.
