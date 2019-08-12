# Shuttle
This is  an explanation on the approach to shuttle data(NASA)

## Problem Statement:
Detect if there is an anomaly in the radiator of a NASA Space Shuttle at a given point of time by taking the conditions of radiator into consideration.
## About Anomaly Detection:
Anomaly detection is a technique used to identify unusual patterns that do not conform to expected behaviour. It has many applications in business, from intrusion detection (identifying strange patterns in network traffic that could signal a hack) to system health monitoring (spotting a malignant tumour in an MRI scan), and from fraud detection in credit card transactions to fault detection in operating environments.
## Data Description:
The dataset shuttle has 58,000 data points; 43,500 for training and 14,500 for testing. There are 9 attributes and 1 target variable. The Id variables is the different instances of Time.
The target variable contains 7 classes: 
    1.	Rad Flow 
    2.	Fpv Close 
    3.	Fpv Open 
    4.	High 
    5.	Bypass 
    6.	Bpv Close 
    7.	Bpv Open
    
These classes indicate the various actions that can be taken regarding the radiator. Adjusting the Radiation Flow is a normal action and hence constitutes to 78.4% of the data, the rest are actions that are taken under abnormal conditions.
Acronyms – Rad Flow (Radiator flow), FPV (flow proportioning valve), BPV (bipropellant valve)

The data was released by NASA. The 9 attributes concern the condition of radiators in a NASA space shuttle. This is a Realtime data collected during an actual space shuttle flight. Data was designed to study the supervised anomaly detection. 
The Training set contains 78.4% data of Class 1 (Rad Flow). The Class 1 (Rad Flow) can be taken as the Normal Class. Besides the Normal Rad Flow Class, about 21.6% of the original data describe abnormal situations. Class 2, 3, 4, 5, 6, 7 can all be classified as an Anomaly.

Here, we are more concerned about increasing the Recall – and the rate of increase in TPR/Recall should be more than the rate of increase in the FPR.
