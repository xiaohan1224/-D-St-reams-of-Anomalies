## D(St)reams of Anomalies

## Anomaly detection

Resource: https://github.com/numenta/NAB/tree/master/data

The dataset chosen is machine temperature system failure. The anomalies are detected using:
    * a) IQR
    * b) Isolation Forest
    * c) KNN

## Purpose:
To detect the anomalies.

## Main steps:
1. Data Preparation, reshape the values into -1 to 1.
2. Visualize the machine temperature based on time
3. IQR, Isolation Forest and KNN anomaly detection methods are applied.

## Result:
The anomalies are detected using the methods above.

## Project Structure

```bash

.
├── notebooks
│     └── Anomaly_detection.ipyb
├── README.md
└── data
      └── machine_temperature_system_failure.csv
```
