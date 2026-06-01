# A-Neural-Index-of-Acting-Against-Environmental-Preferences

In this repository we have stored all the material needed to reproduce the results reported in the paper 'Beyond behavior: a neural index of environmental preference alignment' (TITLE STILL TO CONFIRM).


The "data" folder contains all the data collected in our study. Within this folder you can find:
- **behavioral**: contains the single-trial and summarized behavioral data of all participants who took part in our study. The single-trial dataset also contains the FMT data used in our single-trial mixed-effects model. Participants that were not eligible for the ERSP analysis inevitably have some variables missing.
- **EEG_epochs**: contains all the EEG epochs of participants eligible for the ERSP analysis. A file for each decision type and participant is present. These epochs time range spans from -200 to 1098 ms after stimulus onset, where the stimulus is the appearance of the information related to the monetary reward associated to the single trial. The order of the epochs in each file relates to the order of presentation of trials. The baseline of these epochs was not removed as this is necessary for proper time-frequency data extraction.
- **LORETA**: contains the LORETA files of participants eligible for the ERSP analysis, organized into separate folders according to decision type. The time range of the data spans again from -200 to 1098 ms after stimulus onset.

All analyses were done with the softwares "Brain Vision Analyzer", "Matlab", "R", "RStudio" and "LORETA".

The "Code" folder contains the scripts we used to extract and analyze time-frequency data, analyze behavioral data and visualize the results.
