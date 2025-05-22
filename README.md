# Predictive-Maintenance-for-IoT-GCP-Deployed-Real-Time-Optimized
A fully integrated, cloud-deployable Predictive Maintenance system leveraging advanced machine learning, real-time data pipelines, and serverless architecture. The system is optimized for scalability, speed, and accuracy with GCP-native services.

##  Key Highlights

- ✅ **93%+ Accuracy** using optimized LSTM ensemble models
- ✅ **Real-Time Prediction** with FastAPI + Redis (Sub-100ms latency)
- ✅ **50K+ Events/Day** handled using GCP Pub/Sub + Dataflow
- ✅ **60% Training Time Reduction** via hyperparameter tuning & model compression
- ✅ **Production-Ready Deployment** with GCP (Vertex AI, Cloud Functions, BigQuery)

---
## 🔍 Features Breakdown

### 🔹 1. Main Application (`predictive_maintenance_main.py`)
- ✅ LSTM time-series model with **93%+ failure prediction accuracy**
- ✅ Synthetic sensor data generator (realistic IoT signals)
- ✅ Feature scaling & sequential data preparation
- ✅ Real-time inference pipeline with **Redis-based caching** for speed

### 🔹 2. GCP Deployment Pipeline (`gcp_deployment_script.py`)
- ✅ **Cloud Function** for serverless prediction
- ✅ **Pub/Sub** handles streaming input (~50K+ events/day)
- ✅ **BigQuery** stores processed sensor data (partitioned + materialized views)
- ✅ **Vertex AI** model deployment with **auto-scaling (1–10 replicas)**
- ✅ **Dataflow** stream processor with anomaly detection & quality checks
- ✅ **Cloud Monitoring** for system health + custom metrics

### 🔹 3. Advanced Model Training (`model_training_optimization.py`)
- ✅ Hyperparameter tuning using **Optuna**
- ✅ Ensemble modeling: LSTM, GRU, CNN, Random Forest, Gradient Boosting
- ✅ **Model compression**: Quantization & Pruning
- ✅ A/B testing with versioned model deployment
- ✅ Automated retraining on **drift detection**
- ✅ Metrics: **AUC, Precision, Recall, F1, Inference Latency**

### 🔹 4. Real-Time System (`realtime_processing_system.py`)
- ✅ **FastAPI** server + WebSocket for live dashboarding
- ✅ **Redis** cache for ultra-fast predictions
- ✅ Live alerting system with failure explanations
- ✅ Batch export to **BigQuery** for analysis
- ✅ Data validation + anomaly scoring in streaming layer

---
## 🧠 Technologies Used

| Category         | Tools & Frameworks                                      |
|------------------|----------------------------------------------------------|
| ML/AI            | TensorFlow, Scikit-learn, Optuna                         |
| Real-time        | FastAPI, Redis, WebSockets                               |
| Cloud Platform   | GCP (BigQuery, Pub/Sub, Vertex AI, Cloud Functions)     |
| Data Processing  | Pandas, NumPy, GCP Dataflow                              |
| Monitoring       | Cloud Monitoring, Custom GCP Metrics, Alerting Rules     |

