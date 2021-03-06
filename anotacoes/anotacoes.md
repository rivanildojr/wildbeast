# Grid Layout

## Grid Container

### Display

    - Define o elemento como um grid container;
    - Suporta tais valores: grid, inline-grid, subgrid.

### Grid-template-columns

    - Define o número total de colunas a serem criadas no grid;
    - Aceita quais unidades css e a unidade 1fr(fração do elemento), além de funções como o "repeat", "minmax".

### Grid-template-rows

    - Define a quantidade de linhas a serem criadas no grid;
    - Aceita quais unidades css e a unidade 1fr(fração do elemento), além de funções como o "repeat", "minmax".

### Grid-template-areas

    - Define áreas específicas no grid;
    - As linhas são criadas entres aspas e as colunas por strings separadas por espaços;
    - O ponto (.), pode ser utilizado para criar áreas vazias.
    - Trabalha junto com a a propriedade "grid-area"

### Grid-template

    - Atalho para as propriedades grid-template-areas, grid-template-rows e grid-template-columns.

### Gap

    - Define o espaçamento interno entre os elementos da grid
    - Caso seja passado dois valores, o primeiro será para as colunas e o segunda para as linhas;
    - Existem também as propriedades column-gap (define o gap para a coluna) e o row-gap (define o gap para as linhas).

### Grid-auto-columns

    - Define o tamanho das colunas do grid geradas automaticamente.

### Grid-auto-rows

    - Define o tamanho das linhas do grid geradas automaticamente.

### Grid-auto-flow

    - Define o fluxo dos itens no grid;
    - Gerados em linhas, colunas ou dense (coloca em qualquer lugar que tenha espaço para o item da grid).

### Grid

    - Atalho geral para as propriedades: grid-template-rows, grid-template-columns, grid-template-areas, grid-auto-rows, grid-auto-columns e grid-auto-flow.

### Justify-content

    - Controla o alinhamento dos elementos grid no eixo horizontal (start, end, stretch, center, space-around, space-between, space-evenly);
    - O padrão é os elementos ficaram esticados (stretch).

### Align-content

    - Controla o alinhamento dos elementos grid no eixo vertical (start, end, stretch, center, space-around, space-between, space-evenly);
    - O padrão é os elementos ficaram esticados (stretch).

### Justify-items

    - Controla o alinhamento dos elementos grid no eixo horizontal, com relação a célula. (start, end, stretch, center);
    - O padrão é os elementos ficaram esticados (stretch).

### Align-items

    - Controla o alinhamento dos elementos grid no eixo vertical, com relação a célula. (start, end, stretch, center);
    - O padrão é os elementos ficaram esticados (stretch).

## Grid Item

### grid-column

    - Define quais colunas o grid item irá ocupar;
    - Pode-se definir apenas a coluna inicial e a final, caso receba o valor "-1", o item irá ocupar todas as colunas;
    - Pode receper o valor "span" junto um quatidade, para o grid item ocupar a quantidade de colunas passada a partir de onde ele estiver;
    - Também possui as propriedades: grid-column-start e grid-column-end.

### grid-row

    - Define quais linhas o grid item irá ocupar;
    - Pode-se definir apenas a linha inicial e a final, caso receba o valor "-1", o item irá ocupar todas as linhas;
    - Pode receper o valor "span" junto um quatidade, para o grid item ocupar a quantidade de linhas passada a partir de onde ele estiver;
    - Também possui as propriedades: grid-row-start e grid-row-end.

### grid-area

    - Define a área do grid item irá ocupar;
    - Atalho para as propriedades: grid-row-start, grid-column-start, grid-row-end e grid-row-start;
    - Pode-se utilizar o z-index para controlar o eixo z do grid item.

### justify-self

    - Controla o alinhamento do elemento específico do grid no eixo horizontal, com relação a célula. (start, end, stretch, center);
    - O padrão é os elementos ficaram esticados (stretch).

### align-self

    - Controla o alinhamento do elemento específico do grid no eixo vertical, com relação a célula. (start, end, stretch, center);
    - O padrão é os elementos ficaram esticados (stretch).

### place-self

    - Atalho para as propriedades: align-self e justify-self.

## Materiais de Apoio

  - [CSS Tricks](https://css-tricks.com/snippets/css/complete-guide-grid/)
  - [Grid Grid - MDN](https://developer.mozilla.org/pt-BR/docs/Web/CSS/CSS_Grid_Layout)
  - [CSS Grid guia completo - Origamid](https://www.origamid.com/projetos/css-grid-layout-guia-completo/)
  - [Grid by Example](https://gridbyexample.com/examples/)
  - [CSS Grid Rocketseat - Vídeo](https://www.youtube.com/watch?v=HN1UjzRSdBk&t=)
  - [CSS Grid Layout e Flexbox (Origamid) - Vídeo](https://www.youtube.com/watch?v=x-4z_u8LcGc)
  - [Grid Garden - Jogo](https://cssgridgarden.com/)
