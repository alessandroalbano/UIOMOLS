---
title: Project Publications
date: 2026-02-11
summary: Scientific publications related to the UIOMOLS project and associated research activities.
view: compact
---

This section collects peer-reviewed journal articles and conference papers related to the UIOMOLS project and its methodological developments in clinical Natural Language Processing, causal machine learning, and statistical analysis of Electronic Health Records.

---

## 📰 Journal Article

### Causal Forests for Discovering Diagnostic Language in Electronic Health Records  
**Alessandro Albano, Chiara Di Maria, Mariangela Sciandra, Antonella Plaia**  
*First published: 25 August 2025*  
🔗 https://doi.org/10.1002/asmb.70038  

This paper introduces a causal machine learning framework based on Causal Forests to identify diagnostic language patterns within Electronic Health Records (EHRs), providing interpretable insights into clinically relevant textual features.

---

## 📘 Conference Papers

### Cross Lingual Embeddings for Clinical Text: A Statistical Framework for Validating Real and Synthetic Electronic Health Records  
**Marco Speciale, Alessandro Albano, Mariangela Sciandra, Antonella Plaia**  
*Scientific Meeting of the Italian Statistical Society*, 16 June 2025  
Springer Nature Switzerland, pp. 351–356  


**Abstract**  
The effective integration of real and synthetic clinical data in multiple languages is essential to advance healthcare research. This study proposes a statistical framework leveraging cross-lingual embeddings to validate semantic alignment between authentic Italian EHRs and synthetic English clinical notes. Using state-of-the-art models (E5 and BGE), texts are encoded and analysed via Fuzzy C-Means clustering and multidimensional scaling. The results highlight language-specific structures alongside robust cross-lingual alignment, demonstrating the potential of synthetic data augmentation in addressing resource scarcity.

---

### Investigating Comorbidities from Clinical Texts: A Propensity Score Approach  
**Alessandro Albano, Chiara Di Maria, Mariangela Sciandra, Antonella Plaia**  
*Scientific Meeting of the Italian Statistical Society*, 16 June 2025  
Springer Nature Switzerland, pp. 227–232  


**Abstract**  
This work proposes a methodology to detect comorbidities from clinical discharge notes using propensity scores derived from textual features. Textual information is summarised and incorporated into logistic regression models to assess disease associations. The study compares TF-IDF representations and text embeddings using LASSO, XGBoost, and multilayer perceptrons (MLP). Applied to diabetes and Chronic Kidney Disease, the results demonstrate the value of NLP-based representations in epidemiological analysis.

---

### Causal Machine Learning for Medical Texts  
**Alessandro Albano, Chiara Di Maria, Mariangela Sciandra, Antonella Plaia**  
*Scientific Meeting of the Italian Statistical Society*, 17 June 2024  
Springer Nature Switzerland, pp. 34–39  


**Abstract**  
This paper proposes a causal framework for analysing medical texts using the MIMIC-III dataset. By applying Causal Forests, the study identifies linguistic factors that causally influence the probability of specific diagnoses. The results reveal significant causal relationships between clinical terminology and hypothyroidism diagnosis, highlighting the importance of causal inference in medical NLP.

---
### Ensemble Method for Text Classification in Medicine with Multiple Rare Classes  
**Alessandro Albano, Mariangela Sciandra, Antonella Plaia**  
*Book of Short Papers – CLADAG 2023*, p. 17  

**Abstract**  
This paper presents an ensemble method for text classification in the presence of multiple rare classes within medical record data. The study focuses on classifying clinical notes into multiple disease categories, including rare diseases.

The proposed ensemble approach combines the predictions of three machine learning models — Support Vector Machine (SVM), Random Forest, and Naive Bayes — to improve diagnostic prediction accuracy.

The results show that the ensemble strategy outperforms individual models in terms of classification performance. The methodology was evaluated on a dataset of 50,000 clinical notes containing multiple rare classes, demonstrating the effectiveness of ensemble learning in complex medical text classification tasks.
