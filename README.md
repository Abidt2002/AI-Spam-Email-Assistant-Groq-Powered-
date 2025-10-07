# 🧠 AI Spam Email Assistant (Groq-Powered)

## 📧 Overview  
The **AI Spam Email Assistant** is an intelligent web app that detects whether an email or message is **spam or legitimate**, and explains **why** — powered by **Groq LLMs** for fast, explainable AI responses.  

It combines a **machine learning spam detection model** trained on a labeled dataset with an **AI reasoning assistant** for interactive explanations.  

You can ask questions like:  
> “Is this email real?”  
> “Why is this marked as spam?”  
> “How can I make my message not look spammy?”  

---

## 🚀 Features  
✅ Detects spam vs. non-spam messages using a trained ML model  
✅ Provides natural-language explanations powered by **Groq AI**  
✅ Web interface built with **Streamlit**  
✅ Secure key handling (API keys hidden in environment variables)  
✅ Real-time public sharing via **Ngrok**  

---

## 🧩 Tech Stack  
- **Python 3.12+**  
- **Scikit-learn** (for spam classifier training)  
- **Groq API** (for AI assistant responses)  
- **Streamlit** (for interactive UI)  
- **Ngrok** (for Colab deployment)  

---

## 🧠 Model Architecture  
- **Vectorizer:** TF-IDF text vectorizer  
- **Classifier:** Logistic Regression (trained on custom email dataset)  
- **LLM Assistant:** Groq-powered reasoning engine (`llama3-8b-8192`)  

---

## 📂 Project Structure
📁 AI-Spam-Email-Assistant/
│
├── app.py # Streamlit + Groq chatbot app
├── train_model.ipynb # Model training notebook
├── model.pkl # Trained ML model
├── vectorizer.pkl # TF-IDF vectorizer
├── dataset.csv # Email spam dataset
├── requirements.txt # Dependencies
└── README.md # Project documentation

🧪 Example Usage

Input:
“Congratulations! You’ve won a $500 Amazon gift card.”
Output:
Spam Detected!
Reason: Contains promotional trigger words and unrealistic offers.

🔒 Security
API keys are securely stored using environment variables.
Model and data remain private within Colab or your local machine.

🌐 Live Demo (Colab)

Deploy instantly on Google Colab:
🔗 [https://colab.research.google.com/drive/1dK3EcNs7C-JkO0qprtZsCtdrSRXvlRqG?usp=sharing]

🤖 Future Enhancements
Multilingual spam detection
Email header and metadata analysis
Gmail API integration
Model fine-tuning with larger datasets

🧑‍💻 Author
Abid Khan
AI Engineer | Researcher in ML/DL | Enthusiast in LLM Applications
