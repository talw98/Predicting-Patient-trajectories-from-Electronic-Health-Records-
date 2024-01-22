# Predicting Patient trajectories from Electronic Health Records
*This was a lab assignment of my Masters Degree and under the course 'Medical Text Mining'.*

## Problem Overview

Medical professionals often need to assess patients' well-being and predict their response to treatments. Predicting patients' health based on Electronic Health Records (EHRs) is a valuable tool. However, there are challenges, especially in inter-organizational patient modeling. Privacy rules, data availability, and structural variations in EHRs across organizations make seamless integration and analysis challenging.

## Inconsistencies in EHRs Hindering Inter-Organizational Modeling

1. **Data Standardization and Format Variability:**
   - *Example:* Differences in coding systems and data representation hinder integration and analysis due to inconsistencies between organizations.

2. **Incomplete or Missing Data:**
   - *Example:* Gaps in patient records, like missing information on diagnoses or treatments, arise from variations in data entry practices across organizations.

3. **Differences in Data Quality and Accuracy:**
   - *Example:* Varied data validation practices among healthcare providers result in discrepancies in data quality and accuracy.

## Intra-Organizational Challenges in Patient Trajectory Modeling

### Discrete EHRs:

- **Challenge:** Different departments within a hospital use separate electronic systems, leading to difficulties in integrating patient data due to varied data standards and terminologies.

### Text-Based EHRs:

- **Challenge:** Healthcare professionals rely on free-text notes, causing challenges in patient trajectory modeling due to diverse writing styles, lack of standardization, and the need for advanced text mining techniques.

## Dataset Access

For the purpose of this module, we will use the MIMIC-III dataset, available [here](link). Alternatively, a smaller, publicly available demo version can be used (without textual records). 

## Module Focus: Patient Morbidity Prediction

In this module, the focus is on predicting patient morbidity upon hospital entry. While this may seem like a dark task, it represents a real problem that can be addressed through clinical Natural Language Processing (NLP) engineering.

Feel free to explore the provided dataset and contribute to the ongoing effort in developing solutions for patient trajectory prediction.
