# News-Topic-Classification-on-AG-News-TF-IDF-Baseline-vs.-Fine-Tuned-DistilBERT
AG News topic classification: TF-IDF + Logistic Regression vs. fine-tuned DistilBERT. The classical baseline edged out the transformer (92.0% vs. 91.1% accuracy) when DistilBERT was trained on an 8k subset. Includes per-class F1 and confusion matrices, plus error analysis of Business ↔ Sci/Tech confusion.
Project: News Topic Classification (AG News)
Course: Natural Language Processing, A.Y. 2025-2026

Contents of this folder:
- agnews_project.ipynb   : self-contained Colab notebook (source code)
- NLP_Project_Report.docx: project report
- Presentation           : project presentation slides

Dataset:
This project uses the AG News dataset, loaded automatically via the
Hugging Face "datasets" library (load_dataset("ag_news")) at the start
of the notebook. No separate dataset file is included, as the dataset
is downloaded and cached automatically when the notebook is run.
