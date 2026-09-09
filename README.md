# A Multi-Modal Quantification of Parkinson's Medication Response
**A Proof-of-Concept Study for Remote Telemonitoring**

---

**Published in:** 2025 IEEE 22nd India Council International Conference (INDICON)

### 👥 Authors
* **Abhishriya Mahanta**
* **Dhruv Kansal** 
* **Daksh** 
* **Shubhajit Roy Chowdhury** 
*Indian Institute of Technology (IIT) Mandi, Himachal Pradesh, India*

---

### 📄 Read the Full Paper
[**Download the PDF Here**](./A_Multi-Modal_Quantification_of_Parkinsons_Medication_Response_Using_Kinematic_Rigidity_Profiling_and_Acoustic_Feature_Regression_A_Proof-of-Concept_Study%20(1).pdf)

---

### 🔬 Project Overview
This repository presents a novel, integrated telemonitoring system designed to evaluate Parkinson’s disease (PD) progression remotely. Instead of relying on traditional, resource-intensive clinical visits, this system offers a continuous estimation of a patient's medication response by combining two complementary modalities:

* **Kinematic Rigidity Profiling:** We utilize synchronized Inertial Measurement Units (IMUs) attached to the hand and forearm to objectively quantify wrist rigidity and resistance to passive movement.
* **Acoustic Feature Regression:** We analyze speech signals from sustained phonations using an XGBoost machine learning model to predict Unified Parkinson's Disease Rating Scale (UPDRS) scores.

By fusing these modalities, the system generates a unified **Medication Response Score (MRS)**. This provides clinicians with a continuous, dynamic estimation of a patient's state, rather than a simple binary ON/OFF medication detection.

### 📊 Key Highlights & Results
* **High Predictive Accuracy:** The XGBoost regression model demonstrated robust performance, achieving an **R² of 0.887** and a Mean Squared Error (MSE) of **11.49**.
* **Clinical Reliability:** A Bland-Altman analysis confirmed minimal bias, with over 95% of predicted values falling closely within acceptable limits of agreement compared to clinician-rated UPDRS scores.
* **Real-World Feasibility:** The study validates the use of low-cost, portable hardware (including an STM32 microcontroller and high-quality IMUs) for non-invasive, continuous at-home symptom tracking.
