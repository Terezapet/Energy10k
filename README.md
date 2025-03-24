# Energy10k: Measuring Regulatory Exposure in 10-K Filings

This repository contains code, documentation, and analysis from a text-as-data project aimed at identifying and classifying **environmental and energy regulatory language** in corporate 10-K filings. The project uses a combination of manual coding, supervised learning, topic modeling, and large language models (LLMs) to develop replicable measures of regulatory exposure across industries.

## 🔍 Project Overview

Many companies disclose regulatory risks in their annual 10-K filings, particularly in the **Item 1A: Risk Factors** section. This project extracts those sections, preprocesses the text, and analyzes them using a suite of natural language processing (NLP) and machine learning tools.

The ultimate goal is to build a scalable pipeline to **quantify regulatory discourse**, distinguish between **energy vs. environmental regulation**, and explore **variation across sectors and government levels (federal, state, local)**.

---

## 📁 Repository Structure

| File | Description |
|------|-------------|
| `Final_Project_Report.pdf` | Report with final analysis, modeling, and write-up. |
| `Discovery_Memo.ipynb` | Early exploratory analysis using mutual information and topic modeling. |
| `Measurement_Memo.ipynb` | Codebook design, hand-coding of text, and intercoder reliability testing. |
| `Measurement_Memo_II.ipynb` | Supervised learning, model evaluation, and classification using ML & GPT. |
| `Regulatory_Discussion_Codebook.docx` | Codebook definitions used across the project for human and model classification. |
| `requirements.txt` | Python environment dependencies. |

---
