# Whiteboard to PDF / Quadro para PDF

A single-page web tool that converts digital whiteboard files (`.vwb`, `.zip` or `.json`) into crisp A4 PDFs, page by page.
Everything runs in your browser — the file never leaves your computer.

Uma ferramenta web de página única que converte ficheiros de quadro digital (`.vwb`, `.zip` ou `.json`) em PDF A4 nítido, página a página.
Tudo é processado no browser — o ficheiro não sai do teu computador.

## Features / Funcionalidades

- Bilingual interface: English (default) and Português, switchable at any time
- Opens `.vwb` directly (no manual unzipping needed), plus `.zip` and `.json`
- Preview with draggable page cuts and automatic cut suggestions
- Quality options: 300 / 450 / 600 DPI
- 100% client-side, no server, no uploads

## Usage / Utilização

Open the live page (GitHub Pages) or just open `index.html` in a browser, drop your `.vwb` file, adjust the page cuts and click **Generate and download PDF**.

Requires an internet connection on first load (jsPDF and JSZip are loaded from cdnjs).

## Publish with GitHub Pages

1. Create a repository and upload `index.html` and `README.md`.
2. Go to **Settings → Pages**.
3. Under **Build and deployment**, choose **Deploy from a branch**, select `main` and `/ (root)`, then save.
4. After a minute the site is live at `https://<your-username>.github.io/<repository-name>/`.

## Libraries

- [jsPDF](https://github.com/parallax/jsPDF) (MIT)
- [JSZip](https://github.com/Stuk/jszip) (MIT / GPLv3)
