🔍 LLM Document Analyzer

An intelligent document analyzer that identifies document types (contracts, invoices, reports) and detects missing critical fields using a simulated LLM-based approach.

This project extracts text from PDF files, classifies the document type with confidence scoring, and highlights fields found, missing, and recommended improvements.

🚀 Features

📄 PDF Upload & Text Extraction (via PDF.js)

🤖 AI-like Document Classification (contract, invoice, or report)

✅ Field Detection – identifies required fields based on document type

❌ Missing Field Detection – highlights what’s missing

💡 Smart Recommendations to improve document completeness

🖥️ Clean, Modern UI with drag-and-drop support

📂 Supported Document Types

Contract → Checks for parties, signature, date, payment terms

Invoice → Checks for invoice number, amount, due date, tax, bill to/from

Reports → Classified as general documents (basic analysis)

🛠️ Tech Stack

Frontend: HTML, CSS, JavaScript

PDF Parsing: PDF.js

Document Analysis: Simulated LLM logic (regex-based patterns & heuristics)

📷 Demo Workflow

Upload or drag & drop a PDF.

Extracted text is analyzed.

Document type & confidence score are displayed.

Fields found and missing are highlighted.

Recommendations and extracted text preview are shown.

⚡ How to Run

Clone this repository:

git clone https://github.com/your-username/llm-document-analyzer.git
cd llm-document-analyzer


Open skillrankLLM.html in your browser.

Upload a PDF file and click Analyze Document.

📌 Future Improvements

Integrate with a real LLM API for deeper semantic analysis

Expand support for more document types (purchase orders, resumes, etc.)

Add export/download of analysis results

👨‍💻 Author
Developed for project submission by Sai Krishna Ganta.
