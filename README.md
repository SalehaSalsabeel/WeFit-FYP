# WeFit AI: Personalized Cycle-Aware Fitness & Nutrition Recommender System

[![Python](https://img.shields.io/badge/Python-3.10%2B-3776AB?style=flat-square&logo=python&logoColor=white)](https://www.python.org/)
[![Flutter](https://img.shields.io/badge/Flutter-3.x-02569B?style=flat-square&logo=flutter&logoColor=white)](https://flutter.dev/)
[![FastAPI](https://img.shields.io/badge/FastAPI-Framework-009688?style=flat-square&logo=fastapi&logoColor=white)](https://fastapi.tiangolo.com/)
[![License](https://img.shields.io/badge/License-Academic%20Use-green.svg?style=flat-square)]()
[![Status](https://img.shields.io/badge/Status-In%20Development-orange.svg?style=flat-square)]()

WeFit AI is an intelligent health and wellness platform that harmonizes physical training, recovery routines, and nutritional recommendations with female hormonal fluctuations across the four menstrual cycle phases.

---

## 📌 Problem Statement
Most mainstream fitness applications deliver static, uniform workout and diet plans that overlook cyclical biological shifts. Menstrual phase transitions bring significant fluctuations in basal body temperature, metabolic rate, systemic fatigue, and joint laxity. Fixed exercise regimens during periods of acute fatigue or severe dysmenorrhea often result in overtraining, diminished compliance, and higher injury risk. 

**WeFit AI** resolves this disconnect by integrating cycle tracking, symptom telemetry, and biometric indicators into a personalized, context-aware machine learning recommendation engine.

---

## 🚀 Key Features

* **Phase-Aware Workout Adaptation:** Recommends optimal training modalities based on cycle phase (e.g., maximal strength and progressive overload during the follicular phase; low-impact mobility, pilates, and restorative yoga during the menstrual phase).
* **Dynamic Intensity Gating (MET Scoring):** Uses Metabolic Equivalent of Task (MET) constraints to automatically reduce workout volume and load when high stress, poor sleep, or severe cramps are logged.
* **Phase-Targeted Nutritional Planning:** Calculates macro splits and highlights essential micronutrients (e.g., Iron during menses, Magnesium and complex carbs during the luteal phase).
* **Multi-Modal Daily Check-Ins:** Captures continuous feedback (pain severity, sleep duration, energy level) to refine future recommendations.

---

## 📂 Repository Structure

```text
wefit-ai/
├── data/
│   ├── raw/
│   │   └── menstrual_cycle_data.csv          # Base training dataset
│   └── processed/                            # Normalized and cleaned datasets
├── docs/
│   ├── WeFit_AI_Proposal.pdf                 # FYP proposal document
│   └── WeFit_AI_Dataset_Specification.pdf    # Full data dictionary & schema
├── notebooks/
│   ├── 01_exploratory_data_analysis.ipynb    # Data distribution & correlation plots
│   └── 02_model_prototyping.ipynb            # ML model experimentation
├── src/
│   ├── api/                                  # FastAPI backend endpoints
│   ├── models/                               # Training scripts & exported models
│   └── recommender/                          # Rule-based & ML recommendation logic
├── .gitignore
├── README.md
└── requirements.txt                          # Python dependencies