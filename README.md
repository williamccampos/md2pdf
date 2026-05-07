# MD → PDF

<p align="center">
  <img src="logo.svg" width="80" alt="MD→PDF Logo">
</p>

Conversor de Markdown para PDF direto no navegador. Sem servidor, sem upload — tudo roda localmente.

## Features

- ✍️ Editor Markdown com preview em tempo real
- 📑 Múltiplas abas — abra até 20 arquivos simultaneamente
- ⬇️ Export direto para PDF (download automático, sem tela de impressão)
- 📦 "Todos em PDF" — gera um PDF separado para cada aba
- 🎨 UI estilo iOS 26 glass
- 🔒 100% client-side — nenhum dado sai do seu navegador

## Como usar

1. Abra `index.html` no navegador
2. Cole/digite Markdown ou clique em **📂 Abrir** para carregar arquivos `.md`
3. Clique em **⬇ PDF** para exportar a aba ativa ou **⬇ Todos em PDF** para exportar todos

## Stack

- HTML/CSS/JS puro (zero build)
- [marked.js](https://github.com/markedjs/marked) — parser Markdown
- [html2pdf.js](https://github.com/eKoopmans/html2pdf.js) — geração de PDF client-side

## Limites

| Plano | Arquivos simultâneos |
|-------|---------------------|
| Free  | 20                  |

## License

MIT
