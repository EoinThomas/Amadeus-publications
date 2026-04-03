# Publication Subpages

This directory contains individual pages for each publication with detailed information including abstracts.

## Creating a New Publication Page

1. **Create a new markdown file** with a URL-friendly filename (e.g., `my-paper-title.md`)
   - Use lowercase letters
   - Replace spaces with hyphens
   - Avoid special characters

2. **Use the TEMPLATE.md** as a starting point
   - Copy `TEMPLATE.md` to your new filename
   - Fill in all the sections with your publication details

3. **Update the main readme.md** to link to your new page
   - Wrap the publication title in the table with a link: `[Title](publications/your-filename.html)`
   - Note: Use `.html` in the link, not `.md` (GitHub Pages will convert it automatically)

## File Naming Convention

Examples:
- "Writing Style Matters: An Examination..." → `writing-style-matters.md`
- "PCMC-Net: Feature-Based Pairwise..." → `pcmc-net.md`
- "Unconditionally Calibrated Priors..." → `unconditionally-calibrated-priors.md`

## Front Matter

Each file must include YAML front matter at the top:

```yaml
---
layout: default
title: "Your Publication Title"
year: 2025
---
```

This ensures proper formatting when GitHub Pages renders the page.

## Sections to Include

1. **Title** (H1 heading)
2. **Back link** to main publications page
3. **Publication Details** (authors, venue, year, external link)
4. **Abstract** (the full abstract from the paper)
5. **Key Contributions** (optional but recommended)
6. **Citation** (BibTeX format)
7. **Back link** at the bottom

## Example Files

See these example publications for reference:
- `writing-style-matters.md`
- `unconditionally-calibrated-priors.md`
- `pcmc-net.md`
