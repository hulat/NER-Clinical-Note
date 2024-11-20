# NER-Clinical-Note

This repository contains the code and models necessary to perform **Named Entity Recognition (NER)** tasks on clinical notes in Spanish. We use pre-trained models that have been fine-tuned to improve their performance in NER tasks within the clinical domain.

## Models Used

To carry out the NER task, the following **pre-trained models** have been used, which have been specifically fine-tuned for the clinical domain:

1. **PlanTL-GOB-ES-roberta-base-biomedical-clinical-es**
2. **PlanTL-GOB-ES-roberta-large-bne**
3. **XLM-RoBERTa-base**

## Files and Directories

- **notebooks/**: Contains the Jupyter notebooks used for experimentation and model training. Here you will find practical examples of how to run the models and perform fine-tuning.
- **requirements.txt**: A file that lists the dependencies needed to run the code and models in your local environment.

## Requirements

To run this project, make sure you have the following dependencies installed:

```bash
pip install -r requirements.txt