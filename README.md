

# Jet Engine Failure Prediction using LSTM & Anomaly Detection

A predictive maintenance system using deep learning and anomaly detection to forecast jet engine failures in advance. Enhances safety, reduces downtime, and supports proactive maintenance.

---

## 🎯 Objective

Predict the **Remaining Useful Life (RUL)** of aircraft engines using **LSTM networks** trained on sensor telemetry data (temperature, pressure, vibration), combined with **unsupervised anomaly detection**.

---
## 🌐 APIs Used (via [Aviation Edge](https://aviation-edge.com/))

| API                          | Purpose                                                                  |
| ---------------------------- | ------------------------------------------------------------------------ |
| **Airline Routes API**       | Built flight network graph for route simulation.                         |
| **Real-Time Schedules API**  | Dynamic edge weighting using live flight data.                           |
| **Historical Schedules API** | Validated optimizations, showing \~**7% average travel time reduction**. |


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

## 📦 System Flow

```plaintext
Sensor Data → Preprocessing → LSTM Model + Anomaly Detection
       ↓
     Prediction + Alerts → MLflow Tracking + Dockerized Deployment
```

---


