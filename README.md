# Cross-Day Hand-Gesture Recognition from Wrist sEMG

APS360 Individual Project — Grace MacLeod

## Overview
1D CNN for classifying 16 hand/finger gestures from 12-channel wrist surface EMG, 
evaluated on cross-day generalization using the GRABMyo dataset.

## Dataset
[GRABMyo v1.0.1 on PhysioNet](https://physionet.org/content/grabmyo/1.0.1/) 
— 43 participants, 3 recording days, 16 gestures, 2048 Hz.

## Pipeline
`progress_report_pipeline.ipynb` — complete pipeline 
(download, preprocessing, SVM baseline, 1D CNN training, evaluation). 
Runs end-to-end on Google Colab Pro with GPU + high-RAM.
