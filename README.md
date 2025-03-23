# AI Agent Operator - Quick Setup Guide

## 🛠️ Quick Setup Guide

Follow these steps to set up and run the AI Agent Operator on your local machine.

### 1️⃣ Clone & Enter Repository:
```bash
git clone https://github.com/browser-use/web-ui.git
cd web-ui
```

### 2️⃣ Install Dependencies (Choose ONE):
Using Pipenv:
```bash
pipenv install -r requirements.txt
```
OR using Pip:
```bash
pip install -r requirements.txt
```

### 3️⃣ Browser Automation Setup:
Ensure you have Playwright installed:
```bash
playwright install
```

### 4️⃣ Launch Web Interface:
Run the following command to start the web UI:
```bash
python webui.py --ip 127.0.0.1 --port 7788
```

---

## 🔑 API Key Sources:
To use AI models, obtain API keys from these sources:

- **GROQ API:** [Get API Key](https://console.groq.com/keys)
- **Google AI Studio:** [Get API Key](https://aistudio.google.com/app/apikey)

---

## 💡 Free API Alternatives (Limited Tier):
You can also use these free API alternatives with limited access:

- **Kluster AI:** [Visit Kluster AI](https://www.kluster.ai/)
- **Together AI:** [Visit Together AI](https://www.together.ai/)
- **Hyperbolic:** [Visit Hyperbolic](https://hyperbolic.xyz/)

---

## ⚠️ Notes:
- Ensure you have **Python 3.8+** installed.
- Playwright requires additional dependencies for headless browsing.
- If you encounter issues, check the documentation or raise an issue in the repository.

Happy coding! 🚀

