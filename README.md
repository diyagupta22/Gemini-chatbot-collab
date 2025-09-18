# Gemini Chatbot

This is an AI chatbot powered by **Google Gemini API**.  
You can use this chatbot to have conversational AI experiences and get instant answers to your questions.

---

## Features
- Supports multi-turn conversations  
- Easy to run in Google Colab  
- Powered by Google Gemini API  

---

## Requirements
- Python 3.x  
- `google-generativeai` library  

Install dependencies:  
```bash
pip install google-generativeai
Setup

Set your Gemini API key as an environment variable:

import os
os.environ["GOOGLE_API_KEY"] = "your_api_key_here"


Configure Gemini in your notebook:

import google.generativeai as genai
genai.configure(api_key=os.environ["GOOGLE_API_KEY"])Run in Colab

Click the button below to open the notebook in Colab and run your chatbot:
