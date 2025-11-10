# Google ADK Agent Setup on Kaggle

Welcome to this project where you can set up and run a helpful AI assistant using Google's Agent Development Kit (ADK) and Gemini API—right inside a Kaggle notebook!

---

## About This Project

This project demonstrates how to use Google’s ADK together with Gemini API keys to build a smart assistant that can answer questions, search Google, and provide information interactively inside Kaggle.

---

## Getting Started

### 1. Get Your Google API Key

You need a Gemini API key from Google. Once you have it:

- Open your Kaggle notebook.
- Navigate to **Settings > Secrets**.
- Add a new secret with the key: `GOOGLE_API_KEY` and set your key as the value.
- Keep this key private!

### 2. Upload the Script

Upload the `google_adk_agent_setup.py` script to your Kaggle notebook workspace.

### 3. Run the Setup

Run the notebook cells step by step to:

- Set up the API key and environment variables.
- Import and initialize the Google ADK agent.
- Use the helper function to get the ADK web UI URL to interact with the agent.

### 4. Start Chatting with Your Assistant

Use the example async code snippet to ask your assistant any questions you want.

---

## Live Demo Tips

- Use the `get_adk_proxy_url()` function to get a clickable link to open the ADK Web UI.
- Make sure you start the ADK Web UI service in a separate cell **before** clicking the link.
- Use Python's `asyncio` to run your queries asynchronously within the Kaggle environment.

---

## Why This Project?

- Learn to use Google’s latest AI agent tools with real API integration.
- See how to securely manage API keys using Kaggle Secrets.
- Prototype intelligent assistants quickly inside notebooks.
- Get hands-on experience with interactive AI interfaces.

---

## Contributing & Support

Feel free to open issues if you encounter bugs or want to suggest improvements. Contributions are welcome!

Happy coding and exploring AI agents! 🚀

---
