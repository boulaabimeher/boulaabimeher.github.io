---
layout: default
title: Publications & Supervision
---

[← Back to Home](index.html)

# 📄 Publications & Supervision

---

## Publications

### [Enhancing Diabetic Retinopathy Classification with Swin Transformer and Shifted Window Attention](https://link.springer.com/chapter/10.1007/978-3-031-95841-0_11)

**Boulaabi, M.**, et al. (2025)  
*Artificial Intelligence in Medicine Europe (AIME 2025)*, Springer Nature

**Abstract:**  
Novel approach to diabetic retinopathy classification using Swin Transformer architecture with shifted window attention mechanism. Achieved state-of-the-art results on multiple benchmark datasets with comprehensive evaluation across APTOS 2019 and IDRiD datasets.

**Key Results:**
- 89.65% accuracy on APTOS 2019 dataset (3,662 fundus images)
- 97.40% accuracy on IDRiD dataset
- AUC-ROC: 0.94-0.98 across different DR severity grades
- 20% improvement in model generalization through novel preprocessing pipeline

**Technical Contributions:**
- CLAHE adaptive contrast enhancement on LAB color space
- Automated circular ROI extraction
- Targeted data augmentation strategies
- Cross-dataset validation methodology

[📄 Read Paper](https://link.springer.com/chapter/10.1007/978-3-031-95841-0_11) | [📊 View Results](#)

---

### [Advanced Segmentation of Diabetic Retinopathy Lesions Using DeepLabv3+](https://ieeexplore.ieee.org/document/10912539)

**Boulaabi, M.**, et al. (2024)  
*Proceedings of IEEE/ACS International Conference on Computer Systems and Applications (AICCSA 2024)*

**Abstract:**  
Comprehensive study on lesion segmentation in diabetic retinopathy using DeepLabv3+ architecture with ASPP. Demonstrated exceptional performance with 99% accuracy on IDRiD dataset for multiple lesion types.

**Key Results:**
- 99% segmentation accuracy
- Dice coefficient: 0.97
- IoU (Intersection over Union): 0.95
- Lesion-level sensitivity: 92-97% across all lesion types

**Lesion Types Analyzed:**
- Microaneurysms (MA)
- Exudates (EX)
- Hemorrhages (HE)
- Soft Exudates (SE)

**Technical Innovation:**
- Domain-specific preprocessing pipeline
- CLAHE enhancement on L-channel of LAB color space
- Automated ROI extraction methodology
- Multi-architecture comparison framework

[📄 Read Paper](https://ieeexplore.ieee.org/document/10912539) | [📊 View Results](#)

---

## 📝 Manuscripts in Preparation

### Concept Bottleneck Models for Interpretable Medical Image Diagnosis

**Status:** Manuscript in preparation  
**Expected Submission:** Q2 2026

**Focus:**  
Development of an interpretable deep learning framework based on Concept Bottleneck Models (CBM) for medical diagnosis with clinician-verifiable reasoning.

**Key Components:**
- Integration of LLMs for concept extraction
- Clinician-verifiable intermediate representations
- Multi-modal medical imaging analysis
- Deployment on HPC infrastructure

---

## 👥 Supervision & Mentoring

### Master's Thesis Co-Supervision (3 M2 Students)
**[University of Tunis, ENSIT](https://www.ensit.tn/)**  
*February 2025 - December 2026*

---

### Thesis 1: Automated Melanoma Detection using Deep CNNs

**Student:** M2 Research Student  
**Duration:** February 2025 - December 2026  
**Focus:** Dermatological Image Analysis with Explainable AI

**Research Objectives:**
- Design comprehensive research protocol for melanoma detection
- Implement ensemble architectures (ResNet, EfficientNet, Vision Transformers)
- Develop Grad-CAM explainability framework
- Validate on HAM10000 dataset (10,000+ dermatological images)

**Key Deliverables:**
- Comparative analysis of CNN and Transformer architectures
- Explainability dashboard for clinical decision support
- Cross-validation across multiple skin lesion datasets
- Production-ready deployment pipeline

**Skills Developed:**
- Medical image preprocessing and augmentation
- Ensemble learning techniques
- Explainable AI implementation
- Clinical validation methodologies

---

### Thesis 2: Comparative Analysis of Architectures for DR Detection with XAI

**Student:** M2 Research Student  
**Duration:** February 2025 - December 2026  
**Focus:** Diabetic Retinopathy Detection with Interpretability

**Research Objectives:**
- Systematic comparison of CNN vs. Transformer architectures
- Implementation of multiple explainability methods (Grad-CAM++, LIME, SHAP)
- Cross-dataset evaluation and robustness analysis
- Clinical interpretability assessment

**Architecture Comparison:**
- CNNs: ResNet-50, EfficientNet-B4, DenseNet-121
- Transformers: Vision Transformer (ViT), Swin Transformer
- Hybrid models: CNN-Transformer combinations

**XAI Methods:**
- Grad-CAM++ for visual explanations
- LIME for local interpretability
- SHAP for feature importance
- Attention visualization for transformers

**Expected Outcomes:**
- Comprehensive benchmark study
- Best practices for DR detection
- Interpretability guidelines for clinical deployment

---

### Thesis 3: Fine-Tuning LLMs for English-Arabic Medical Translation

**Student:** M2 Research Student  
**Duration:** February 2025 - December 2026  
**Focus:** Multilingual Medical NLP  
**Collaboration:** Union of Arab Scientific Research Councils

**Research Objectives:**
- Domain adaptation of multilingual models (mT5, mBART)
- Implementation of LoRA (Low-Rank Adaptation) for efficient fine-tuning
- Creation of specialized English-Arabic medical translation dataset
- Development of deployment strategy for clinical settings

**Technical Approach:**
- Parameter-efficient fine-tuning with LoRA
- Medical terminology alignment
- Quality evaluation metrics for translation
- Clinical validation with domain experts

**Dataset Development:**
- Curated medical literature corpus
- Clinical report translations
- Medical terminology glossary
- Quality assurance pipeline

**Expected Impact:**
- Bridge language barriers in medical research
- Enable Arabic-speaking clinicians to access English medical literature
- Contribute to multilingual medical NLP research

---

## 📊 Supervision Philosophy

My approach to student supervision emphasizes:

- **Hands-on Learning:** Practical implementation alongside theoretical understanding
- **Research Independence:** Encouraging students to develop their own research questions
- **Reproducibility:** Teaching best practices in code documentation and experiment tracking
- **Clinical Relevance:** Ensuring research has real-world medical applications
- **Publication Preparation:** Guiding students through the academic writing process

---

## 🎯 Future Supervision Interests

I am interested in supervising students on topics including:

- Interpretable AI for medical imaging
- Vision transformers for healthcare applications
- Multi-modal medical data fusion
- Large language models for clinical decision support
- Federated learning for privacy-preserving medical AI

---

[← Back to Home](index.html) | [Next: Teaching Experience →](teaching.html)
