---
uid: u6548263
name: Haoyang Chen
project_supervisor: Ben Swift
course_supervisor: Jochen Renz
course_title: Advanced Computing Research Project (COMP4550)
course_units: 12 + 12 
semester: 1 and 2
---

NOTE: the actual pdf form which needs to be submitted is
[here](http://courses.cecs.anu.edu.au/courses/CSPROJECTS/Independent_Study_Contract.pdf).
However, collaboratively editing a pdf is a bit gross, so you should write your
project up in this markdown file and then copy-paste it into the pdf form just
before submission.

## Section A (Students and Supervisors)

### Learning Objectives

1. Understand how chord progressions are related to people's emotions

_(add/remove as required)_

### Project Description

The overall direction for this research project is to build a connection between common chord progressions and people’s emotions, and to use machine learning techniques to create chord progressions which can bring people new feelings.

The dataset of the project will be gathered from pop music. Ten common chord progressions from pop music will be chosen and classified into several emotion labels based on the feelings they bring to people. The identified chord progressions will then be transformed into MIDI files for further processing. 

For a systematic mapping between chord progressions and the feelings they bring to people upon playing, arousal/valence graph will be used. An online performance will be carried out to collect feedback from audiences. Each audience will provide an arousal/valence-graph coordinate to indicate their strong/weak and positive/negative emotion.

Once the emotion feedbacks are gathered, another classification will be carried out. Ten different types of audio files will be labelled with different emotion labels. In the next step, an existing LSTM network model will be used to train the audio datasets and output new sequences of music. The new pieces of music can be classified based on previous labels. 

Another performance using new chord progressions will be carried out to collect emotion feedbacks from audiences. The classified coordinates will then be compared with the feedback emotions to test classification accuracy. 


### Assessment

_See form_

### Meeting Dates

Weekly (group meeting) and fortnightly (individual meeting).
