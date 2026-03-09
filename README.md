# Ship Engine Anomaly Detection

This project explores anomaly detection methods to identify abnormal behaviour in ship engine sensor data. Detecting unusual operating patterns early can support predictive maintenance and reduce operational risk.

## Approach

The dataset contains engine telemetry measurements such as RPM, pressures, and temperatures. After exploratory analysis, three anomaly detection approaches were compared:

- Interquartile Range (IQR) statistical outlier detection  
- One-Class Support Vector Machine (OCSVM)  
- Isolation Forest  

Principal Component Analysis (PCA) was used to visualise the detected anomalies.

## Tools

Python • Pandas • Scikit-learn • Matplotlib • Seaborn • PCA

## Outcome

All methods successfully detected abnormal engine behaviour patterns, with Isolation Forest providing the most practical approach for multivariate anomaly detection.

## Outputs

- Anomaly detection models identifying abnormal engine observations  
- PCA visualisations comparing anomaly detection methods  
- Notebook implementation and written project report

## Files

- `engine_anomaly_detection_analysis.ipynb` — full implementation  
- `engine_anomaly_detection_project_summary.pdf` — detailed report
