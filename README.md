# Lernjournal4 App

Small Streamlit app for quick sentiment analysis of user text.

## What it does

- Takes free-form text input
- Runs sentiment classification with Hugging Face Transformers
- Returns label (`POSITIVE` / `NEGATIVE`) and confidence score

Current model in use:
- `distilbert-base-uncased-finetuned-sst-2-english`

## Run locally

```bash
python -m venv .venv
# Windows: .venv\\Scripts\\activate
# macOS/Linux: source .venv/bin/activate
pip install -r requirements.txt
streamlit run streamlit_app.py
```

## Notes

This repository is a lightweight learning project focused on NLP + Streamlit basics.