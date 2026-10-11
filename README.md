# Student Performance Prediction Model
A machine learning classification project that predicts whether a secondary school student will pass or fail their final course grade, so that teachers can identify at-risk students early.

## Problem Statement 
Secondary schools often identify struggling students only after poor grades have already appeared, leaving little time to intervene. This project builds a classification model that takes student demographic, family, and behavioral features and predicts whether a student will pass (G3 ≥ 10) or fail (G3 < 10). Success is measured primarily by recall on the "fail" class, with precision, F1, and ROC-AUC as secondary metrics.

## Dataset
- **Source:** [UCI Machine Learning Repository, Student Performance](https://archive.ics.uci.edu/dataset/320/student+performance)
- **Reference:** Cortez, P. & Silva, A. (2008). *Using Data Mining to Predict Secondary School Student Performance.*
- **Size:** 649 records (Portuguese).
- **Features:** demographics, family background, study habits, absences, alcohol consumption, school support, and prior grades (G1, G2).
- **Target:** binary pass/fail derived from final grade G3.

## Project Structure 
