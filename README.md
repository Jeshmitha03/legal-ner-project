# legal-ner-project
A Legal Named Entity Recognition (NER) model built using transformer-based architectures like LegalBERT and RoBERTa. It extracts key entities such as Court, Case Number, Petitioner, Respondent, Date, and Law Section from Indian legal documents. Trained and evaluated on a domain-specific dataset.
# 🏛️ Legal Named Entity Recognition (NER)

This project focuses on building a Named Entity Recognition (NER) model tailored for Indian legal documents using transformer-based models like LegalBERT and RoBERTa.

## 📌 Objective

To identify and extract key legal entities (e.g., Court, Case Number, Petitioner, Respondent, Date, Law Section) from Indian legal texts using state-of-the-art NLP models.

## 🔧 Technologies Used

- Python
- Hugging Face Transformers
- LegalBERT, RoBERTa
- PyTorch / TensorFlow
- spaCy
- Pandas, NumPy
- Google Colab / Jupyter Notebooks

## 📁 Dataset

- Dataset: [AjayMukundS/Indian_Legal_NER_Dataset](https://huggingface.co/datasets/AjayMukundS/Indian_Legal_NER_Dataset)
- Format: BIO tagging for legal entities.

## ⚙️ Model Architecture

- Pretrained Model: LegalBERT / RoBERTa
- Token Classification Head
- Fine-tuning on custom legal NER dataset

## 📈 Evaluation Metrics

- Precision, Recall, F1-Score (entity-level and overall)
- Confusion Matrix for entity classes

## 💡 Results

- Achieved an F1-score of **[Your Score]%** on validation set
- Successfully identified key legal entities in test samples

## 🚀 How to Run

1. Clone the repo
   ```bash
   git clone https://github.com/yourusername/legal-ner-project.git
   cd legal-ner-project
