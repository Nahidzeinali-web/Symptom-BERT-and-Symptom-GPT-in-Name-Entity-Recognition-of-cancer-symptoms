BERT & GPT Named Entity Recognition for Nausea/Vomiting & Anxiety Detection
Project Overview
This project aims to develop and refine Named Entity Recognition (NER) models using BERT and GPT architectures to identify specific terms related to nausea/vomiting and anxiety in clinical notes. By building on Bio-clinical BERT and Bio-GPT, the project introduces models tailored for extracting these symptoms in electronic health records (EHRs). The goal is to enhance the accuracy of symptom detection for improved patient care and monitoring.

Project Structure
1. Preprocessing Dataset
In this stage, clinical notes are prepared for model training and testing. This includes data cleaning, tokenization, and standardization to ensure that the dataset is ready for further processing and model pretraining.

2. Further Pretraining on Bio-clinical BERT and Bio-GPT with Large EHR Clinical Notes
To make Bio-clinical BERT and Bio-GPT more effective in clinical contexts, these models are further pretrained on extensive EHR clinical notes. This pretraining step aims to enhance the model’s understanding of clinical language, especially in recognizing nuances related to symptom expressions.

3. Fine-tuning Symptom-BERT for Anxiety and Nausea/Vomiting Detection
Symptom-BERT is fine-tuned to recognize a diverse range of terms and expressions associated with anxiety and nausea/vomiting in clinical documentation. This phase focuses on customizing the model for high accuracy in these specific symptom categories.

4. Fine-tuning Symptom-GPT for Anxiety and Nausea/Vomiting Detection
Symptom-GPT, a GPT-based counterpart to Symptom-BERT, is fine-tuned similarly to Symptom-BERT. The model is trained to generate symptom-specific insights, enabling improved understanding and extraction of anxiety and nausea/vomiting mentions within clinical notes.

Contact:
For inquiries, please reach out to Nahid Zeinali at Nahid-Zeinali@uiowa.edu.
