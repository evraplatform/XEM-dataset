# XEM-dataset
EVR@ XSens Expressive Motion (XEM) dataset

This dataset is a dataset for detecting emotions from body movements while performing a certain action.
This dataset consists of movements linked with 5 actions called 1: dancing, 2: moving, 3: waving hands, 4: stopping, and 5: pointing.
Each gesture is performed with 4 different emotions:
1: Anger.
2: Neutrality.
3: Happiness.
4: Sadness.
Ten participants, Masters and PhD students from University of Evry Val d'Essonne, participated in this dataset.
Each student is asked to repeat each movement 5 times. 
This means that there are 100 = 5(steps of the motion)*4(basic emotion)*5(repetition) videos for each participant.
So in total we have 1000=10*10 videos.

In the attached file you will find a  5*10*20 .mat file.
5 = The number of actions(a).
10 = The number of participants(p).
20 = The number of repetition(e).
	The first 5 examples are related to Anger emotion
	the second 5 examples are related to Neutrality emotion
	the third 5 repetitions are related to Happiness
	and the last 5 examples are related to Sadness.
The information of each video can be read by Data{a,p,e} in Matlab.
In each example, the first column shows the time, columns 2 to 70 for the three-dimensional coordinates of each joint of the body,
 the next 69 columns for the velocity of the joint,
 the third 69 column for the angular velocity of the joint,
 the fourth 66 column for the Euler angles 
 and the last three columns show the center of mass of each movement.
