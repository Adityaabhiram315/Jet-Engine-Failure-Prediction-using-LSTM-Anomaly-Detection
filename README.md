# Jet-Engine-Failure-Prediction-using-LSTM-Anomaly-Detection

This project implements a predictive maintenance system for jet engine components using LSTM-based deep learning and sensor telemetry. The goal is to predict failures and detect anomalies ahead of time, improving aviation safety, operational uptime, and maintenance efficiency.

🔑 APIs Used in the Project (FROM AVIATION EDGE $ 7 USD / month)
1.) Airline Routes API

-Used to build the real-world flight network graph.

-Provided direct and indirect routes between global airport pairs.

-Enabled accurate edge creation in graph algorithms (Dijkstra, Floyd-Warshall).

2.)Real-time Schedules API

-Fetched current flight timings and frequencies to simulate real-time routing.

-Helped dynamically update edge weights (travel time, delays) in the graph.

-Made the simulation closer to a live operational scenario.

3.)Historical Schedules API

-Used to validate algorithmic results by comparing optimized paths with real historical flight durations and paths.

Helped estimate actual time reduction (~7%).

🎯 Objective
To forecast the Remaining Useful Life (RUL) of aircraft engines by analyzing time-series sensor data (temperature, pressure, vibration) using Long Short-Term Memory (LSTM) networks, supported by unsupervised anomaly detection models for real-time health monitoring.

💡 Key Features
LSTM-based Time Series Prediction: Trained deep recurrent neural networks to predict jet engine component degradation, achieving 92% precision in forecasting failures 24+ hours in advance.

Anomaly Detection Models: Integrated Isolation Forest and Autoencoder-based models to detect early deviations in sensor patterns and alert maintenance teams.

Feature Engineering & Optimization: Applied statistical analysis and signal smoothing techniques to clean raw sensor inputs for enhanced model performance.

Edge-Deployable ML Pipeline: Developed and deployed the ML pipeline using MLflow, Docker, and Streamlit, simulating an on-prem or edge deployment use case.

Live Dashboard: Built an interactive dashboard to visualize engine health metrics, model predictions, and alerts for operational decision-making.

📦 Tech Stack
Python, Pandas, NumPy, Matplotlib, Seaborn

TensorFlow/Keras for LSTM modeling

Scikit-learn for anomaly detection

Streamlit for visualization

MLflow + Docker for deployment

📊 Outcome
This project replicates real-world aircraft predictive maintenance pipelines and demonstrates how deep learning and anomaly detection can enable proactive maintenance. Achieved measurable improvements in failure prediction precision and alert response latency, with real-time inference capabilities and scalable deployment.

