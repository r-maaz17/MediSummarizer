# MediSummarizer

MediSummarizer is an advanced Natural Language Processing (NLP) pipeline designed to extract medical symptoms and classify diseases from unstructured clinical text. Utilizing **BioBERT** (a domain-specific language model pre-trained on large-scale biomedical corpora), this project aims to assist healthcare professionals by transforming dense medical notes into structured, searchable summaries.

---

## 🚀 Features

- **Symptom Extraction (NER):** Automatically identifies and extracts complex medical symptoms, conditions, and anatomical mentions from raw text notes.
- **Disease Classification:** Predicts disease categories based on the contextual information provided in clinical summaries.
- **BioBERT Integration:** Leverages state-of-the-art transformer architecture fine-tuned specifically for clinical and biomedical text structures.
- **Data Pipeline:** Includes full preprocessing scripts to clean medical text, handle tokenization alignment, and manage class imbalances.

---

## 🛠️ Tech Stack & Architecture

- **Language:** Python
- **Frameworks:** Hugging Face Transformers, PyTorch
- **Core Model:** BioBERT (`dmis-lab/biobert-v1.1`)
- **Data Manipulation:** Pandas, NumPy, Scikit-learn
- **Environment Management:** Virtualenv

---

## 📦 Setup & Installation

Follow these steps to run the pipeline locally:

1. **Clone the repository:**
   ```bash
   git clone [https://github.com/r-maaz17/MediSummarizer.git](https://github.com/r-maaz17/MediSummarizer.git)
   cd MediSummarizer
