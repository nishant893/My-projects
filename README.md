# My-projects
Survival analysis.py

Survival analysis corresponds to a set of statistical approaches used to investigate the time it takes for an event of interest to occur.
In cancer studies, typical research questions are like:
What is the impact of certain clinical characteristics on patient’s survival
What is the probability that an individual survives 3 years?
Are there differences in survival between groups of patients?
Objectives
The aim is to describe the basic concepts of survival analysis. In cancer studies, most of survival analyses use the following methods:
Kaplan-Meier plots to visualize survival curves
Cox proportional hazards regression to describe the effect of variables on survival
Basic concepts
Here, we start by defining fundamental terms of survival analysis including:
Survival time and event(death)
Censoring
Survival function and hazard function
Survival and hazard functions
The survival probability, also known as the survivor function S(t), is the probability that an individual survives from the time of origin (e.g. diagnosis of cancer) to a specified future time t.
The hazard, denoted by h(t), is the probability that an individual who is under observation at a time t has an event at that time

Kaplan-Meier survival estimate 
The estimated probability (S(t)) is a step function that changes value only at the time of each event. It’s also possible to compute confidence intervals for the survival probability.
The KM survival curve, a plot of the KM survival probability against time, provides a useful summary of the data that can be used to estimate measures such as median survival time.

