# MIT-AJL-Team1
Equitable AI for Dermatology Team 1

Team Members:
[Karen Bei
]([url](https://github.com/kbei5234)) [Isabelle Wang
]([url](https://github.com/isabellelwang))
[Michelangelo Zampieri](https://github.com/mzampieri19)

Competition Overview: 
This Kaggle Competition aims to put the machine learning skills learned over the past year into a more practical setting. We see the importance of preparing a quality data set, training it, and fine tuning our model to meet real world needs. 

Project Overview: 
The project aims to increase awareness for the harmful social implications of AI and reduce significant discriminatory threats. 

Real World Impact: 
The model should classify skin conditions across diverse skin tones to increase fairness in dermatology and ensure that historically underrepresented groups deserve fair treatment. 

Competition Objectives: 
- Create a model that is able to classify 21 various skin conditions across a range of skin tones
- Document the process to tie technologies and model back to the real world impact

Overall Team Goals:
- Create working model first then fine tune for optimization.
- Achieve top 10 rank
- Everyone works on things they are familiar and unfamiliar with 

Data Processing:
The main data processing we did for this process was data augmentation and resizing. For data augmentation we did most of the basic operations, zoom in/out, brightness changess, rotations, and shifting. We also resized all images to (244, 244) for more consistancy. 

Files in this Github:
- pre-processing.ipynb. This notebook checks the original data, and does some basic exploration. Then it augments the images in the trianing dataset to provide mor training images.

- training.ipynb. In this notebook a CNN model is prepared and trained.

- my_model.h5. Saves the model and its paramters to make it easier to load in the future (no need to train it everytime).

- predictions.csv. A Csv file of the model's predictions (what we would submit). 

