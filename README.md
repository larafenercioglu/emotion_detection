# emotion_detection
CS464 Introduction to Machine Learning Term Project @ Bilkent University

The main purpose of this project is to detect which emotion is present in a given speech.
We have converted the speeches to MFCC to take advantage of its ability to demonstrate 
the short-term power spectrum of a sound and take the coefficients as features. Then we 
use SVM, CNN, and RNN algorithms to classify different emotions. 
Classes we want to classify are {0: sad, 1: angry, 2: happy, 3: disgust, 4: neutral, 5: fear}.

Datasets can be reached from here: 
- https://tspace.library.utoronto.ca/handle/1807/24487 
- https://zenodo.org/record/1188976#.YcsKh2hBxnI

**See the** [Final Report](https://github.com/larafenercioglu/emotion_detection/blob/main/final_report.pdf)
