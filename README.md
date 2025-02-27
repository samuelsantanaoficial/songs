# songs

## Songbooks

Songbooks LaTex `pdflatex` usando o pacote `songs`.
- Book **A5** `\documentclass[10pt,a5paper]{book}`
- Duas páginas para cada música
- Cabeçalho e rodapé com **fancyhdr** `\usepackage{fancyhdr}`

## Atualizar o Sumário (index)

- Para criar o índice vc tem que primeiro gerar um pdf depois executar o script lua pelo terminal:

```bash
texlua songidx.lua index.sxd index.sbx
```
ou chamar o script `index.sh`:

```bash
./index.sh
```
- ele cria dois arquivos: `index.sxd` e `index.sbx` contendo as informações para o índice

- quando criar o pdf novamente vai carregar o índice/sumário corretamente

> obs: todos os arquivos devem está na mesma pasta, e abrir o terminal dentro desta mesma pasta.
