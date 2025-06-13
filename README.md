

# LSTM-Powered Predictive Maintenance for Jet Engines

A predictive maintenance system using deep learning and anomaly detection to forecast jet engine failures in advance. Enhances safety, reduces downtime, and supports proactive maintenance.

Note: This project was completed earlier as part of academic research and has now been refined and deployed to GitHub for public reference and demonstration.
---

## 🎯 Objective

Predict the **Remaining Useful Life (RUL)** of aircraft engines using **LSTM networks** trained on sensor telemetry data (temperature, pressure, vibration), combined with **unsupervised anomaly detection**.


---
## 🔑 Key Features

| Feature                    | Summary                                                                                         |
| -------------------------- | ----------------------------------------------------------------------------------------------- |
| **LSTM Forecasting**       | Achieved **92% precision** in failure prediction, over **24+ hours in advance**.                |
| **Anomaly Detection**      | Used **Isolation Forest** and **Autoencoders** to identify sensor anomalies and trigger alerts. |
| **Edge-Ready ML Pipeline** | Deployed via **Docker** and tracked with **MLflow** for scalable integration.                   |
| **Feature Engineering**    | Applied signal smoothing, normalization, and transformations for model efficiency.              |


---

## 🛠 Tech Stack

| Category             | Tools Used                      |
| -------------------- | ------------------------------- |
| **Languages**        | Python, NumPy, Pandas           |
| **ML/DL Frameworks** | TensorFlow, Keras, Scikit-learn |
| **Deployment**       | Docker, MLflow                  |
| **Visualization**    | Matplotlib, Seaborn             |

---

## 📈 Outcomes

* Predicted component failures with **92% precision** using LSTM models.
* Triggered real-time alerts via anomaly detection.
* Achieved **\~7% improvement** in travel time using historical validation.
* Packaged as a **deployable pipeline** ready for edge/cloud inference.

---


