# codex
# 🤖 kymbob’s Kopilot

Welcome to **kymbob’s Kopilot** — my personal AI-powered coding assistant.
This repo is where I experiment with **local LLMs**, **custom APIs**, and **VS Code integrations** to create a self-hosted alternative to GitHub Copilot.

---

## ✨ Features
- 🧠 **ChatGPT / LLM Integration** – connect to local or cloud models (Ollama, AnythingLLM, LocalAI, OpenAI API)
- 🖥 **VS Code Support** – works with [Continue.dev](https://continue.dev) or REST Client to chat directly inside the editor
- 🛠 **Automation Scripts** – helper tools for development + AI workflows
- 📂 **Prompt Library** – reusable prompts and templates

---

## 🚀 Getting Started

### 1. Clone the Repo
```bash
git clone https://github.com/kymbob/codex.git
cd codex
```

### 2. Run the ChatGPT demo web page
Set your OpenAI API key and install dependencies:

```bash
export OPENAI_API_KEY="your-key"
pip install -r requirements.txt
python app.py
```

The app will run on [http://localhost:5000](http://localhost:5000). You can reverse-proxy it through Apache to serve on ports 80 or 443.
