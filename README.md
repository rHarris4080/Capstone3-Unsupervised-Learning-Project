# Capstone3-Unsupervised-Learning-Project
Unsupervised learning project investigating relationships and patterns in US gun violence.

Capstone 3 - Unsupervised Learning: US Gun Violence Investigation
Robert Harris - 5/18/21
The US has a Worldwide reputation as a country of uncontrolled gun violence. The US is a unique country in that its citizens have the right to own and bear arms as written in the 2nd Amendment. I found a few datasets of interest covering gun violence in one form or another. While I liked one focused on police shootings I decided to pursue a more generalized one on raw gun violence from 2013-2018 on Kaggle.com.

Task:
Write an unsupervised learning model to help identify some patterns associated with gun violence in the United States. The dataset is comprised of 239,677 reported gun related incidents from 2013 to 2018 and can be found at https://www.kaggle.com/jameslko/gun-violence-data. 

Approach:
The dataset has a vast amount amount of information where extensive preliminary cleaning and exploratory data analysis will dominate the early process. A KModes clustering approach is implemented because of the categorical nature of the feature set.

Stakeholders:
Anyone interested in gaining any insight into gun violence in the US. While many relationships would make common sense on the surface (ie drugs, gangs, robbery, etc...), any further insights gained could always be beneficial going forward.

Limitations:
Dataset: Very little is known about the suspect as far as mental health and motive is concerned. Some key words like robbery, gang vs gang, and drugs give us some indicating factors but these descriptors were only occasionally present. Also, my knowledge of Natural Language Processing(NLP) is basically non-existent at this point. My implementation of parsing key word descriptors was therefore archaic at best.
Work-Arounds: My self taught working knowledge of lambda functions is a work in progress. While I have improved in their implementation, I still find myself reverting to more primititive work-arounds when pressed for time.

Further Investigation:
I would find it interesting to investigate the makeup of the suspects including but not limited to mental health, criminal history, educational level, employment history, and other pertinent personal information. This could also be segued into a supervised learning model with a predictive component.
