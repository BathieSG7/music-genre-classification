# Music Genre Classification
![](https://img.shields.io/badge/python-3.6-brightgreen.svg) ![](https://img.shields.io/badge/tensorflow-1.3.0-orange.svg)
![](https://img.shields.io/badge/keras-2.0-blue.svg)

## Overview
Recognizing music genre is a challenging task in the area of music information retrieval. One approaches is studied here:
1. Feature Engineering Approach using Logistic Regression, SVMs, Random Forest and eXtreme Gradient Boosting.
We Plan to use Spectrogram based end-to-end image classification using a CNN (VGG-16)

This project was carried out as a part of the course CS 698 - Computational Audio offered by [Prof. Richard Mann](https://cs.uwaterloo.ca/~mannr/) at the University of Waterloo. For a detailed description about the project, please refer to [this article](https://arxiv.org/abs/1804.01149) published on [arXiv](https://arxiv.org/).
It's also another version of the originial repository: music-genre-classification

## Datasets
The *Audio Set* data [released by Google](https://research.google.com/audioset/download.html) is used in this study. Specifically, only the wav files that correspond to the following class labels are extracted from YouTube based on the video link, start and end times. 
And Mbalaxx songs is downloaded using the pytube module and youtube-dl .


## Requirements
- pytube==9.4.0
- numpy==1.12.1
- pandas==0.22.0
- youtube-dl==2018.2.4
- scipy==0.19.0
- librosa==0.5.1
- tqdm==4.19.1
- scipy==0.19.0
- Pillow==4.1.1

## Instructions
1. First, the audio wav files need to be downloaded using the tool [youtube-dl](https://rg3.github.io/youtube-dl/). For this run `all audio_retrieval.py`files. Note that the each file is about 1.3 MO, totally upto 5 GB!
2. The next step is to run the models. Please refer to the corresponding Jupyter notebooks. 

## Results
The models are evaluated on the basis on AUC, accuracy and Fscore. 




