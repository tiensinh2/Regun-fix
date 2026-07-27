---
name: article-reader
description: Use when the user wants to read an article, analyze a research paper, review a blog post, or extract information from a written piece.
---

# Article Reader

Follow these steps to read and analyze an article or research paper.

## Step 1 — Load the article
- If a file path is given, use `read_file` to open it.
- If a URL is given, ask the user to paste the article text directly.
- If it's a PDF paper, use the `pdf-reader` skill first.

## Step 2 — Extract metadata
Identify and present:
- **Title**
- **Author(s)**
- **Publication / Journal / Source**
- **Date published**
- **Type** (research paper, news article, blog post, opinion piece)

## Step 3 — Analyze the structure and content
For a **research paper**, extract:
- **Abstract / Summary**
- **Problem statement** — what problem does it solve?
- **Methodology** — how was it done?
- **Key findings / Results**
- **Conclusions**
- **Limitations**
- **References / Citations** (notable ones)

For a **news article or blog post**, extract:
- **Main claim or thesis**
- **Supporting arguments**
- **Evidence or data cited**
- **Conclusion or call to action**

## Step 4 — Present findings
- Present extracted information in a clean structured format.
- Highlight the most important insight in one sentence at the top.

## Step 5 — Offer follow-up actions
- Summarize in 3 bullets (use `summarizer` skill)
- Create slides from this article (use `slide-creator` skill)
- Answer specific questions about the article
- Compare with another article
