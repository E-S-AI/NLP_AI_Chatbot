# NLP AI Chatbot

An intelligent question-answering system using NLP techniques and the BART model from Hugging Face. This project combines semantic search using TF-IDF with answer generation via BART to provide accurate responses.

---

## 📁 Project Structure
project-root/
├── Code/
│ └── nlp_ai_chatbot.ipynb # Main project notebook
├── AI.csv # Dataset (Questions and Answers)
├── requirements.txt # Required Python packages
├── .gitignore # Git ignore file
└── README.md # This file

## 🚀 How to Run

1. **Install dependencies:**
   ```bash
   pip install -r requirements.txt

📦 Dependencies
pandas

nltk

scikit-learn

transformers

datasets

torch

sacrebleu

rouge-score

📊 How It Works
If the similarity score between the input question and existing data is ≥ 40% (based on TF-IDF + Cosine Similarity), the system returns the stored answer.

Otherwise, it generates a new answer using the facebook/bart-base model.

📝 Dataset
The AI.csv file must contain two columns:

Question: The question text

Answer: The reference answer text

🪪 License
This project is licensed under the MIT License.

👨‍💻 Author
A personal project to experiment with AI-based question answering techniques.

yaml
Copy
Edit

