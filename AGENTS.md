# Agent Instructions

## Project Description

This is a static Persian (Farsi) website analyzing the debate between traditional medicine and modern medicine in Iran. The site is built from `content.md` and `references.md` source files, with all HTML/CSS/JS contained in a single `index.html` file.

## Conventions

- Never commit, stage, reset, or discard changes unless explicitly requested. Preserve unrelated user changes.
- Markdown documents have no line-length limit.
- Markdown headings must be followed by a blank line.
- All textual files, including code and documents, must end with a newline.
- Skills are in the `.agents/skills/` folder.
- All website content will be in Persian (Farsi) language for Iranian Readers unless explicitly requested otherwise.
- HTML/CSS/JS changes should maintain RTL layout and Vazirmatn font usage
- Content updates should be made first to source `.md` files then reflected in `index.html`
- The single-file architecture (`index.html`) should be preserved unless restructuring is explicitly requested

## Project Structure

```
integrative-medicine-analysis/
├── index.html           # Website (HTML/CSS/JS)
├── content.md           # Main content
├── references.md        # Bibliography & references
├── infographic*.png     # Infographic images
├── README.md            # Project overview
├── LICENSE              # License file
```
