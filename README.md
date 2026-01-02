# ICUB — Improvised Christ University ChatBot

This repository contains the "ICUB Improvised Christ University ChatBot" Jupyter notebook and supporting files.

What's included
- A sanitized Jupyter notebook: ICUB_Improvised_Christ_University_ChatBot_.ipynb
- requirements.txt — Python dependencies
- LICENSE — MIT
- .gitignore — common ignores

Quick start
1. Clone the repository.
2. Create a virtual environment:
   - python -m venv .venv
   - source .venv/bin/activate  (Linux/macOS) or .venv\Scripts\activate (Windows)
3. Install dependencies:
   - pip install -r requirements.txt
4. Set your API key securely:
   - Export env var OPENROUTER_API_KEY or OPENAI_API_KEY
   - Do NOT hardcode API keys in the notebook.
5. Open the notebook in Jupyter / Colab and run cells.

Security note
- The notebook originally contained a hard-coded key. It has been removed and replaced with code that reads from environment variables. Do not commit real keys.

Author: Neeraj Ashish Goli