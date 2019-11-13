# Project 3 Generative Audio

Yifan Hou, yihou@ucsd.edu

(Your teammate's contact info, if appropriate)

## Abstract

When people see some images, they will imagine sounds in their minds. In this project, I want to generate different background music for different images.When people choose or upload a image, the program will generate corresponding audio for the image. To complete this, first I need one well-established, pre-trained image recognition model to calssify images. Then I use another convolutional neural network reads the audio as spectrogram images, evolving so that the distribution of its output gets as close as possible to that of the first one. Once trained, the two networks allow us to generate the best-matched sound for a scene.


## Model/Data

Briefly describe the files that are included with your repository:
- two trained models(pre-trained image recognition modle and SoundNet model)
- training data (train sounds)

## Code

Your code for generating your project:
- Jupyter notebooks: main.ipynb

## Results

Documentation of your results in an appropriate format, both links to files and a brief description of their contents:
- beach.mp3 and beach2.mp3 for beach image
- train.mps for train image
- town.mp3 and town2.mp3 for town image

## Technical Notes

Python 3
Jupyter notebook
keras
scipy

## Reference

References to any papers, techniques, repositories you used:
- http://soundnet.csail.mit.edu/
- https://github.com/eborboihuc/SoundNet-tensorflow
- http://soundnet.csail.mit.edu/
