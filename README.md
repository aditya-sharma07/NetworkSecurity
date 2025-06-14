# 🛡️ NetworkSecurity: Phishing Detection using Machine Learning

This project is a full-stack machine learning system designed to detect phishing websites based on structured network traffic or related feature data. It integrates a FastAPI backend, a machine learning training pipeline, and MongoDB for storage and inference, offering both model training and real-time predictions through a web interface.

---

## 📌 Features

- 🔍 **ML-Powered Phishing Detection**: Trained model to detect phishing based on CSV data input.
- 🚀 **Training Pipeline**: Supports end-to-end pipeline including ingestion, validation, transformation, and model training.
- 🌐 **FastAPI Interface**: REST API with interactive Swagger docs for training and predictions.
- 🧾 **HTML Output**: Upload CSV → Get prediction table rendered as a webpage.
- ☁️ **MongoDB Integration**: Stores ingested and predicted data using secure connections.
- 🐳 **Docker-Ready**: Easily containerized via Docker.

---

## 🧠 Tech Stack

| Layer        | Technology      |
|--------------|-----------------|
| **Language** | Python 3.x      |
| **Framework**| FastAPI         |
| **ML**       | Scikit-learn    |
| **Storage**  | MongoDB Atlas   |
| **Pipeline** | Custom training pipeline with modular design |
| **DevOps**   | Docker, GitHub Actions |
| **Extras**   | Pandas, NumPy, Certifi, dotenv |

---


## 🚀 How to Run Locally

### ✅ Prerequisites

- Python 3.8+
- MongoDB Atlas URI
- `virtualenv` or `venv`

### 🧪 Setup Environment

```bash
git clone https://github.com/aditya-sharma07/NetworkSecurity.git
cd NetworkSecurity-main
python -m venv venv
source venv/bin/activate  # or .\venv\Scripts\activate on Windows
pip install -r requirements.txt


