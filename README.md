# Identify Customer Segments

## Overview
Unsupervised learning analysis using real-world demographic data provided by 
Bertelsmann Arvato Analytics. The goal is to identify which segments of the 
German population are most likely to be customers of a mail-order sales company, 
enabling more targeted and effective marketing campaigns.

## What It Does
- Cleans and preprocesses 891,000+ records of German demographic data
- Applies PCA to reduce dimensionality across 85 features
- Uses KMeans clustering to segment the general population into groups
- Compares cluster distributions between the general population and existing 
  customers to identify over and underrepresented segments

## Tech Stack
- Python, Pandas, NumPy
- Scikit-learn (PCA, KMeans, preprocessing)
- Matplotlib, Seaborn

## Dataset
Data provided by Bertelsmann Arvato Analytics — not included in this repo 
due to licensing restrictions.

## Project Context
Completed as part of the Udacity Machine Learning Nanodegree (Part of Accenture).
