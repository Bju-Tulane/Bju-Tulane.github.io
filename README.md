# Bangyan Ju — Academic Website

Personal academic website of **Bangyan Ju**, Ph.D. student in Computer Science at Tulane University.
Built with the [al-folio](https://github.com/alshedivat/al-folio) Jekyll theme and hosted on GitHub Pages.

## Pages

| Page | File | Content |
| --- | --- | --- |
| About (landing) | `_pages/about.md` | Bio, headshot, office address, email, news, selected publications, social links |
| Research | `_pages/research.md` | Research overview and the four main projects |
| Publications | `_pages/publications.md` + `_bibliography/papers.bib` | Publication list generated from BibTeX |

## Deploy

1. Create a public GitHub repository named **`Bju-Tulane.github.io`**.
2. Push this folder to its `main` branch.
3. In **Settings → Actions → General → Workflow permissions**, choose **Read and write permissions**.
4. Wait for the **Deploy site** action to finish (it creates a `gh-pages` branch).
5. In **Settings → Pages**, set **Source = Deploy from a branch**, **Branch = `gh-pages` / (root)**.
6. Visit `https://bju-tulane.github.io`.

## Updating content

- **News:** add a file to `_news/` (copy an existing one and change the date and text).
- **Publications:** add a BibTeX entry to `_bibliography/papers.bib`; `selected = {true}` shows it on the landing page; `pdf = {file.pdf}` links a PDF placed in `assets/pdf/`.
- **Photo:** replace `assets/img/prof_pic.jpg`.

Theme license: MIT (see `LICENSE`).
