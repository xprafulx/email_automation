# Automated Job Application Email Sender

This Python project automatically generates personalized job application emails and sends them along with your CV to a list of companies. It uses **AI (Ollama + Qwen model)** to craft emails based on the job description and your CV content.

---

## Features

- Reads job descriptions and company info from a CSV file.
- Extracts text from your CV (PDF format) to use in the email.
- Generates personalized, concise emails using AI.
- Sends emails via Gmail SMTP with CV attached.
- Logs success/failure for each sent email.
- Supports delays between emails to prevent spam detection.

---

## Requirements

- Python 3.9+
- Gmail account (with App Password if 2FA is enabled)
- Python packages:

```bash
pip install pandas requests ollama pdfplumber python-dotenv tqdm pydantic
