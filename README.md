# 🤖 Simple AI Chatbot using LangChain

A lightweight Streamlit-based AI chatbot built using [LangChain](https://www.langchain.com/), [OpenAI](https://platform.openai.com/), and [Hugging Face models](https://huggingface.co/models). It supports conversational response generation using pre-trained LLMs.

## 🚀 Features

- Chat interface powered by Streamlit
- Uses `LangChain` for LLM orchestration
- Connects to OpenAI or Hugging Face endpoints
- Simple configuration with environment variables
- Deployable on [Streamlit Cloud](https://streamlit.io/cloud)

---

## 🛠️ Setup Instructions

### 1. Clone the Repository
```bash
git clone https://github.com/kpant2190/Simple-AI-Chatbot-using-Langchain.git
cd Simple-AI-Chatbot-using-Langchain
```

### 2. Install Dependencies
```bash
pip install -r requirements.txt
```

### 3. Setup Environment Variables
```bash
OPENAI_API_KEY=your_openai_api_key
LANGCHAIN_API_KEY=your_langchain_api_key
LANGCHAIN_ENDPOINT=https://api.smith.langchain.com
LANGCHAIN_PROJECT=simple-chatbot
LANGCHAIN_TRACING_V2=true
```

For Streamlit Cloud, set the same values in the Secrets tab in TOML format:
```
OPENAI_API_KEY = "your_openai_api_key"
LANGCHAIN_API_KEY = "your_langchain_api_key"
LANGCHAIN_ENDPOINT = "https://api.smith.langchain.com"
LANGCHAIN_PROJECT = "simple-chatbot"
LANGCHAIN_TRACING_V2 = "true"
```




