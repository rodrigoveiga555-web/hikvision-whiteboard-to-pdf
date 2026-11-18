# Whiteboard to PDF / Quadro para PDF

A single-page web tool made to convert **Hikvision digital whiteboard** files (`.vwb`, `.zip` or `.json`) into crisp A4 PDFs, page by page.

These files don't contain a picture of the board. They store the **mathematical coordinates of every point the pen passed through** on the whiteboard (plus colour, pen width and pen type). This tool reads those coordinates and redraws each stroke as smooth curves at high resolution, so the PDF stays sharp at any zoom level.

Everything runs in your browser — the file never leaves your computer.

> This is an independent project and is not affiliated with or endorsed by Hikvision.

---

Uma ferramenta web de página única, feita para converter ficheiros do **quadro digital Hikvision** (`.vwb`, `.zip` ou `.json`) em PDF A4 nítido, página a página.

Estes ficheiros não guardam uma imagem do quadro. Guardam as **coordenadas matemáticas de todos os pontos por onde a caneta passou** no quadro (além da cor, da espessura e do tipo de caneta). Esta ferramenta lê essas coordenadas e volta a desenhar cada traço em curvas suaves e em alta resolução, por isso o PDF fica nítido mesmo com muito zoom.

Tudo é processado no browser — o ficheiro não sai do teu computador.

> Este é um projeto independente, sem qualquer ligação à Hikvision.

## Features / Funcionalidades

- Bilingual interface: English (default) and Português, switchable at any time
- Opens `.vwb` directly (no manual unzipping needed), plus `.zip` and `.json`
- Preview with draggable page cuts and automatic cut suggestions
- Quality options: 300 / 450 / 600 DPI
- 100% client-side, no server, no uploads

## Usage / Utilização

Open the live page (GitHub Pages) or just open `index.html` in a browser, drop your `.vwb` file, adjust the page cuts and click **Generate and download PDF**.

Requires an internet connection on first load (jsPDF and JSZip are loaded from cdnjs).

## Libraries

- [jsPDF](https://github.com/parallax/jsPDF) (MIT)
- [JSZip](https://github.com/Stuk/jszip) (MIT / GPLv3)
