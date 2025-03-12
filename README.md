# SmartHealth-Research

## 📌 Overview  
The **SmartHealth-Research** project focuses on using sensory data collected from **mobile devices (smartphones and wearables)** to monitor **depression symptoms** and predict **treatment outcomes**. This research contributes to the field of **smart and connected health**, offering data-driven solutions for mental health monitoring using machine learning and time-series analysis. The project includes evaluation of SVM, XGBoost, LSTM, and GRU-D models using transfer learning, feature selection, and explainability analysis with SHAP techniques, as well as experiments with Langchain GPT-4 on an open-source dataset.  

*Note: Due to NIH grant restrictions, the code and data for this project cannot be shared publicly.*

## 📂 Research Areas  
This project explores two key directions:

### **1. Predicting Symptom Improvement During Depression Treatment Using Sleep Sensory Data**  
🔹 **Key Findings:**  
- Sleep data from **Fitbit devices** is used to predict changes in depression symptoms.  
- A dataset of **28 participants** was analyzed.  
- **ℓ1 trend filtering** was applied to extract high-level sleep features from noisy raw data.  
- Evaluated **SVM, XGBoost, Random Forrest** using **feature selection and explainability analysis**.  
- Features such as **mean and standard deviation of sleep duration** showed correlations with self-reported depression scores.  
- Machine learning models achieved an **F1 score of 0.68**, demonstrating the potential of **sleep sensory data in predicting symptom improvement**.  

📄 **Publication:**  
[Predicting Symptom Improvement During Depression Treatment Using Sleep Sensory Data](https://dl.acm.org/doi/abs/10.1145/3610932)  
📌 *Chinmaey Shende, Soumyashree Sahoo, Stephen Sam, Parit Patel, Reynaldo Morillo, Xinyu Wang, Shweta Ware, Jinbo Bi, Jayesh Kamath, Alexander Russell, Dongjin Song, and Bing Wang.*  
📌 *Proceedings of the ACM on Interactive, Mobile, Wearable and Ubiquitous Technologies (IMWUT), 2023.*  

---

### **2. Using Mobile Daily Mood and Anxiety Self-ratings to Predict Depression Symptom Improvement**  
🔹 **Key Findings:**  
- A **daily 5-point Likert-scale** survey for **mood and anxiety** was used for monitoring depression treatment.  
- **67 participants** contributed data via a smartphone app.  
- Mood and anxiety ratings were significantly correlated with self-reported clinical questionnaire scores.  
- Evaluated **SVM, XGBoost, Random Forrest** using **transfer learning, feature selection, and explainability analysis**.  
- Machine learning models trained on these surveys achieved an **F1 score of 0.68**, indicating their reliability in tracking depression symptom improvement.  
- **Prediction accuracy was robust even with missing data**, making daily mood surveys a viable alternative to burdensome clinical questionnaires.  

📄 **Publication:**  
[Using Mobile Daily Mood and Anxiety Self-ratings to Predict Depression Symptom Improvement](https://ieeexplore.ieee.org/abstract/document/10614430)  
📌 *Soumyashree Sahoo, Chinmaey Shende, Md Zakir Hossain, Parit Patel, Xinyu Wang, Md Ishtyaq Mahmud, Jinbo Bi, Jayesh Kamath, Alexander Russell, Dongjin Song, Bing Wang.*  
📌 *Accepted for Proceedings of ACM/IEEE CHASE, 2024.*  


---

## 🔧 Implementation Details  
- Developed the **models using LSTM, GRU-D and BERT** and submissions are under review. Experimented with **Langchain GPT-4** for open-source datasets.  
- Developed a **full-stack application** (HIPAA compliant) using **JavaScript, JSON, Java/Android, and REST API** for sensory data integration.  
- Designed a **PostgreSQL database** and **ETL pipeline**, deployed on **GCP and AWS DevOps pipeline**.  
- Built a **Flask and JavaScript-based dashboard** with **BI tools (Plotly, Matplotlib)** to present predictions to clinicians.  
- Performed **testing of the web portal** and **API testing** using **Postman, Cucumber, Selenium, and A/B testing**.  
- Conducted **statistical analysis, segmentation, and visualization** of sensory data from smart devices using **Python and R**.  

---

## 🚀 Conclusion  
The **SmartHealth-Research** project highlights the **feasibility of using sensory data and mobile-based self-ratings** to monitor depression symptom improvement. The research demonstrates that **automated, objective monitoring tools** can be used effectively in clinical settings, reducing patient burden and improving mental health assessments.  

---

## 🔮 Future Work  
- Expanding the dataset with **diverse participant groups**.  
- Exploring **deep learning approaches** for time-series prediction.  
- Integrating **multimodal data** (e.g., heart rate, activity levels) for enhanced accuracy.  
- Deploying a **real-time monitoring system** using smartphone and wearable integration.  
---

This repository will include **research papers**.
