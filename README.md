# Markdown → PDF Template

This repository is a **GitHub template** for automatically converting
Markdown files into PDF documents using Pandoc and GitHub Actions.

## How to Use This Template

1. Click **Use this template**
2. Name your new repository
3. Edit `README.md`
4. Commit changes
5. GitHub Actions will auto-generate `README.pdf`

## Requirements (one-time)

After creating a repo from this template:

1. Go to **Settings → Actions → General**
2. Set:
   - Read and write permissions
   - Allow GitHub Actions to create and approve pull requests
3. Save

## Output

- `README.md` → canonical source
- `README.pdf` → auto-generated on each change

## Notes

- Uses Pandoc + XeLaTeX (containerized)
- No local LaTeX required
- Safe for academic and documentation projects
