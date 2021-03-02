# ShopCert_Image_Classifer
Image recognition and binary classifier to predict whether a document is a cert or non cert.


PART 1: INTRODUCTION
Background
An FAA/EASA Cert is essential before we can ship a part to a customer or airline and subsequently install that part on to an aircraft. Part of the QC process is that upon receipt, these documents are supposed to be scanned in to the system and tagged with the appropriate document type. Occasionally, there are shortfalls in the system and these documents are either not scanned, mislabeled, or not labeled at all. Currently this misstep in the process is not identified until we are preparing the part for shipment to the customer. Once this missing document is identified, it then requires the team to scramble to try and find the doc, and in the worst cases, require us to go back to the repair vendor for a copy which may lead to us miss our shipment, resulting in penalties and aircraft groundings.

Purpose of Project
The purpose of this project is to be proactive in the process and identify before an active requirement occurs. The goal is to build an image classifer to identify a CERT from a NON-CERT.
T
This notebook/ppt shows the full end to end project including all the below:
1) Building the Raw Dataset:  Note that since the data is propriety, I can only show a few sample images.
2) Exploratory Data Analysis & Data Augmentation
3) ImageDataGenerators
4) Loading Data
5) Creating more sample data
6) Preparing / Normalizing data
7) Building the Model
8) Defining CNN layers
9) Brief Overview on how CNN works
10) Predicting new data
11) Evaluating and interpreting the model results
12) Current Model Performance
13) Thoughts on improving performance
14) Next steps


![image](https://user-images.githubusercontent.com/9125316/109580166-c3f6b680-7abf-11eb-9005-d57fcb623258.png)
