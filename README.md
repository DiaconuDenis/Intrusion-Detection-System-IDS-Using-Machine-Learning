# Intrusion-Detection-System-IDS-Using-Machine-Learning


---

## Project Overview

This project implements an advanced **Intrusion Detection System (IDS)** powered by a **Random Forest** machine learning algorithm. Its primary goal is to **identify and classify cyber threats** within network traffic in **real-time**. The Random Forest model was rigorously trained on the comprehensive **CICIDS 2017 dataset**, enabling it to accurately detect various types of attacks. Live network packet analysis and threat detection are performed efficiently using the **Scapy** library.

This IDS aims to enhance network security by providing a proactive and intelligent approach to identifying sophisticated cyberattacks, offering a robust layer of defense against malicious activities.

---

## Key Features

* **Advanced Threat Detection:** Utilizes a Random Forest classifier to identify a wide range of cyberattacks, including but not limited to DDoS, PortScan, Brute Force, XSS, and SQL Injection.
* **Real-time Network Monitoring:** Leverages Scapy to capture and analyze live network traffic, enabling immediate threat detection.
* **CICIDS 2017 Trained Model:** The machine learning model is trained on one of the most widely recognized and comprehensive datasets for intrusion detection, ensuring high accuracy and reliability.
* **Modular & Scalable Architecture:** Designed with modularity in mind, allowing for easy integration of different machine learning models, preprocessing techniques, or deployment scenarios.
* **Detailed Logging:** Provides clear output and logging for detected anomalies and identified attack types.

---

## Technologies Used

* **Language:** Python
* **Machine Learning & Data Science Libraries:** `scikit-learn`, `pandas`, `numpy`
* **Network Packet Analysis:** `Scapy`
* **Serialization:** `joblib` (for saving/loading the trained model)

---

## Getting Started

Follow these instructions to set up and run the Intrusion Detection System on your local machine.

### 1. Clone the Repository

First, clone the project repository to your local machine:

```bash
git clone [https://github.com/DiaconuDenis/Intrusion-Detection-System.git](https://github.com/DiaconuDenis/Intrusion-Detection-System.git)
cd Intrusion-Detection-System
