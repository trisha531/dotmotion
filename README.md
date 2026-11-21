# dotmotion
Description: 
This is a dot motion task, used to understand perceptual decision-making, where a percentage of dots move in one direction and the remaining move in another (left and right). Participants are made to identify the direction of the dots in each trial. On each trial, participants see a cloud of moving dots and decide whether the overall motion is toward the left or the right. This task can be used to compare perceptual decision-making and reaction times across when researching on groups like clinical populations. This task was created using the PsychoPy Coder.

Trials: 
The number of trials range from 10 to 150, with five coherence levels. The directions in which the dots run are set to 0° for right, and 180° for left. Each trial is initiated with a fixation cross displayed for a random duration between 0.5 and 1.5 seconds. This is usually done to keep the participants from anticipating or predicting the onset of the dots. The dots stay on screen until the participant denotes which direction they run towards by pressing the left or right arrow key, and reaction time to make their decision is measured.

Output: 
At the end of the task, an Excel file (.xlsx) with the participant number is saved. A dataframe holding direction, coherence, accuracy, response, reaction time, and fixation duration for every trial is also buil. Figures like a scatter plot to show coherence against reaction time, a histogram of reaction times and a box plot of reaction time by direction is displayed at the end of the task.
