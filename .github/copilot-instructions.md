# aeo-demo-healthcare

## Project
AEO (AI Engine Optimization) demo template for healthcare industry using HTML with Schema.org structured data, llms.txt generation, and AI-friendly markup.

## Conventions
- Use semantic HTML5 elements (article, section, header, footer, nav)
- Include Schema.org JSON-LD structured data for healthcare entities
- Add llms.txt for AI crawler accessibility
- Use FAQ schema (FAQPage) for common healthcare questions
- Keep all markup inline or in minimal external files
- Prefer native HTML elements over custom components

## Naming
- Use kebab-case for HTML filenames (e.g., `healthcare-services.html`)
- Use descriptive, SEO-friendly filenames
- Name Schema.org entity files with -schema suffix

## Architecture
- Single HTML files per page with embedded or inline JSON-LD
- Separate files for different Schema.org types (MedicalOrganization, FAQPage)
- llms.txt at root for AI crawler discovery
- No build system required—pure static HTML

## Commands
- No build commands needed—edit HTML files directly
- Validate structured data with Google Rich Results Test
- Test AI accessibility with llms.txt validator

## Do Not
- Do not use client-side JavaScript for core content rendering
- Do not hide content from AI crawlers (no cloaking)
- Do not use dynamic or server-side rendering for this template
- Do not omit structured data from healthcare entity pages