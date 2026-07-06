
---


# AI-Driven Precision Crop Recommendation

An automated, end-to-end Machine Learning classification pipeline developed and optimized using **IBM watsonx.ai AutoAI** and deployed on **IBM Cloud** to provide real-time, high-accuracy crop recommendations based on localized soil chemistry and atmospheric metrics.

---

## 📌 Project Overview
Traditional crop selection methods rely heavily on historical habits or broad-regional manual soil tests with long reporting backlogs. This leaves farmers highly vulnerable to localized climate fluctuations and rapid soil degradation. High variance in accuracy, slow turnaround times, and vulnerability to sudden weather changes can lead to localized crop failures, poor yields, and severe financial risk.

This project addresses these inefficiencies by building a reliable multi-class classification pipeline capable of mapping continuous chemical and climatic factors directly to a target crop category. This allows farmers to optimize regional yields while preserving valuable resources.

* **Domain:** Agriculture / Smart Farming
* **Developer:** Prajakta Bramhane
* **Repository Link:** https://github.com/PRAJ-u/crop-reccomdation.git
* **Deployment Space:** Live Online REST API Endpoint (`Crop_Recommendation`)

---

## 🛠️ Proposed Solution & Technology Stack
* **Cloud Platform:** IBM Cloud
* **AI Engine:** IBM watsonx.ai Studio (AutoAI Framework Environment)
* **Pipeline Enhancements:** AutoAI-driven automated data preprocessing, feature engineering (FE), algorithm selection, and hyperparameter optimization (HPO-1).
* **Champion Model Architecture:** LightGBM Classifier Ensemble
* **User Interface:** Responsive, client-facing deployment web view.

---

## 📊 Dataset Framework & Structural Inputs
The analytical model processes a structured dataset (`Crop_recommendation.csv`) comprising **7 independent numerical inputs** to predict the target crop category:

| Metric Name | Data Type | Description | Agronomic Relevance |
| :--- | :--- | :--- | :--- |
| **N** | Numerical | Ratio of Nitrogen content in soil (mg/kg) | Encourages robust leaf and vegetative development |
| **P** | Numerical | Ratio of Phosphorus content in soil (mg/kg) | Improves root development and seed creation |
| **K** | Numerical | Ratio of Potassium content in soil (mg/kg) | Controls water retention and disease resistance |
| **temperature** | Float | Environmental temperature (°C) | Controls photosynthetic rates and crop metabolism |
| **humidity** | Float | Relative humidity (%) | Governs transpiration and moisture balance |
| **ph** | Float | pH value of localized target soil | Dictates nutrient solubility and root absorption |
| **rainfall** | Float | Total volume of precipitation (mm) | Primary source of hydration for crop growth |

---

## 📈 System Performance & Pipeline Comparison
Using the AutoAI leaderboard environment, 9 individual pipelines were automatically generated and cross-validated:

* **Pipeline 6 (Snap Random Forest Classifier):** Achieved an overall accuracy of 98.1% using HPO-1 optimization.
* **Pipeline 5 (Snap Random Forest Classifier):** Achieved 98.1% accuracy with baseline parameters.
* **Pipeline 2 (LightGBM Classifier Ensemble - Champion):** **Achieved a top accuracy of 99.1%** via automated hyperparameter tuning, proving optimal leaf-wise tree growth and speed.

---

## 🚀 Production Verification Results
The trained LightGBM pipeline was promoted to an online deployment space on IBM Cloud to expose a production REST API. The endpoint was verified using a live testing record, yielding the following results:

* **Input Data Array:** Balanced environmental metrics profile.
* **Multiclass Classification Prediction:** `chickpea`
* **Prediction Confidence Score:** **100% Certainty**

---

## 🌟 Novelty and Uniqueness
* **End-to-End Automation:** Automates precision crop identification, removing manual verification backlogs and human guessing from the workflow.
* **No-Code Machine Learning Pipeline:** Leverages IBM watsonx.ai AutoAI to automatically uncover the best classification model without extensive manual coding.
* **Intelligent Platform Consolidation:** Multi-class classification processes 7 independent environmental parameters through a single intelligent layer to cleanly map to discrete target crop categories.
* **Unbiased Engineering:** Automated feature engineering extracts hidden soil-climate patterns, ensuring consistent, data-backed farming decisions.

---

## 🔮 Future Scope
1. **IoT Integrations:** Integrate live automated telemetry sensors directly into farm soil beds to stream soil parameters dynamically.
2. **Dynamic APIs:** Incorporate real-time local weather forecasting and GPS-tracked precipitation APIs directly into the pipeline.
3. **Global Scaling:** Expand historical datasets to include localized tropical, arid, and specialty crops to scale the system nationwide and globally.
4. **Mobile Deployment:** Expose native iOS/Android client apps supporting localized regional languages to break technology barriers for growers.

---

## 📜 Certificates Earned
* **Certificate 1: Getting Started with Artificial Intelligence**
  * *Issued by:* IBM SkillsBuild
  * *Issue Date:* June 24, 2026
  * *Verification Credential:* [Credly Badge](https://www.credly.com/badges/94ff80d7-9bd7-4f40-9559-933cb1f40aa4)
* **Certificate 2: Lab: Troubleshoot Your Code Using IBM Bob**
  * *Issued by:* IBM SkillsBuild
  * *Course Code:* ALM-COURSE_4071307
  * *Completion Date:* June 24, 2026 (GMT)

```
