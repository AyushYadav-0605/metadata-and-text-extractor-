# Streamlit File Upload and Search App

## What this does
- Upload any file
- Extract metadata + text (supports .txt, .pdf, .docx)
- Store information in SQLite (`filedata.db`)
- Search by file name / metadata / text
- Grid result view + download button

## Setup
1. `cd "c:\Users\HP\New folder (3)"`
2. `python -m pip install -r requirements.txt`
3. `streamlit run app.py`

## Notes
- `uploads/` holds files
- `filedata.db` stores indexed records
- Extend `extract_text` for more file types if needed
