# BERT_XAI_8Methods

## Project Overview

This project investigates how a **BERT-based sentiment classifier** makes decisions on the **SST-2** dataset. The main notebook, [CourseProject-2025A.ipynb](CourseProject-2025A.ipynb), compares **eight explainable AI (XAI)** methods to understand which words or phrases influence the model's predictions.

## Included XAI Methods

- **Integrated Gradients (IG)**
- **LIME-Text**
- **SHAP-Text**
- **Sufficiency & Comprehensiveness**
- **Attention Rollout**
- **Anchors-Text**
- **DiCE-Text**
- **Activation / Path Patching**

## Objective

The goal is to:

- identify the **tokens or spans** that drive sentiment predictions,
- compare the **strengths and limitations** of different explanation methods,
- analyze **misclassified or ambiguous cases**, and
- evaluate how reliable each XAI method is for interpreting BERT decisions.

## Outputs

The project generates explanation summaries and related artifacts in the **xai_out** folder, which support comparison across methods and model behavior analysis.
