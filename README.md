# 🎙️ Niraj Koli - Voice Interview Bot

This project is a Streamlit-based AI chatbot that impersonates **Niraj Koli**, a Generative AI Engineer, in a professional interview setting. It uses the OpenAI GPT model to respond to voice-based questions in real time, providing insightful, personalized, and technically grounded answers.

---

## 🚀 Features

- 🎤 Voice input using your microphone
- 🤖 Real-time responses from ChatGPT (impersonating Niraj)
- 🧠 Preloaded with Niraj's resume and career context
- 🗣️ Text-to-Speech (TTS) for voice responses
- 🔗 Modular prompt design for scalability

---

## 🧠 Personality Profile (System Prompt)

The bot has been trained to mimic Niraj Koli’s persona:
- GenAI Engineer skilled in RAG, LangChain, Hugging Face, and MLOps
- Completed BCG Forage simulation on financial chatbots
- Interned at Learnbay building LLM-based fraud/churn models
- Delivered high-performance Streamlit apps with real-time LLaMA responses
- Speaks with confidence, clarity, and professionalism

---

## 📁 Folder Structure

```
.
├── agent.py              # Main Streamlit app
├── prompts/
│   ├── __init__.py
│   └── prompts.py        # Contains INSTRUCTIONS and templates
└── .streamlit/
    └── secrets.toml      # Store your OpenAI API key here
```

---

## 🔧 Setup Instructions

### 1. Clone the Repository
```bash
git clone https://github.com/your-username/niraj-voice-bot.git
cd niraj-voice-bot
```

### 2. Install Requirements
```bash
pip install -r requirements.txt
```

### 3. Add Your OpenAI API Key

Create a `.streamlit/secrets.toml` file:
```toml
[default]
api_key = "sk-your-openai-api-key"
```

### 4. Run the App
```bash
streamlit run agent.py
```

---

## 📝 Example Questions You Can Ask

- What’s your life story in a few sentences?
- What are your strengths and challenges?
- How did you transition from Mechanical Engineering to AI?
- Tell me about your experience at Learnbay and BCG Forage.

---

## 📜 License

MIT License

---

## 🙋‍♂️ Author

Built by [Niraj Koli](https://www.linkedin.com/in/nirajkoli/)
