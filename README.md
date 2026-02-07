# 🚀 MLOps Project 2 – End-to-End ML Pipeline with Monitoring

This project focuses on **hands-on MLOps concepts**, especially **orchestration and monitoring of ML systems in a production-like setup**.

The goal was not model accuracy, but understanding how ML pipelines behave **after deployment**.

---

## 🧠 Tech Stack
- **Dataset**: Titanic
- **Orchestration**: Astro Airflow
- **Containerization**: Docker
- **Storage**: Google Cloud Storage
- **Backend / UI**: Flask
- **Feature Store**: Redis
- **Monitoring**: Prometheus & Grafana

---

## 🔄 Pipeline Overview
1. Data stored in Google Cloud Storage
2. Airflow DAG orchestrates the ML pipeline
3. Features are stored and fetched from Redis
4. Model is served via Flask
5. Prometheus scrapes application metrics
6. Grafana visualizes system & prediction metrics

---

## 📊 Monitoring & Observability
- Prometheus scrapes metrics from the Flask `/metrics` endpoint
- Grafana dashboards visualize:
  - Prediction count
  - Application health
  - Runtime metrics



---

## 🚀 Key Learnings
- Building production-like ML pipelines
- Monitoring deployed ML systems
- Understanding observability in MLOps
- Orchestrating workflows using Airflow

---

## 📌 Note
The Titanic dataset was intentionally chosen to keep the focus on **MLOps infrastructure and monitoring**, not model performance.

---

## 👩‍💻 Author
Sanika Shantaram Aher  
Final Year AIML | Aspiring ML / MLOps Engineer
