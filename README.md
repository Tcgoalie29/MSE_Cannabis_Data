# MSE_Cannabis_Data

README for the Dataset: Multiscale Entropy in the Prefrontal Cortex

Dataset Title

Multiscale Entropy in the Prefrontal Cortex: Insights from Cannabis Consumption Patterns and Cortical Comparisons

Authors

William T. Creel
Colleen A. Brenner
Richard E. Hartman
Contact Information

Correspondence: William T. Creel, Email: wcreel@students.llu.edu
Abstract

This dataset supports the study investigating the impact of cannabis consumption patterns on complexity levels in the prefrontal cortex (PFC) using Multiscale Entropy (MSE) analysis of resting-state EEG data. The study involves 57 participants categorized into non-users, low-frequency users (use ≤ 1x/week), and frequent users (use ≥ 2x/week). The findings demonstrated significantly lower MSE levels in the PFC, particularly at coarse scales, in frequent users compared to non-users. The PFC also exhibited reduced MSE compared to other cortical regions, irrespective of cannabis use.

Keywords

Entropy
Electroencephalography (EEG)
Prefrontal Cortex
Cannabis
Neural Dynamics
Files Included

MSE_All_Groups_Averaged_Lobes.csv: This file contains the averaged MSE values across different cortical lobes for all participants.
MSE_All_Groups_Wide_PFC_Average.csv: This file contains the detailed MSE values specifically in the prefrontal cortex, for all participants.

Data Description

MSE_All_Groups_Averaged_Lobes.csv:

Columns: Participant ID, Group (Non-users, Low-frequency users, Frequent users), Frontal Lobe MSE, Parietal Lobe MSE, Occipital Lobe MSE, Temporal Lobe MSE.
Rows: Each row represents an individual participant's MSE data averaged across selected channels for the specified cortical lobe.
MSE_All_Groups_Wide_PFC_Average.csv:

Columns: Participant ID, Group, Scale 1 MSE, Scale 2 MSE, ..., Scale 20 MSE (Each column represents MSE values at different scales for the prefrontal cortex).
Rows: Each row represents an individual participant's MSE data in the prefrontal cortex at various temporal scales.

Methodology

Data Acquisition: Resting-state EEG data were collected from 57 participants aged 18-48, categorized based on cannabis consumption patterns.

EEG Recording: Data were recorded using 32 Ag/AgCL electrodes and a Neuroscan SYNAMPS system, with electrodes placed according to the international 10-20 system and a sampling frequency of 1000 Hz.

Preprocessing: Data were band-pass filtered between 0.5 and 60 Hz and Z-scored using the MNE Python library.

MSE Analysis: MSE was computed using the EntropyHub toolkit. Time series were coarse-grained, and Sample Entropy (SampEn) was calculated across multiple scales.

Statistical Analysis

Tools: BlueSky Statistics (V10.2.0) and Statistica (TIBCO Statistica, 2017) was used for statistical analysis.

Tests: Repeated-measures ANOVA (RM-ANOVA) and t-tests were employed to analyze MSE levels across different groups and regions.

Usage Notes

The dataset is provided for further analysis and replication of results presented in the associated manuscript.
Researchers are encouraged to cite the original study when using this dataset.

Repository Information

The datasets generated and/or analyzed during the current study are available in the GitHub repository at [https://github.com/yourusername/survey-dataset](https://github.com/Tcgoalie29/MSE_Cannabis_Data/tree/main).

References

For detailed methodology, analysis, and findings, please refer to the manuscript titled "Reduced Multiscale Entropy in the Prefrontal Cortex: Insights from Cannabis Consumption Patterns and Cortical Comparisons" by William T. Creel, Colleen A. Brenner, and Richard E. Hartman.
