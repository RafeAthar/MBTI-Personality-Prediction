# MBTI-Personality-Prediction

<br/>
<br/>
<p align="center">
<img src="https://user-images.githubusercontent.com/45414297/220366080-c0e29010-3abf-4787-993e-6ca4d8a7c6c3.png" height=500>
</P>
<p align="center"> <a href="https://en.wikipedia.org/wiki/Myers%E2%80%93Briggs_Type_Indicator#/media/File:MyersBriggsTypes.png">Image Source</a></p>
<br/>

This project predicts the MBTI personality type of people based on their posts on PersonalityCafe forum. The dataset has been taken from <a href="https://www.kaggle.com/datasnaek/mbti-type"> Kaggle </a>. 

MBTI (Myers–Briggs Type Indicator) is one of the frameworks for grouping people in various personality types. Its theory is based on the work of famous psychiatrist Carl Jung. It categorises each person in one of the 16 types which are based on the combinations of 4 pairs of preferences as given below:

Introversion (I) - Extraversion (E)

Intuition (N) - Sensing (S)

Thinking (T) - Feeling (F)  

Judging (J) - Perceiving (P)

All the 16 types can be seen in the image above.

<br/>

Following files are present in this repository:

*mbti_1.csv* contains posts of people and their personality.
*MBTI - Preparing Data.ipynb* is python code for cleaning posts and calculating new columns.
*mbti_cleaned_dataset.csv* contains original and cleaned posts alongwith new engineered columns.
*Predicting MBTI Personality.ipynb* finally consists of code for predicting personality type.
