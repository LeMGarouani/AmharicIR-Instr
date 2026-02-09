# AmharicIR-Instr

This repository contains the proposed Amharic datasets for **instruction tuning** and **information retrieval (IR)**.

The fine-tuned models associated with these datasets are available on [**HuggingFace**]( https://huggingface.co/mgarouani/Amharic/tree/main)

---

## 📁 Repository Structure

The repository is organized into two main components: 

## 1️⃣ Amharic GPT-Style Prompt–Response Dataset

This directory contains instruction–response style data designed for training and evaluating information retrieval models in Amharic.

### Files:
- **`amharic_gpt_dataset.json`**  
  The main dataset in JSON format, consisting of Amharic prompt–response pairs.

- **`amharic_gpt_dataset.csv`**  
  A CSV version of the same dataset for easier inspection and preprocessing.

- **`amharic_GPT_cleaned.xlsx`**  
  A cleaned and structured Excel version of the dataset, intended for manual inspection and statistical analysis.

These datasets are suitable for:
- Instruction tuning  
- Question answering  
- Amharic text generation  

---

## 2️⃣ Amharic Query–Document Triplets for Dense Retrieval

This directory contains datasets designed for training/evaluating information retrieval models using *(query, positive document, negative document)* triplets.

### Files:
- **`JSONL format`**  
  Triplet-based dense retrieval dataset in JSONL format suited for the BEIR IR framework.
  
- **`amharic_dense_ir.json`**  
  Triplet-based dense retrieval dataset in JSON format.

- **`amharic_dense_ir.csv`**  
  CSV version of the dense retrieval dataset.

- **`All dense retrieval dataset.xlsx`**  
  A consolidated Excel file containing the full dense retrieval dataset.

These datasets are suitable for:
- Dense Passage Retrieval (DPR)  
- Bi-encoder training  
- Neural information retrieval in Amharic  

---

## 📝 File Generation Prompts

- **`prompts.docx`** 
instruction prompts for LLM-generated queries
---


## 📌 Available Formats

All datasets are provided in multiple formats (JSON, CSV, XLSX) to support:
- Model training  
- Exploratory data analysis  
- Reproducible research workflows  

---






