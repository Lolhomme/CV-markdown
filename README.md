# Markdown CV

This project is a Markdown-based CV powered by MkDocs with Material theme. It supports both French and English versions with bilingual navigation and includes a detailed skills page and a classic one-page resume.

## Project Structure

- **mkdocs.yml**: MkDocs configuration with i18n plugin for French/English support.
- **docs/**
  - **index.fr.md**: Detailed CV with skills and experience (French)
  - **index.en.md**: Detailed CV with skills and experience (English)
  - **resume.fr.md**: Classic one-page resume (French)
  - **resume.en.md**: Classic one-page resume (English)
  - **assets/custom.css**: Custom styles including two-column resume layout and print optimizations
  - **assets/print-button.js**: Print-to-PDF button for the header
- **.gitignore**: Excludes MkDocs build output (`/site`)
- **LICENSE**: MIT License

## Features

- **Bilingual Support**: Separate navigation for French and English pages via i18n plugin
- **Two Resume Formats**: 
  - Detailed version with skills cards and full professional experience
  - Classic one-page resume with two-column layout (contact + hobbies on left, name/title/sections on right)
- **Print-Optimized**: Single-page PDF export for resume, fits perfectly when printed
- **Material Theme**: Modern, responsive design with light/dark mode toggle

## Building & Deploying

### Local Development
```bash
mkdocs serve
```
Visit `http://localhost:8000`

### Build Static Site
```bash
mkdocs build
```
Output is generated to `/site` directory (gitignored).

### Deploy to GitHub Pages
Automated via GitHub Actions when pushing to main branch. The site is accessible at `https://laulom.io`.

## Recent Changes

- Added classic one-page resume pages (`resume.fr.md`, `resume.en.md`)
- Implemented i18n plugin with language-specific navigation
- Added comprehensive print CSS for single-page resume PDF export
- Updated terminology: "Prompt Engineer" → "AI Augmented Software Engineer" / "Ingénieur Logiciel Augmenté par l'IA"
- Added GraphQL to skills section
- Print button in header for easy PDF export

## License

This project is licensed under the MIT License. See the LICENSE file for more details.
