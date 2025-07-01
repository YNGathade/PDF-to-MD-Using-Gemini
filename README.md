# PDF to Markdown Using Gemini
A Python-based tool that converts PDF files into clean and readable Markdown format using Google’s Gemini AI (Pro/Flash models). This tool allows users to interactively select PDFs, extract their content, and output well-structured `.md` files — perfect for documentation or publishing workflows.
# Features
-  Convert PDF text into Markdown format automatically  
-  Uses Google Gemini (Pro/Flash) to reformat and structure content  
-  Interactive CLI to select PDF files for conversion  
-  Automatically creates output folder for markdown files  
-  Lightweight and easy to run locally  
#  Technologies Used
**Python 3.10+**
**Google Gemini API (Pro / Flash)**
**PyMuPDF (`fitz`)** – for extracting text from PDFs  
**InquirerPy / Inquirer** – for interactive CLI selection  
**Markdown** – as the final export format  
**VS Code** – for development  
**Git & GitHub** – for version control and collaboration
# Installation
1. **Clone this repository**
   ```bash
   git clone https://github.com/your-username/pdf-to-md-gemini.git
   cd pdf-to-md-gemini
**Create and activate a virtual environment**
python -m venv .venv
.venv\Scripts\activate    # On Windows
source .venv/bin/activate # On macOS/Linux
**Set up Google Gemini API key**
Get API key from Google AI Studio
Create a .env file in the root director
GOOGLE_API_KEY=your_api_key_here


