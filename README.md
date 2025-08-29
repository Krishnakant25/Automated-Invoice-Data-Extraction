# Automated Invoice Data Extraction (n8n Workflow)

This n8n workflow automates the process of extracting data from invoices (PDFs or images) using OCR and AI, validates key fields, and stores structured results into Google Sheets for seamless reporting and tracking.

## 🚀 Features
- Extracts text from PDF/Image invoices via OCR.
- Uses AI-powered parsing to identify invoice fields (invoice no, date, items, totals, etc.).
- Validates extracted data before saving.
- Stores results automatically in Google Sheets.
- Supports both line-item details and invoice summaries.

## 📂 Workflow Overview
1. Upload invoices to Google Drive.  
2. Workflow downloads and processes files.  
3. OCR/AI extracts structured data.  
4. Results appended/updated in Google Sheets.  

## 🛠️ Tech Stack
- [n8n](https://n8n.io/) (workflow automation)
- OCR API (OCR.space)
- Google Drive (input source)
- Google Sheets (output storage)
- AI model (Google Gemini / LangChain integration)

## 📦 Usage
1. Import the provided JSON template into your n8n instance.  
2. Configure your credentials (Google Drive, Google Sheets, OCR API key).  
3. Run the workflow and upload invoices to your configured Drive folder.  
4. Extracted data will appear in your linked Google Sheet.
   
## 📜 License
This project is shared under the MIT License for educational purposes.  
_This workflow is inspired by a bootcamp project and adapted for portfolio use._  

## 🙌 Acknowledgments
Special thanks to the [Codebasics AI Automation Bootcamp](https://codebasics.io/) for the guidance and learning resources.

<img width="1184" height="491" alt="Invoice_data_extraction" src="https://github.com/user-attachments/assets/1de31508-4de2-4bb8-8365-8cb59aa70485" />
