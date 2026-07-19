# AI Chatbot ~ by Krishna Kalra

A simple web-based AI chatbot built with Flask and powered by Groq's LLM API.

## Features

- Chat interface in the browser
- Conversation memory (remembers earlier messages in the session)
- Powered by the `llama-3.3-70b-versatile` model via Groq

## Tech Stack

- **Backend:** Python, Flask
- **LLM Provider:** [Groq](https://groq.com/)
- **Frontend:** HTML (Flask templates)

## Setup

1. Clone this repository
   ```
   git clone https://github.com/YOUR_USERNAME/ai-chatbot.git
   cd ai-chatbot
   ```

2. Create a virtual environment and activate it
   ```
   python -m venv venv
   venv\Scripts\activate
   ```

3. Install dependencies
   ```
   pip install flask groq python-dotenv
   ```

4. Create a `.env` file in the project root and add your Groq API key
   ```
   GROQ_API_KEY=your_api_key_here
   ```

5. Run the app
   ```
   python app.py
   ```

6. Open your browser and go to `http://127.0.0.1:5000/`

## Notes

This project was built as a learning exercise to explore Flask, API integration, and building conversational AI interfaces.
