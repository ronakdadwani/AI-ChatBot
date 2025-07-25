# AI Real Estate Chatbot Backend

This project is the backend for an AI-powered chatbot for a real estate website. It uses FastAPI, OpenAI, and LangChain for agentic AI and automation.

## Structure

```
AI Chatbot/
│
├── app/
│   ├── main.py         # FastAPI entry point
│   ├── agents.py       # Agent logic (LangChain, tools, etc.)
│   ├── models.py       # Data models (Pydantic)
│   ├── utils.py        # Helper functions
│   └── config.py       # API keys, settings
│
├── requirements.txt    # Python dependencies
└── README.md
```

## Setup
1. Create a virtual environment:
   ```sh
   python -m venv venv
   source venv/bin/activate  # On Windows: venv\Scripts\activate
   ```
2. Install dependencies:
   ```sh
   pip install -r requirements.txt
   ```
3. Run the server:
   ```sh
   uvicorn app.main:app --reload
   ``` #   A I - C h a t B o t  
 