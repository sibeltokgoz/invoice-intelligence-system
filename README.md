# Invoice Intelligence System

AI-powered financial document intelligence platform for invoice processing, accounting automation, inventory tracking, cost allocation, and financial analytics.

## Features

- PDF invoice upload
- Image invoice upload
- PDF text extraction
- OCR fallback for scanned documents
- AI-powered invoice field extraction
- Invoice line item extraction
- Accounting software integration
- Inventory tracking
- Cost center allocation
- Financial analytics engine

## Tech Stack

Backend:
- Python
- FastAPI

AI Layer:
- OpenAI API

Document Processing:
- PyMuPDF
- Tesseract OCR

Database:
- PostgreSQL

Queue:
- Redis + Celery

Storage:
- Local Storage (MVP)
- AWS S3 (Production)

Future Roadmap:

Phase 1:
- Document ingestion

Phase 2:
- Structured invoice extraction

Phase 3:
- Invoice item classification

Phase 4:
- Accounting integration

Phase 5:
- AI analytics engine

Example future query:

"How much did we spend on electrical equipment in the last 12 months?"

Expected output:

ABC Elektrik → 42,000 TRY  
Mega Kablo → 17,500 TRY  
Teknik Bobin → 6,800 TRY  

Total → 66,300 TRY
