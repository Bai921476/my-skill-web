---
name: pptx-visual-enhancer
description: Use this skill when creating or improving PowerPoint decks that should automatically include topic-relevant images, screenshots, evidence figures, product/case visuals, or report graphics, and when decks need stronger visual hierarchy, larger fonts, better slide occupancy, cleaner card layouts, image captions, source notes, and visual QA. Trigger on requests involving PPT, pptx, slides, presentations, decks, reports, research presentations, case briefings, pitch decks, courseware, "make fonts bigger", "add related images", "make the PPT stronger", "more visual", "improve layout", or similar Chinese requests such as 自动加图, 加相关图片, 字体放大, 版面更强, 观感更大, 优化PPT, 科研汇报, 案件汇报, 课件, 路演.
---

# PPTX Visual Enhancer

## Goal

Create or improve editable PowerPoint decks so they feel presentation-ready: readable from a distance, visually grounded in the subject matter, and supported by real images or evidence-like figures when available.

## Default Workflow

1. Understand the deck purpose, audience, number of slides, and output format.
2. Build or revise the slide outline so each slide has one clear claim.
3. Gather visual assets before final layout:
   - First use user-provided files, figures, screenshots, charts, PDFs, or source documents.
   - If the topic is public and current, search the web for official or reputable images.
   - Prefer real subject images over generic stock-like decoration.
4. Design the slide around the visual asset, not as an afterthought.
5. Increase typography scale for presentation readability.
6. QA the result for text overflow, overlap, source labels, and image fit.

## When To Search For Images

Search or extract images when the deck is about:

- A legal case, dispute, public event, product, company, venue, person, artwork, technical system, medical topic, report, dataset, or research paper.
- A user asks for a stronger deck, more polished slides, better visual proportion, bigger fonts, or less text-heavy layout.
- A slide discusses facts, evidence, process, timeline, comparison, product function, visual examples, or real-world context.

Prefer sources in this order:

1. User-provided source files and images.
2. Official pages, court or agency pages, company pages, paper figures, report graphics, and product screenshots.
3. Reputable media images and screenshots for public events or legal cases.
4. Generated or illustrative images only when real images are unavailable, inappropriate, or explicitly requested.

## Image Use Rules

- Use images on selected high-impact slides, not necessarily every slide.
- Good image targets: cover, background/context, technical workflow, evidence/facts, timeline, comparison, case study, conclusion.
- Keep images large enough to inspect. Tiny decorative thumbnails are usually not worth adding.
- Frame evidence-like screenshots in simple figure cards with concise captions.
- Add short source notes such as "Source: official report", "Public reporting screenshot", "User-provided screenshot", or "Illustrative diagram".
- For suspected infringement, disputes, crime, medical, or other sensitive material, label image status precisely. Do not overstate that a public screenshot is court-admitted evidence unless the source says so.
- Avoid dark, cropped, blurred, atmospheric, or generic images when the user needs to inspect the actual subject.

## Layout Patterns

Use these patterns when adding images to existing slides:

- **Two-column evidence slide**: large image left, key interpretation card right.
- **Workflow slide**: process cards on top, screenshot or figure strip below.
- **Timeline slide**: timeline across the top, real-world image and summary card below.
- **Comparison slide**: table or matrix plus one small source image only if it helps explain the comparison.
- **Cover slide**: use one strong subject image if it does not compete with the title.

When improving an existing deck:

- Remove low-value bullets before shrinking image size.
- Move explanatory text into one companion card next to the image.
- Keep 0.3-0.5 inch gaps between image, cards, and footer.
- Keep source labels small but readable and out of the main content flow.

## Typography Scale

Default to larger, presentation-friendly fonts.

Recommended sizes:

| Element | Size |
|---------|------|
| Cover title | 40-52pt |
| Slide title | 30-38pt |
| Section label / card title | 18-24pt |
| Body text | 15-18pt |
| Table text | 11-14pt |
| Captions / source notes | 8.5-11pt |

When a user asks for larger fonts, stronger layout, or better visual proportion:

- Increase all text sizes by roughly 12-18% as a first pass.
- Give body text under 14pt a larger boost.
- Keep footers and source notes smaller than body text but still readable.
- If text overflows after scaling, cut or consolidate wording rather than shrinking everything back down.
- When practical, compare average font size before and after; a meaningful deck-wide change is often +1.5pt to +3pt.

## Tables And Cards

- Use dark table headers with white header text.
- Use alternating row backgrounds for readability.
- Avoid tables with tiny text; simplify rows or split across slides if needed.
- Use card layouts for modules, but do not nest cards inside cards.
- Make card titles visibly larger than body text.

## QA Checklist

Before final delivery:

- Confirm the output remains editable `.pptx`.
- Confirm slide count and page order.
- Confirm images are embedded, not merely linked.
- Confirm key image slides have captions or source notes.
- Confirm the deck contains no leftover placeholders.
- Check for text overflow, image/text overlap, low contrast, tiny captions, cramped tables, and footer collisions.
- If rendering tools are available, export slides to images and visually inspect at least the edited slides.

