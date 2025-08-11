<<<<<<< HEAD
readme_content = """
# ADGM Corporate Agent (Colab)

An AI-powered legal assistant for reviewing and validating ADGM-compliant documents using Gemini-based RAG.

## Overview
This project processes .docx files, verifies compliance with ADGM regulations, adds comments for issues, and generates a structured JSON report. It runs in Google Colab with a Gradio interface.

## Setup Instructions
1. **Open in Colab**: Upload `ADGM_Corporate_Agent.ipynb` to Google Colab[](https://colab.research.google.com/).
2. **Install Dependencies**: Run the first cell to install required packages.
3. **Set API Key**: Enter your Google API key for Gemini when prompted (obtain from https://aistudio.google.com/).
4. **Upload Reference Documents**: Run the cell prompting for `Data Sources.pdf` and ADGM documents (PDFs/.docx) from https://www.adgm.com/documents/.
5. **Run the Application**: Execute all cells to launch the Gradio UI at the provided public URL.
6. **Upload Documents**: Use the UI to upload .docx files for analysis.

## Usage
- Access the Gradio UI via the public URL.
- Upload .docx files (e.g., `example_input.docx`).
- Download the `output_report.json` and `reviewed.docx` files.

## Data Sources
- `Data Sources.pdf`: Contains links to ADGM documents.
- Example documents: Checklists, employment contracts, resolutions (e.g., https://www.adgm.com/documents/registration-authority/registration-and-incorporation/checklist/).

## Dependencies
- python-docx==0.8.11
- docx2txt==0.8
- langchain==0.3.3
- gradio==3.50.2
- PyPDF2==3.0.1
- sentence-transformers==3.2.0
- langchain-google-genai==0.0.6
- google-generativeai==0.8.3
- langchain-community==0.3.3
- unstructured[docx]
- numpy==1.26.4

## Outputs
- `output_report.json`: Structured analysis report.
- `reviewed.docx`: Document with added compliance comments.
"""

with open("README.md", "w") as f:
    f.write(readme_content)
files.download("README.md")
=======
[![Review Assignment Due Date](https://classroom.github.com/assets/deadline-readme-button-22041afd0340ce965d47ae6ef1cefeee28c7c493a6346c4f15d667ab976d596c.svg)](https://classroom.github.com/a/vgbm4cZ0)
>>>>>>> 707a0611d0043e05a554a309617abc7b7af7612b
