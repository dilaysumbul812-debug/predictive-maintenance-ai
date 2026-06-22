# 🏭 Predictive Maintenance & Industrial AI Platform

This project is a comprehensive artificial intelligence automation system that uses real-time logs and failure data from production floor machinery to predict equipment failures via Machine Learning algorithms, measure operator performance, and automatically generate and email PDF reports. The main goal of the system is to make sense of production data, increase operational efficiency, and generate rapid insights for predictive maintenance processes.

## 🌟 Key Features

* **🤖 AI-Driven Failure Prediction:** Deterministic prediction of next-day failure probabilities and production quantities of machines using XGBoost Regression and Classification models.
* **🧠 Explainable AI (XAI - SHAP):** Explaining model decisions with SHAP integration and providing root cause analysis via LLM-based engineering hypotheses.
* **🕵️‍♂️ Micro Downtime (Chokotei) & Anomaly Detection:** Automatic detection of operators' short-term idle times and biological fatigue hours using the Isolation Forest algorithm.
* **📊 Automated PDF Reporting:** Generating custom, typographically formatted PDF reports for managers and maintenance engineers containing Heatmaps, Pareto Analysis, and Radar Charts using the ReportLab library.
* **🎯 K-Means Clustering:** Categorizing machines and operators into strategic clusters (e.g., "Optimum", "Heavy Vehicles") based on performance metrics to offer actionable maintenance recommendations.
* **📧 Automated Email Distribution:** Automatically dispatching the generated reports to company executives via a local SMTP server.

## 🛠️ Technologies Used

* **Backend & ML:** Python, XGBoost, Scikit-learn (KMeans, IsolationForest), SHAP, Pandas, NumPy
* **Visualization & Reporting:** ReportLab, Matplotlib
* **AI & Communication:** Llama 3.1 (Localhost integration via Ollama), smtplib (On-Premise Exchange)
* **Data Sources:** MS SQL Server (SQLAlchemy, PyODBC), Excel (`.xlsx`)

## ⚙️ Installation and Setup

You can follow the steps below to run the project locally on your machine:

### 1. Clone the Repository
```bash
git clone [https://github.com/dilaysumbul812-debug/predictive-maintenance-ai.git](https://github.com/dilaysumbul812-debug/predictive-maintenance-ai.git)
cd predictive-maintenance-ai
2. Install Dependencies
Ensure Python is installed on your system and install the required dependencies:

Bash
pip install pandas numpy xgboost scikit-learn shap reportlab matplotlib sqlalchemy pyodbc requests
3. Ollama and Llama 3.1 Setup
To ensure data privacy and generate engineering hypotheses for SHAP data, the project uses the Llama 3.1 model running entirely locally.

Download and install Ollama

Open your terminal, download and run the model:

Bash
ollama run llama3.1
4. Run the Application
After entering your database connection details and email settings into the (anonymized) fields in the code, start the main script:

Bash
python main.py
Once the system is running, it will generate your PDF outputs and analysis charts under the Raporlar/ (Reports) directory.

📂 Project Structure
main.py: The heart of the system. Manages data processing, model training, SHAP analysis, and PDF report generation.

uretim_tablosu.xlsx & ariza_tablosu.xlsx: Deterministic datasets analyzed by the system and used to train ML models.

Raporlar/: The directory where historical PDF-based system analyses and generated charts (Heatmap, Pareto, Radar) are stored.

👨‍💻 Developer
Dilay Sümbül - Electrical-Electronics Engineer & AI Developer

My LinkedIn Profile

My GitHub Profile # 🏭 Predictive Maintenance & Industrial AI Platform

This project is a comprehensive artificial intelligence automation system that uses real-time logs and failure data from production floor machinery to predict equipment failures via Machine Learning algorithms, measure operator performance, and automatically generate and email PDF reports. The main goal of the system is to make sense of production data, increase operational efficiency, and generate rapid insights for predictive maintenance processes.

## 🌟 Key Features

* **🤖 AI-Driven Failure Prediction:** Deterministic prediction of next-day failure probabilities and production quantities of machines using XGBoost Regression and Classification models.
* **🧠 Explainable AI (XAI - SHAP):** Explaining model decisions with SHAP integration and providing root cause analysis via LLM-based engineering hypotheses.
* **🕵️‍♂️ Micro Downtime (Chokotei) & Anomaly Detection:** Automatic detection of operators' short-term idle times and biological fatigue hours using the Isolation Forest algorithm.
* **📊 Automated PDF Reporting:** Generating custom, typographically formatted PDF reports for managers and maintenance engineers containing Heatmaps, Pareto Analysis, and Radar Charts using the ReportLab library.
* **🎯 K-Means Clustering:** Categorizing machines and operators into strategic clusters (e.g., "Optimum", "Heavy Vehicles") based on performance metrics to offer actionable maintenance recommendations.
* **📧 Automated Email Distribution:** Automatically dispatching the generated reports to company executives via a local SMTP server.

## 🛠️ Technologies Used

* **Backend & ML:** Python, XGBoost, Scikit-learn (KMeans, IsolationForest), SHAP, Pandas, NumPy
* **Visualization & Reporting:** ReportLab, Matplotlib
* **AI & Communication:** Llama 3.1 (Localhost integration via Ollama), smtplib (On-Premise Exchange)
* **Data Sources:** MS SQL Server (SQLAlchemy, PyODBC), Excel (`.xlsx`)

## ⚙️ Installation and Setup

You can follow the steps below to run the project locally on your machine:

### 1. Clone the Repository
```bash
git clone [https://github.com/dilaysumbul812-debug/predictive-maintenance-ai.git](https://github.com/dilaysumbul812-debug/predictive-maintenance-ai.git)
cd predictive-maintenance-ai
2. Install Dependencies
Ensure Python is installed on your system and install the required dependencies:

Bash
pip install pandas numpy xgboost scikit-learn shap reportlab matplotlib sqlalchemy pyodbc requests
3. Ollama and Llama 3.1 Setup
To ensure data privacy and generate engineering hypotheses for SHAP data, the project uses the Llama 3.1 model running entirely locally.

Download and install Ollama

Open your terminal, download and run the model:

Bash
ollama run llama3.1
4. Run the Application
After entering your database connection details and email settings into the (anonymized) fields in the code, start the main script:

Bash
python main.py
Once the system is running, it will generate your PDF outputs and analysis charts under the Raporlar/ (Reports) directory.

📂 Project Structure
main.py: The heart of the system. Manages data processing, model training, SHAP analysis, and PDF report generation.

uretim_tablosu.xlsx & ariza_tablosu.xlsx: Deterministic datasets analyzed by the system and used to train ML models.

Raporlar/: The directory where historical PDF-based system analyses and generated charts (Heatmap, Pareto, Radar) are stored.

👨‍💻 Developer
Dilay Sümbül - Electrical-Electronics Engineer & AI Developer


My GitHub Profile
