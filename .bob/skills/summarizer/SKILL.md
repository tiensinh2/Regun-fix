---
name: summarizer
description: Use when the user wants to summarize content, get a summary of a file, article, PDF, code, or any text, or asks for a TL;DR.
---

# Summarizer

Follow these steps to produce a clear, concise summary of any content.

## Step 1 — Identify the content to summarize
- If a file path is provided, use `read_file` to load it.
- If it's a PDF, use `read_file` (Bob reads PDFs natively).
- If the user pastes text directly, use that.
- If unclear, ask: "What would you like me to summarize?"

## Step 2 — Determine summary style
Choose based on context (or ask the user):
- **Brief** — 2–3 sentences, highest-level only
- **Bullet points** — 5–7 key takeaways
- **Structured** — sections with headings mirroring the source
- **Executive** — 1 paragraph, business-focused, no jargon
- **Technical** — preserves technical detail, audience is experts

Default to **bullet points** if not specified.

## Step 3 — Generate the summary
- Lead with a **one-sentence overview** of what the content is about.
- Follow with the chosen summary style.
- Keep language clear and direct — no filler phrases.
- Preserve important numbers, names, and findings exactly as stated.
- Do not add opinions or information not in the source.

### Example output format (bullet style):
```
**Overview:** [One sentence describing the content]

**Key Points:**
- [Point 1]
- [Point 2]
- [Point 3]
- [Point 4]
- [Point 5]

**Conclusion:** [One sentence on the main takeaway]
```

## Step 4 — Offer follow-up actions
- Make it shorter or longer
- Change the format (executive, technical, bullets)
- Create slides from this summary (use `slide-creator` skill)
- Answer questions about the original content
