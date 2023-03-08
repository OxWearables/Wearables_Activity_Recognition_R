# Wearable Activity Recognition R: A set of introductory notebooks for activity recognition of wearables data using R.

This repository contains introductory material for the analysis of accelerometry data collected from wearable devices.
Notebooks were initially developed in python, and are available [here](https://github.com/OxWearables/Oxford_Wearables_Activity_Recognition.git).
However, we look to adapt the spirit of those notebooks into R, as an intro to those with an epidemiology background to consider difficulties in processing complicated exposures.

This repository is with thanks to Dr. Ben Feakins, Dr. Shing Chan and Prof. Aiden Doherty, however is currently maintained by Aidan Acquah.

## Understanding the Dataset

The Capture24 dataset is an annotated accelerometry dataset collected from 151 participants by the OxWearables group.
During the study, participants were instructed to wear a wrist worn accelerometer for 24 hours, as well as an outward facing camera that would take a picture every \~20 seconds.
A sleep diary was also used to identify sleep.
As a result of captured images, it is possible to annotate the activity of participants while wearing the device.

This dataset is incredibly useful, as it allows for: 
1. The evaluation of the performance of human activity recognition (HAR) models.
2. The development of models trained on this data set to identify activities in unlabeled datasets.
3. Training of self supervised models.

It should however be noted that there are limitations to this dataset: 
1. Snapshots are only taken every roughly 20 seconds, potentially missing some activities.
2. Snapshots may often not fully characterise the behaviour of the participants.
3. The definition of activity levels can at times be unclear, made further confusing by the mapping between the provided annotations, and desired activity labels.

## Getting set up

Getting set up is a simple process, but may take some time to complete all steps as datasets are quite large.

1.  Clone/download this repository. This best done using git, and typing in the command:

```{bash}
git clone https://github.com/OxWearables/Wearables_Activity_Recognition_R.git
```

If however, you do not have experience with git, or do not have git installed, you can instead download this repository from <https://github.com/OxWearables/Wearables_Activity_Recognition_R>.
After opening the webpage, click the "Code" button and select "Download ZIP".
Ensure to extract the downloaded zip file.

2. Open the "Wearables_Activity_Recognition_R" project folder in RStudio.
If you do not have RStudio install, you can follow the instructions here: <https://rstudio-education.github.io/hopr/starting.html>

3. Start working from the first R Notebook, located at `scripts/1-Introduction.Rmd`.
