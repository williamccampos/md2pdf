# md2pdf

A simple, zero-dependency Markdown to PDF converter that runs entirely in your browser.

## Getting Started

1. Clone or download this repository
2. Open `index.html` in any modern browser (Chrome, Firefox, Safari, Edge)
3. That's it — no install, no server, no build step

## Usage

1. **Write or paste** Markdown in the left panel
2. **Or load a file** — click "📂 Abrir .md" to open a `.md` file from your computer
3. **Preview** updates in real-time on the right panel
4. **Export to PDF** — click "⬇ Salvar PDF", then:
   - **macOS:** PDF → Save as PDF (bottom-left of print dialog)
   - **Windows:** Select "Microsoft Print to PDF" as printer
   - **Linux:** Select "Print to File" or "Save as PDF"

## Features

- Real-time Markdown preview
- Load `.md` / `.txt` files from disk
- Export to PDF via native system print dialog (choose any folder)
- Styled output with tables, code blocks, lists, blockquotes
- Dark editor / light preview
- Single HTML file — works offline after first load

## Requirements

- Any modern browser (ES6+)
- Internet connection on first load only (for [marked.js](https://github.com/markedjs/marked) CDN)

> To use fully offline, download `marked.min.js` and reference it locally in `index.html`.

## License

MIT
