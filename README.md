# google_AI_agent_day_1


# Google ADK Agent Setup on Kaggle

This project demonstrates how to use the Google Agent Development Kit (ADK) with Gemini API for question answering in Kaggle notebooks.

## Setup Instructions

1. **Add your Google API key to Kaggle Secrets**  
   - Go to your Kaggle notebook → Settings → Secrets  
   - Add key: `GOOGLE_API_KEY` with your Gemini API key as the value

2. **Upload `google_adk_agent_setup.py` to Kaggle notebook**

3. **Run the notebook cells**  
   - Import and setup the agent  
   - Run the helper function `get_adk_proxy_url()` to get the proxy UI URL for visual interface  
   - Run the ADK web UI in a separate cell (e.g., `!adk web start ...` as per Google docs)  
   - Use agent runner to query questions asynchronously

## Live Demo

Use the example code snippet below in Kaggle (async context):

