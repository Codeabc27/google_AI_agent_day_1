Google ADK Agent Setup on Kaggle
Welcome to this simple project where you can set up and run a helpful AI assistant using Google’s Agent Development Kit (ADK) and Gemini API—all within a Kaggle notebook!

What’s this project about?
This project shows you how to connect to Google’s ADK using your Gemini API key and create a smart assistant that can answer questions, search Google, and help you get information on the fly. It’s perfect if you want to explore conversational AI with cutting-edge Google models, right from your Kaggle environment.

How to get started
Get your Google API key ready
Before running, you need a Gemini API key from Google. Once you have it, go to your Kaggle notebook → Settings → Secrets and add:

Key: GOOGLE_API_KEY

Value: your actual API key (keep this private!)

Upload the script
Upload the file google_adk_agent_setup.py to your Kaggle notebook workspace.

Run the code
Run the cells step-by-step to set up the agent and start the assistant. The script also includes a helper for opening the ADK web UI in your browser so you can interact with the assistant nicely.

Ask your assistant
Use the provided example lines to start chatting with the agent asynchronously. You can ask it anything like “What is the Agent Development Kit from Google?” or “What languages does the SDK support?” and get smart answers in return.

Live demo tips
The ADK web UI runs separately. Use the helper function get_adk_proxy_url() to get a clickable link that opens the interface.

Make sure to run the web UI cell before clicking that link, or you might run into errors.

The example usage runs asynchronously, so if you’re running in Kaggle, be sure to use asyncio or run it in an async-friendly environment.

Why this project?
Explore Google’s latest AI agent toolkit with real API integration

See how to securely handle API keys with Kaggle Secrets

Learn how to build interactive AI apps inside notebooks

Quickly prototype intelligent assistants with web UI support

Need help or want to contribute?
Feel free to open issues or pull requests if you find bugs or want to improve the example. Happy coding and exploring AI agents!
