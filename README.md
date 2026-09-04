# CP4 - Grid Layout & Responsividade

Projeto desenvolvido com HTML e CSS puro (sem bibliotecas ou frameworks), utilizando `display: grid` nas duas seções pedidas.

## Integrantes

- Nome: Henrique Vieira Ferreira — RM: 569586
- Nome: Leonardo Gracioli — RM: 571031

## Estrutura de pastas
```
cp4-grid/
├── index.html
├── style.css
└── README.md
```

## O que foi implementado

- **Seção 1 (hero)**: grid com `grid-template-areas` definindo as áreas `hero`, `text` e `gallery` (a galeria de 3 fotos é um sub-grid dentro da área `gallery`).
- **Seção 2 (galeria)**: grid de 5 colunas x 2 linhas usando `repeat(auto-fit, minmax(...))` + `grid-auto-flow: dense` para o efeito de blocos altos intercalados, técnica nativa de grid responsivo.
- Variáveis CSS para cores, fontes, espaçamentos e transições.
- `gap` para todo o espaçamento entre itens de grid (nenhum uso de `margin` para isso).
- Fonte Poppins via Google Fonts.
- `alt` descritivo em todas as imagens.
- Hover/transições no botão "Saiba mais" e nas imagens da galeria.
- 2 breakpoints via `@media`: mobile (abaixo de 600px, empilhado em 1 coluna) e um ajuste intermediário para tablet, mantendo o layout desktop original acima de 1024px.

## Como visualizar
Basta abrir o arquivo `index.html` em qualquer navegador.
