# YouTube Toxic Content Filter 🎯

This project is a Final Year artefact titled **"Protecting and Nurturing Young Minds"**, aimed at filtering harmful YouTube content using NLP.

## 🚀 Project Overview

Children are increasingly exposed to toxic and unproductive digital content. This system uses a fine-tuned **DistilBERT** transformer model to classify toxic YouTube-style comments and suggest educational alternatives.

Key features:
- ✅ DistilBERT fine-tuned on Jigsaw Toxic Comment dataset
- 🧠 Detects comments containing toxicity, insults, threats, hate speech, etc.
- 🧪 Logs toxic content and can recommend replacement suggestions
- 📊 Evaluation includes Accuracy, Precision, Recall, and F1 Score

## 🛠️ Tools & Technologies

- Python (Colab)
- Hugging Face Transformers (`distilbert-base-uncased`)
- PyTorch
- Scikit-learn
- Google Drive for model storage
- GitHub for version control

## 📈 Model Performance

| Metric     | Score   |
|------------|---------|
| Accuracy   | 95.80%  |
| Precision  | 91.04%  |
| Recall     | 62.89%  |
| F1 Score   | 74.39%  |

## 🗂️ Files Included

- `toxic_comment_bert_training.ipynb` – Full training, evaluation, and logging script
- `distilbert_finetuned/` – (Model saved in Google Drive; link or instructions can be added)
- `classification_log.csv` – Log of predictions (optional)

## 💡 Future Scope

- Integration into Chrome extension
- Live YouTube comment moderation
- Add multilingual support (e.g., Urdu, Hindi)
- Parent dashboard with viewing patterns and notifications

## 📄 License

This project is for academic and non-commercial research purposes only.
