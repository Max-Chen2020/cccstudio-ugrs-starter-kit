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

### Project Title

Exploration of relationship between chord progressions and people's emotions

### Learning Objectives

1. understand some aspects of the relationship between specific musical chord
   progressions and people's emotions

2. train a ML model to generate chord progressions with specific emotional
   characteristics

### Project Description

The aim of this research project is to explore the connection between common chord progressions and people’s emotions, and to use machine learning techniques to create chord progressions which can bring people similar feelings.

The dataset of the project will be gathered from pop music. Common chord progressions from pop music will be chosen and classified into several emotion labels based on the feelings they bring to people. The identified chord progressions will then be transformed into MIDI files to be played and processed. 

For a systematic mapping between chord progressions and people's emotions, arousal/valence graph will be used. An online performance will be carried out to collect feedback from audiences. Each audience will provide an arousal/valence-graph coordinate to indicate their strong/weak and positive/negative emotion upon listening to the audios.

Once the emotion feedbacks are gathered, another classification will be carried out. Ten different types of audio files will be labelled with different emotion labels based on the majority votes from audiences. In the next step, an existing LSTM network model will be used to train the classified audio datasets and output new sequences of music. 

Evaluation of the model will be carried out generatively. Providing an arousal/valence graph coordinate, the output audio will be played to audiences to gather emotion feedbacks. Comparison between the feedback and the input coordinate emotion will be carried out to see if the feelings are similar.

### Assessment

_See form_

### Meeting Dates

Weekly (group meeting) and fortnightly (individual meeting).
