# Dicionário CSS

CSS sempre foi de grande dificuldade para mim, então reuni diversos exemplos visuais dos componentes e propriedades mais comuns em uma única página. A ideia é ver o componente funcionando, achar a classe no `style.css` e copiar o código para outros projetos.

## Como usar

1. Baixe ou clone o repositório.
2. Abra o `index.html` no navegador.
3. Veja o exemplo, leia o nome da classe indicada no cabeçalho de cada cartão e procure por ela no `style.css`.
4. Copie o bloco da seção correspondente (junto com as variáveis de cor da seção 0 e o `@keyframes`, quando houver).

Não precisa instalar nada. A página usa só HTML e CSS, sem JavaScript.

## O que tem aqui

| Nº | Seção |
|----|-------|
| 1 | Caixas (borda, sombra, efeito vidro, círculo) |
| 2 | Botões (variações e hover) |
| 3 | Gradientes (linear, radial, cônico, texto) |
| 4 | Layout (flexbox e grid) |
| 5 | Cards e badges |
| 6 | Cabeçalho |
| 7 | Barra lateral |
| 8 | Rodapé |
| 9 | Carrossel (automático e arrastável) |
| 10 | Animações (`@keyframes`) |
| 11 | Formulário |
| 12 | Tipografia |
| 13 | Alertas e barra de progresso |
| 14 | Interruptor (toggle) |
| 15 | Acordeão |
| 16 | Tooltip |
| 17 | Modal |
| 18 | Menu hambúrguer |
| 19 | Tabela |
| 20 | Posicionamento (cantos, centro, `z-index`, `sticky`, `fixed`) |
| 21 | Hero |
| 22 | Efeitos (zoom, esqueleto de carregamento, neon) |
| 23 | Imagens: tamanho e ajuste (`object-fit`, `aspect-ratio`) |
| 24 | Imagens: posição e recortes (`object-position`, `clip-path`) |
| 25 | Imagem como fundo (`background-*`, parallax) |
| 26 | Imagens: filtros e efeitos |

## Estrutura

    ├── index.html   # página com os exemplos
    ├── style.css    # todo o CSS, organizado por seção numerada
    └── dogs.jpg     # imagem usada nos exemplos das seções 23 a 26

## Observações

- O `style.css` tem uma parte chamada "DOC" que serve só para montar a página de exemplos. Ao copiar para outro projeto, ignore essa parte.
- No exemplo de `position: fixed` (seção 20i), o pai usa `transform` apenas para a demonstração caber na caixa. Em um projeto real, não use esse `transform`.
- Os exemplos respeitam `prefers-reduced-motion`: quem desativa animações no sistema não as vê.

## Objetivo

Este repositório é um material de estudo e consulta pessoal. 
