# 🗼 Paris Travel Chatbot

A conversational AI chatbot designed to answer tourist-related questions about Paris landmarks using open-source language models from Hugging Face. This project replicates a ChatGPT-style experience locally — no OpenAI API key required.

---

## ✨ Features

- Answers travel-related questions about Paris (e.g., directions, landmark details, artwork suggestions).
- Replaces OpenAI's GPT API with **Mistral-7B-Instruct** from Hugging Face.
- Role-based prompt structure using `"system"`, `"user"`, and `"assistant"` roles.
- Temperature control and max token settings for predictable outputs.
- Local inference using `transformers` and `PyTorch`.

---

## 📌 Sample Questions

- How far away is the Louvre from the Eiffel Tower (in miles) if you are driving?
- Where is the Arc de Triomphe?
- What are the must-see artworks at the Louvre Museum?

---

## 🧠 Model Used

- [`mistralai/Mistral-7B-Instruct-v0.1`](https://huggingface.co/mistralai/Mistral-7B-Instruct-v0.1)  
Instruction-tuned open-source LLM optimized for chat applications.

---

## 🛠 Technologies & Libraries

- Python
- Hugging Face Transformers
- PyTorch
- Sentence-based prompt design

---

## 🚀 How to Run

1. **Clone the repo**
   ```bash
   git clone https://github.com/TeddyM1975/Paris-Travel-Chatbot.git
   cd Paris-Travel-Chatbot
   
2. **Install dependencies**
   ```bash
    pip install -r requirements.txt
3. **Run the chatbot script**
   ```bash
   python chatbot.py

Ensure you have a GPU-enabled setup or sufficient memory to run 7B models locally. You can also try smaller models like tiiuae/falcon-7b-instruct if needed.

## 📁 File Structure
  Paris-Travel-Chatbot/
  │
  ├── chatbot.py               # Main script to run the chatbot
  ├── requirements.txt         # Dependencies
  └── README.md                # Project overview

## 🙌 Acknowledgements
- Hugging Face for open-access instruction-tuned models.
- Mistral AI for the excellent Mistral-7B-Instruct model.

## 📜 License
This project is open-source and available under the MIT License.
