# Stack Overflow Predictive Modeling

By: Vanessa Alvarado

<p align = "center">
  <img src="images/Stack Overflow Landing Photo.png"/><br>
</p>


## Background 
- Summarize Stack Overflow:
	- "Stack Overflow is the largest, most trusted online community for developers to learn, share​ ​their programming ​knowledge, and build their careers."
	- "Stack Overflow is a question and answer site for professional and enthusiast programmers." 
	- "Stack Overflow is an open community for anyone that codes. We help you get answers to your toughest coding questions, share knowledge with your coworkers in private, and find your next dream job."
	- "Stack Exchange (Stack Overflows parent company) is a network of question-and-answer (Q&A) websites on topics in diverse fields, each site covering a specific topic, where questions, answers, and users are subject to a reputation award process. The reputation system allows the sites to be self-moderating.[7] As of August 2019, the three most actively-viewed sites in the network are Stack Overflow, Super User, and Ask Ubuntu.[8] " -- Wikipedia

## Problem Statement
Programmers from all levels scour the web for the best answers for common to more challenging tasks. More times than not, Google directs you to a Stack Overflow [link](https://stackoverflow.com/questions/53645882/pandas-merging-101): 

<p align = "center">
  <img src="images/google stackoverflow search.png"/><br>
</p>

<p align = "center">
  <img src="images/stackoverflow pandas merging.png"/><br>
</p>





## Table of Contents
1. [Data Dictionary](https://github.com/VPNA09/Stackoverflow-NLP/blob/master/readme.md#data-dictionary) 
2. [Data Files](https://github.com/VPNA09/Stackoverflow-NLP/blob/master/readme.md#data-files)
3. [Data Acquisition](https://github.com/VPNA09/Stackoverflow-NLP/blob/master/readme.md#data-acquisition)
	- [Data Cleaning](https://github.com/VPNA09/Stackoverflow-NLP/blob/master/readme.md#data-cleaning) 
4. [Feature Engineering](https://github.com/VPNA09/Stackoverflow-NLP/blob/master/readme.md#feature-engineering)  
5. [Exploratory Data Analysis](https://github.com/VPNA09/Stackoverflow-NLP/blob/master/readme.md#exploratory-data-analysis)
6. [Modeling](https://github.com/VPNA09/Stackoverflow-NLP/blob/master/readme.md#modeling)
7. [Conclusions & Limitations](https://github.com/VPNA09/Stackoverflow-NLP/blob/master/readme.md#conclusions-and-limitations) 
8. [Future Work](https://github.com/VPNA09/Stackoverflow-NLP/blob/master/readme.md#future-work) 

### Data Dictionary
|Feature|Type|Description|
|---|---|---|
|id|int|Unique numeric identifier for Stack Overflow question |
|CreationDate|datetime|Creation date for Stack Overflow question|
|Title|obj|User generated title for Stack Overflow question|
|Body|obj|Original question: including html artifacts, numbers etc.|
|A|int|A|
|B|object|B|
|A|int|A|
|B|object|Will add more|  

### Data Files
Data files are too large upload to GitHub. The following links are zipped data files: 
- 2019 Weekly csv files (zipped)
    - [Weeks 1 - 20](https://drive.google.com/open?id=1uttbh17hfhnfMLqnajbw3yX7LC27yQFY)
    - [Weeks 21-40](https://drive.google.com/open?id=1Isrpl4XX-Sv3CDmI2eNI26fX8Hu98mt4)
    - [Weeks 41-52](https://drive.google.com/open?id=15FEnPmx_LaP9_xpxB3zz6BMqFDgTbVc6)
 - [2019 Combined Weekly csv file (zipped)](https://drive.google.com/open?id=1OPgd2J14mfQkCpvhz9O8qFbql0FUpDaf)
 - [Final Version, used for modeling (zipped)](https://drive.google.com/open?id=1zDhE4GE45HkwbPjMCbw0S36UxoWXHqX5) 

## Executive Summary

### Data Acquisition
- Where did you get your data? / How did you acquire your data?

### Data Cleaning
#### 2019 Weekly Data
- 

#### 2019 Combined Data  
- 

#### Final (For Modeling) 
- 

### Feature Engineering
- How did you transform or engineer your data? Why?

### Exploratory Data Analysis
- 
- 


### Modeling
- What are your metrics?
- How did you optimize hyperparameters?
- How did you select your model?

### Conclusions and Limitations
- What were your findings?
- What risks/limitations/assumptions affect these findings?
- Summarize your statistical analysis, including:
	- implementation
	- evaluation
	- inference


### Future Work
- How can I build off what I have? 
	- Cloud commuting
	- Different NLP techniques 
