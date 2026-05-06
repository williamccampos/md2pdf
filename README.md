# md2pdf

Conversor simples de Markdown para PDF que roda inteiramente no navegador.

## Como usar

1. Clone ou baixe este repositório
2. Abra o `index.html` em qualquer navegador moderno (Chrome, Firefox, Safari, Edge)
3. Pronto — sem instalação, sem servidor, sem build

## Uso

1. **Escreva ou cole** Markdown no painel esquerdo
2. **Ou carregue um arquivo** — clique em "📂 Abrir .md" para abrir um arquivo do seu computador
3. **Preview** atualiza em tempo real no painel direito
4. **Exportar para PDF** — clique em "⬇ Salvar PDF", depois:
   - **macOS:** PDF → Salvar como PDF (canto inferior esquerdo do diálogo de impressão)
   - **Windows:** Selecione "Microsoft Print to PDF" como impressora
   - **Linux:** Selecione "Imprimir em arquivo" ou "Salvar como PDF"

## Funcionalidades

- Preview em tempo real do Markdown
- Carregamento de arquivos `.md` / `.txt` do disco
- Exportação para PDF via diálogo nativo do sistema (escolha qualquer pasta)
- Nome do PDF gerado automaticamente a partir do título do documento
- Estilo limpo com suporte a tabelas, código, listas e blockquotes
- Editor dark mode / preview light mode
- Arquivo HTML único — funciona offline após o primeiro carregamento

## Requisitos

- Qualquer navegador moderno (ES6+)
- Conexão com internet apenas no primeiro acesso (para o CDN do [marked.js](https://github.com/markedjs/marked))

> Para usar 100% offline, baixe o `marked.min.js` e referencie localmente no `index.html`.

## Licença

MIT
