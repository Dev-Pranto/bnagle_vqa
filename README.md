# BanglaVQA: Visual Question Answering with Qwen2-VL 🇧🇩 👁️

**BanglaVQA** is a multimodal AI project designed to perform Visual Question Answering (VQA) in the **Bengali language**. It leverages the state-of-the-art **Qwen2-VL-7B-Instruct** model to analyze images and generate accurate answers to questions asked in Bangla.

![Python](https://img.shields.io/badge/Python-3.10%2B-blue)
![Model](https://img.shields.io/badge/Model-Qwen2--VL--7B-violet)
![Task](https://img.shields.io/badge/Task-Visual_Question_Answering-green)

## 📂 Repository Contents

This repository contains the code and the results of the VQA experiments:

* **`qwen2vl.ipynb`**: The main Jupyter Notebook containing the end-to-end pipeline:
    1.  Data Loading & Preprocessing (mapping Bangla questions to COCO images).
    2.  Model Loading (Qwen2-VL-7B-Instruct).
    3.  Inference Loop (generating answers).
    4.  Evaluation (Fuzzy matching).
    5.  Report Generation (Excel, HTML, JSON).
* **`bangla_vqa_results_with_images.xlsx`**: An Excel report containing the test images, the Bengali questions, the model's answers, and the correctness score.
* **`bangla_vqa_report.html`**: An interactive HTML visual report for viewing results in a browser.
* **`bangla_vqa_results_detailed.json`**: A raw data file containing detailed metrics and logs for analysis.

## 📊 Performance Snapshot

Results based on a validation run of **150 samples**:

* **Model:** Qwen/Qwen2-VL-7B-Instruct
* **Total Samples:** 150
* **Accuracy:** 36.67% (Exact match or >85% similarity)
* **Average Similarity Score:** 57.60%
* **Correct Predictions:** 55 / 150

## 💻 Usage

### 1. Installation
To run the notebook locally or on Colab/Kaggle, you will need the following dependencies:

```bash
pip install torch transformers pillow fuzzywuzzy python-levenshtein xlsxwriter accelerate


I apologize for the confusion. I see from your screenshot that you have uploaded the output files and the notebook directly to the root of the repository.Here is the corrected README.md that perfectly matches the file structure shown in your image. It explains that the project is contained within the Jupyter Notebook.Markdown# BanglaVQA: Visual Question Answering with Qwen2-VL 🇧🇩 👁️

**BanglaVQA** is a multimodal AI project designed to perform Visual Question Answering (VQA) in the **Bengali language**. It leverages the state-of-the-art **Qwen2-VL-7B-Instruct** model to analyze images and generate accurate answers to questions asked in Bangla.

![Python](https://img.shields.io/badge/Python-3.10%2B-blue)
![Model](https://img.shields.io/badge/Model-Qwen2--VL--7B-violet)
![Task](https://img.shields.io/badge/Task-Visual_Question_Answering-green)

## 📂 Repository Contents

This repository contains the code and the results of the VQA experiments:

* **`qwen2vl.ipynb`**: The main Jupyter Notebook containing the end-to-end pipeline:
    1.  Data Loading & Preprocessing (mapping Bangla questions to COCO images).
    2.  Model Loading (Qwen2-VL-7B-Instruct).
    3.  Inference Loop (generating answers).
    4.  Evaluation (Fuzzy matching).
    5.  Report Generation (Excel, HTML, JSON).
* **`bangla_vqa_results_with_images.xlsx`**: An Excel report containing the test images, the Bengali questions, the model's answers, and the correctness score.
* **`bangla_vqa_report.html`**: An interactive HTML visual report for viewing results in a browser.
* **`bangla_vqa_results_detailed.json`**: A raw data file containing detailed metrics and logs for analysis.

## 📊 Performance Snapshot

Results based on a validation run of **150 samples**:

* **Model:** Qwen/Qwen2-VL-7B-Instruct
* **Total Samples:** 150
* **Accuracy:** 36.67% (Exact match or >85% similarity)
* **Average Similarity Score:** 57.60%
* **Correct Predictions:** 55 / 150

## 💻 Usage

### 1. Installation
To run the notebook locally or on Colab/Kaggle, you will need the following dependencies:

```bash
pip install torch transformers pillow fuzzywuzzy python-levenshtein xlsxwriter accelerate

