# Wearable Activity Recognition R: A set of introductory notebooks for activity recognition of wearables data using R.

This repository contains introductory material for the analysis of accelerometry data collected from werarable devices.
Notebooks were initially developed in python, and are available [here](https://github.com/OxWearables/Oxford_Wearables_Activity_Recognition.git).
However, we look to adapt the spirit of that notebook into R, with a greater focus
on an intro to those with an epidiemiology background to consider difficulties in processing
complicaed exposures.
This repository is with thanks to Prof. Aiden Doherty, Dr. Shing Chan, Dr. Ben Feakins,
however is currently maintained by Aidan Acquah.

## Understanding the Dataset
The Capture24 dataset is an annotated accelerometry dataset collected from 151 participants by 
the OxWearables group led by Prof. Aiden Doherty. During the study, participants were
instructed to wear a wrist worn accelerometer for 24 hours, as well as an outward facing camera that would take a picture every ~15 seconds. A sleep diary was also used to identify sleep.
As a result of captured images, it is possible to annotate the activity of participants while wearing the device.
This dataset is incredibly useful as it allows for:
1. The evaluation of the performance of human activity recognition (HAR) models.
1. The use of trained models to identify activities in unlabelled datasets.
1. Training of self supervised models.

It should however be noted that there are limitations to this dataset.
1. Snapshots are only taken every roughly 15 seconds, potentially missing some activities
1. Snapshots may often not fully charaterise behaviour 
1. The definition of activity levels can at times be unclear, made further confusing by the mapping between the provided annotations, and desired activity labels. 

## Getting set up
Getting set up is a simple process, but may take some time to complete all steps as datasets are quite large. 

1. Clone/download this repository. This best done using git, and typing in the command:
```{bash}
git clone https://github.com/OxWearables/Wearables_Activity_Recognition_R.git
```
If however, you do not have experience with git, or do not have git installed, you can instead download this repository from [https://github.com/OxWearables/Wearables_Activity_Recognition_R](https://github.com/OxWearables/Wearables_Activity_Recognition_R. 
After opening the webpage, click the "Code" button and select "Download ZIP". 
Ensure to extract the downloaded zip file.

2. Open the "Wearables_Activity_Recognition_R" project folder in RStudio. 
If you do not have RStudio install, you can follow the instructions here: [https://rstudio-education.github.io/hopr/starting.html](https://rstudio-education.github.io/hopr/starting.html)
