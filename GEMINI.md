# aeo-demo-healthcare

## Overview
A demonstration template tailored for the healthcare industry, focusing on AI Engine Optimization (AEO). It utilizes Schema.org structured data, an `llms.txt` file, and FAQ markup to ensure content is easily discoverable and interpretable by AI agents and search engines.

## Tech Stack
- **Core**: HTML5
- **SEO/AEO**: JSON-LD (Schema.org), `llms.txt`
- **Styling**: CSS3 (Responsive, Accessible)

## Architecture
- `index.html`: Main entry point containing semantic HTML and metadata.
- `llms.txt`: A text file specifically designed to help Large Language Models understand the site content.
- `faq.html` / Section: Dedicated Frequently Asked Question area for rich snippet generation.
- `js/schema.js`: Script to dynamically inject or manage structured data.

## Commands
- **Run**: Since this is a static HTML project, you can serve it using any static server.
  - Python: `python3 -m http.server`
  - Node: `npx serve .`
- **Validate**: Use Google Rich Results Test to verify Schema.org implementation.

## Coding Style
- **Semantic HTML**: Use proper tags (`<article>`, `<section>`, `<header>`) for accessibility and SEO.
- **Accessibility**: High contrast colors and ARIA labels where necessary (crucial for healthcare).
- **Clean Code**: Minimal inline JavaScript; keep logic separated.

## Important Rules
- **Mandatory Metadata**: Do not remove the `llms.txt` reference or JSON-LD scripts; they are essential for the AEO functionality.
- **Data Accuracy**: Ensure Schema.org data matches the visible content on the page.
- **No Bloat**: Keep the HTML lightweight to ensure fast loading, which is vital for mobile health searches.