# MathMate AI

Mathematics problem-solving tutor built with Flask and Gemini `gemini-3.1-flash-lite`.

## Run locally
```bash
pip install -r requirements.txt
python app.py
```

Set `GEMINI_API_KEY` in `.env` first.

## Production
```bash
gunicorn app:app
```
