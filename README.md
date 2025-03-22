# MIT-AJL-Team1
Equitable AI for Dermatology Team 1

**Team Members:**
[Karen Bei](https://github.com/kbei5234), 
[Isabelle Wang](https://github.com/isabellelwang),
[Michelangelo Zampieri](https://github.com/mzampieri19),
[Humaira Sarwary](https://github.com/humairasarwary),
[Natalie Cheng](https://github.com/nataliemcheng)

__________________________________________________________________________

**Project Highlights**

- uilt a \[insert model type\] using \[techniques used\] to solve \[Kaggle competition task\]
- Achieved an F1 score of \[insert score\] and a ranking of \[insert ranking out of participating teams\] on the final Kaggle Leaderboard
- Used \[explainability tool\] to interpret model decisions
- Implemented \[data preprocessing method\] to optimize results within compute constraints
_________________________________________________________________________

**Setup and Execution**

Files in this Github:
- pre-processing.ipynb. This notebook checks the original data, and does some basic exploration. Then it augments the images in the trianing dataset to provide mor training images.

- training.ipynb. In this notebook a CNN model is prepared and trained.

- my_model.h5. Saves the model and its paramters to make it easier to load in the future (no need to train it everytime).

- predictions.csv. A Csv file of the model's predictions (what we would submit).

To run the pre-processing and training notebooks, download the files and open them in your desired workspace. After that, you should be able to run all the cells like any other jupyter notebook. 
_________________________________________________________________________

**Project Overview** 
The project aims to increase awareness for the harmful social implications of AI and reduce significant discriminatory threats. 

Competition Overview: 
This Kaggle Competition aims to put the machine learning skills learned over the past year into a more practical setting. We see the importance of preparing a quality data set, training it, and fine tuning our model to meet real world needs. 

Real World Impact: 
The model should classify skin conditions across diverse skin tones to increase fairness in dermatology and ensure that historically underrepresented groups deserve fair treatment. 

Competition Objectives: 
- Create a model that is able to classify 21 various skin conditions across a range of skin tones
- Document the process to tie technologies and model back to the real world impact

Overall Team Goals:
- Create working model first then fine tune for optimization.
- Achieve top 10 rank
- Everyone works on things they are familiar and unfamiliar with

__________________________________________________________________________

**Data Exploration**

Data Processing:
The main data processing we did for this process was data augmentation and resizing. For data augmentation we did most of the basic operations, zoom in/out, brightness changess, rotations, and shifting. We also resized all images to (244, 244) for more consistancy. After this step, we created 17160 images from the original 2860 images. Each category has 5x the number of images what it had initially. 


__________________________________________________________________________
**Model Development**

__________________________________________________________________________
**Results & Key Findings**

__________________________________________________________________________

**Impact Narrative**
__________________________________________________________________________

**Next Steps & Future Improvements**
