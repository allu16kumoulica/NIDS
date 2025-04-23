# NIDS

## About:
This project is a Real-Time Network Intrusion Detection System (NIDS) that uses machine learning models to detect and classify malicious network traffic. It captures network packets using Scapy, processes them into flows, and classifies them using a Random Forest classifier and an Autoencoder for anomaly detection. The system features a real-time Flask-based dashboard, which displays flow details, classification results, and risk levels. LIME is used to explain model predictions, and Plotly visualizes anomalies. The system helps detect threats like DDoS attacks and botnets, providing security analysts with real-time alerts and insights into network activity.

## Requirements:
1. Windows OS
2. Python 3.9
3. Npcap:

## Project Setup:
<code> python -m venv venv</code><br>
<code> venv\Scripts\activate.bat</code><br>
<code> pip install -r requirements.txt</code><br>
<code> python application.py</code><br>
<code> Now open web address http://localhost:5000</code>
