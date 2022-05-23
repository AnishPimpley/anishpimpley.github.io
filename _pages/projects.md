---
permalink: /projects
title: "Projects title"
excerpt: "Prjects except"
author_profile: true
redirect_from: 
  - /projects/
  - /projects.html
youtubeId1: oXWCuavGVdg?start=820&end=1006
youtubeId2: QE9vT0zaZdU
---

## Industry (public)

### GPT3 blog generation tool for Satya's demo at Microsoft Ignite 
[link](https://blogs.microsoft.com/ai/new-azure-openai-service/?fbclid=IwAR2PN8geJoB1UCeh3GtGOpyWCjTwdWhrleAG-qkCdt-C4Z1jJgpYCbcEiVQ)                        
*keywords : Large Language models, GPT3, NLP, Deep Learning*          
Built POC for real-time transcription, correction, summarization and creative blog writing for WNBA games in low domain specific data settings.

### Interpret Text - Open-source tool for State-of-the-Art text-based Model Explanations
[link](https://github.com/interpretml/interpret-text-contrib)          
*keywords : Explainability, NLP, Deep Learning*                
Implemented & architected one of the first general purpose toolkits for architecture agnostic interpretation of contemporary & classical NLP models. 

### Adding support for XLNET in MSFT's core NLP repository
[link](https://github.com/microsoft/nlp-recipes/tree/master/utils_nlp/models/xlnet)
*keywords : Deep Learning, NLP, Tranformers*

### Implementing Deeplab v3+ in Production for Matlab.
[link](https://www.mathworks.com/help/vision/examples/semantic-segmentation-using-deep-learning.html) ; [Feature page](https://www.mathworks.com/help/vision/ref/deeplabv3pluslayers.html#d117e118028)
*keywords : Computer Vision, Deep Learning*

## Academia

### Stagewise non-uniform regularization for Cascade classifiers
We propose a new approach to building cascaded classifiers in computation sensitive, low power environments. We extend the firm cascade architecture by introducing non-uniform stage-wise regression terms into the loss function. We introduce a modification over the L1 regularizer, tuned to encourage sparse connections. We evaluate the effects of such a regularizer on use cases with imbalanced classes such as human activity recognition and smoking detection.
*keywords : Computer Vision, Deep Learning*

### Hand-drawn images to Simulink programs
We convert rough hand drawn images of full simulink diagrams and convert them to full working Simulink models in machine. I worked on the exraction, detection and classification part of the pipeline.      
We made a custom dataset, finetuned an imagenet pretrained GoogLeNet based model and used classical vision, topological, density and connectivity properties to extract the graphical structure and flow from the image.

![Video Demonstration](https://raw.githubusercontent.com/AnishPimpley/anishpimpley.github.io/master/media/doodle%20to%20simulink.gif)

### Convert Audio files to Video of person speaking
We use an LSTM to take an audio file as input and generate a video of a person speaking in sync with the audio file.
The goal is to preserve facial landmarks 
The base face model is input as the initial state of the LSTM and the audio signal for a particular time interval is fed at each timestep.

![Video Demonstration](https://raw.githubusercontent.com/AnishPimpley/anishpimpley.github.io/master/media/audio2Face.gif)

