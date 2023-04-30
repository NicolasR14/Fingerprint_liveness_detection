# Fingerprint liveness detection
## Description
Part of a school project where the goal was to detect fake fingerprints (silicone,ecoflex,gelatin,latex,silgum,playdoh)

## Dataset
Dataset used is from 2009 and 2011 LivDet's competition, fully labelled.

## Approaches
Two approaches were tested : 
  - Global approach : the whole image is passed in a CNN network where the output layer classify the sample in two possible predictions : fake or alive fingerprint
  - Local approach : analysis of the pores (on the ridges of the fingerprint). Extraction of texture parameters as features vector. Use of clustering algorithm (KNN) to classify.

## Model performance
As the dataset was fully labeled, the model performance is easy to determine : accuracy, false positive/false negative rates.
