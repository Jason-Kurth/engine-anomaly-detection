# Ship Engine Anomaly Detection

## Problem
Modern ship engines generate large volumes of sensor data, but identifying abnormal operating behaviour that may signal mechanical issues is difficult using simple monitoring rules.

This project applies unsupervised anomaly detection techniques to identify unusual engine behaviour patterns in sensor telemetry data.

## Method
The dataset contains engine telemetry measurements such as RPM, pressures, and temperatures. After exploratory analysis, three anomaly detection approaches were compared:

- Interquartile Range (IQR) statistical outlier detection  
- One-Class Support Vector Machine (OCSVM)  
- Isolation Forest  

Principal Component Analysis (PCA) was used to visualise the detected anomalies.

## Outcome
All methods successfully detected abnormal engine behaviour patterns, with Isolation Forest providing the most practical approach for multivariate anomaly detection.

## Tools
Python • Pandas • Scikit-learn • Matplotlib • Seaborn • PCA

## Outputs
- Anomaly detection models identifying abnormal engine observations  
- PCA visualisations comparing anomaly detection methods  
- Notebook implementation and written project report

## Files
- `engine_anomaly_detection_analysis.ipynb` — full implementation  
- `engine_anomaly_detection_project_summary.pdf` — detailed report
