# Machine-Learning-Project

MEG Datasets Project
Overview
This repository contains information and resources related to Magnetoencephalography (MEG) datasets collected for analyzing brain dynamics associated with cognitive and neurological functions. MEG is a neuroimaging technique that measures magnetic fields generated by neuronal activity, providing insights into brain function.

Author and Institution
Name: Kritheesh S

Institution: Amrita School of Engineering

Abstract
This project focuses on acquiring high-quality MEG datasets from publicly available sources. The datasets are intended for research on brain activity related to motor and cognitive imagery, visual imagination, and geometric shape processing. The data acquisition methods emphasize ethical standards, reproducibility, and standardized procedures.

Included Datasets
Dataset Title	Description	Link
A magnetoencephalography dataset for motor and cognitive imagery BCI	MEG data recorded with a 306-channel Elekta Neuromag system at Ulster University.	DOI:10.6084/m9.figshare.c.5101544.v1
A magnetoencephalography dataset for motor and cognitive imagery-based brain-computer interfacing	Similar setup with Elekta Neuromag system and MaxShield magnetic shielding for improved data quality.	DOI:10.6084/m9.figshare.13561976
Visual Imagination with MEG	MEG signals stored in .npz format, including raw signals, sampling frequency, channels, and timestamps.	Kaggle Dataset
A geometric shape regularity effect in the human brain: MEG dataset	Public dataset in BIDS format with raw MEG recordings and metadata for event, channel, and participant info.	OpenNeuro ds006012
A multi-subject, multi-modal human neuroimaging dataset	Combined MEG and EEG recordings with detailed electrode positioning and participant responses.	OpenNeuro ds002718
Data Acquisition Details
MEG data were recorded using a 306-channel Elekta Neuromag system, including magnetometers and planar gradiometers.

Participants were screened for metallic objects before entering magnetically shielded rooms.

Head position and orientation were tracked using fiducial landmarks and head position indicator coils.

Ocular and cardiac activities were monitored using electro-oculogram (EOG) and electrocardiogram (EKG) electrodes.

Data were filtered online (bandwidths typically between 0.01–300 Hz) and sampled at 1 kHz.

Participants were seated comfortably approximately 80 cm from a projector screen during recordings.

Some datasets include additional metadata files in .tsv format for events, channels, and participant demographics, following BIDS standards.

One dataset includes simultaneous EEG recordings with detailed electrode layouts and stimulus response data.

Dataset Formats
Raw MEG data in FIF format.

Compressed NumPy arrays (.npz) for MEG signal time series.

Tab-separated values (.tsv) files for metadata and event annotations.

Metadata includes sensor types, participant demographics, and experimental conditions.

References
Rathee, D., Cecotti, H., & Prasad, G. (2017). Single-trial effective brain connectivity patterns enhance discriminability of mental imagery tasks. Journal of Neural Engineering, 14(5), 056005.

Wang, Y., Sprague, T. C., Serences, J. T. (2020). A geometric shape regularity effect in the human brain: MEG dataset. OpenNeuro.

Additional dataset DOIs and links are provided above.

Usage
These datasets can be used for research in brain-computer interfaces, cognitive neuroscience, and neuroimaging data analysis. The data formats and accompanying metadata facilitate preprocessing, analysis, and reproducibility.

Repository Link
For code and further project details, visit the GitHub repository:
https://github.com/kritheeshsaravanan/Machine-Learning-Project
