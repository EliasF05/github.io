---
layout: default
title: Elias Frühwein - Data Science Portfolio
---

# Elias Frühwein
**Data Science Master's Student at ETH Zurich**  
📍 Zurich, Switzerland | 📧 [elias@fruehwein.net](mailto:elias@fruehwein.net) | 🔗 [LinkedIn](https://linkedin.com)

---

## 🎓 Education

### **ETH Zurich** *(Sep. 2026 – Jun. 2028 Expected)*
* **Master of Science in Data Science**
* *Zurich, CH*

### **Maastricht University** *(Sep. 2023 – Jun. 2026)*
* **Bachelor of Science in Data Science and Artificial Intelligence**
* *Maastricht, NL*
* **Metrics:** GPA: 9.21/10 (Summa Cum Laude) | Ranked **1st** in a cohort of 189 students.
* *Note:* Successfully managed a 2-year 40% part-time internship alongside tutoring in parallel with full-time studies.

### **German International School New York** *(Sep. 2019 – Jul. 2023)*
* **German International Abitur & New York State High School Diploma**
* *White Plains, NY, USA*
* **Honors:** Awarded Abitur Book Prize (German Physical Society's top physics honor per graduating class).

---

## 💼 Experience

### **Aucos AG** | *Machine Learning Research Intern*
*Sep. 2024 – Jun. 2026 | Aachen, DE*
* **Role:** Solely responsible for predictive time series anomaly detection in electroplating lines.
* **Research & Modeling:** Developed an unsupervised Gaussian mixture model for density estimation that predicts whether voltage will diverge from the nominal range up to 1 hour ahead of time.
* **Deep Learning:** Trained an LSTM autoencoder for anomaly detection and a CNN to map voltage and current time series to the physical parameters of a rectifier circuit.
* **Performance:** Optimized for a near-zero false-positive rate to avoid alarm fatigue in a real-time (1 check every 10s) production setting; achieved $TPR = 0.7$ at $FPR = 0$ on held-out data.
* **Deployment:** Developed and integrated a C++ service to deploy the model into production software.

### **Maastricht University** | *Teaching Assistant*
*Sep. 2025 – Jan. 2026 | Maastricht, NL*
* **Courses:** Discrete Mathematics, Logic.
* **Responsibilities:** Explained fundamental concepts in tutorials and graded student assignments.

---

## 📚 Publications & Projects

### **Reconstruction of Quantized Time Series with Particle Methods** *(Feb. 2026 – Jul. 2026)*
> **Authors:** Elias Frühwein, Dr. Philippe Dreesen, Dr. Anirudh Wodeyar.  
> *Status: In preparation, targeting submission to IFAC SysID 2027.*
* Derived and implemented the following for an $AR(p)$ model with quantized observations:
  * Fully adapted auxiliary particle filter
  * Particle EM algorithm
  * Particle estimate of observed-data log-likelihood (enabling AIC-based order estimation)
* **Results:** Reconstructed signal shows a statistically significant increase in $R^2$ over the quantized signal on $AR(p)$ data, under model misspecification, and on real-world data across several domains.

### **GradNode** | [GitHub Repository](https://github.com/EliasF05/GradNode) *(Feb. 2024 – Mar. 2024)*
* Built **GradNode**, a lightweight autograd framework written completely in Java from scratch (no LLM assistance).
* Developed **JNN**, a Multi-Layer Perceptron (MLP) framework built directly on top of GradNode.

---

## 🛠 Skills & Coursework

* **Programming Languages:** Python, MATLAB, SQL, Java, C++ (Intermediate)
* **Libraries & Frameworks:** PyTorch, Statsmodels, Scikit-Learn, NumPy, pandas
* **Relevant Coursework:** Machine Learning, Natural Language Processing, Simulation & Statistical Analysis, Probability & Statistics, Linear Algebra, Mathematical Modeling
* **Spoken Languages:** German (Native), English (C2)
