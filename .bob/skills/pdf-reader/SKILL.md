---
name: pdf-reader
description: Use when the user wants to read a PDF file, extract text from a PDF, analyze a PDF document, or get information from a PDF.
---

# PDF Reader

Follow these steps to read and extract content from a PDF file.

## Step 1 — Identify the PDF file
- Ask the user for the PDF file path if not already provided.
- Use `read_file` to open the PDF — Bob can read PDF files directly.

## Step 2 — Extract and structure the content
- Read the full PDF using `read_file`.
- Identify and extract:
  - **Title** and **author(s)** if present
  - **Section headings** and structure
  - **Key content** from each section
  - **Tables, figures, or data** mentioned
  - **References or citations** if academic

## Step 3 — Present the extracted content
- Present the content in a clean, structured format.
- Use headings that mirror the document's own structure.
- If the document is long, provide a high-level outline first, then detail on request.

## Step 4 — Offer follow-up actions
After extracting, offer the user these options:
- Summarize the PDF (use the `summarizer` skill)
- Answer specific questions about the content
- Extract only a specific section or page range
- Create slides from the content (use the `slide-creator` skill)
