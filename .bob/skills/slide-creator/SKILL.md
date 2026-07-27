---
name: slide-creator
description: Use when the user wants to create slides, make a presentation, build a slideshow, or convert content into presentation format.
---

# Slide Creator

Follow these steps to create structured slide content from any input.

## Step 1 — Understand the input and goal
- Identify the source material (PDF, article, text, code, topic).
- Ask the user if not clear:
  - How many slides? (default: 8–12)
  - Target audience? (technical, general, executives)
  - Presentation style? (overview, deep-dive, pitch)

## Step 2 — Plan the slide structure
Build a logical outline:
1. **Title slide** — title, subtitle, presenter name
2. **Agenda / Overview** — list of main topics
3. **Content slides** — one key idea per slide
4. **Data / Evidence slides** — stats, figures, comparisons if relevant
5. **Conclusion slide** — key takeaways
6. **Q&A / Thank you slide**

## Step 3 — Generate each slide
For each slide, output:
```
## Slide N: [Title]
**Key message:** one sentence summary

- Bullet point 1
- Bullet point 2
- Bullet point 3

[Speaker notes: what to say aloud for this slide]
```

## Step 4 — Review and refine
- Present all slides in order.
- Ask the user if they want to adjust any slide — add, remove, rewrite, or reorder.
- Offer to export as Markdown, or suggest copy-pasting into PowerPoint / Google Slides.
