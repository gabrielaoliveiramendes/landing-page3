# Landing Page Responsiva com CSS Grid Avançado
Este repositório contém o código de uma landing page desenvolvida com foco na utilização de propriedades avançadas do CSS Grid para a criação de layouts responsivos e flexíveis. O principal objetivo deste projeto foi o aprendizado e a demonstração das capacidades do `display: grid` e suas diversas propriedades.

## Principais Conceitos do CSS Grid Aplicados
Este projeto explora as seguintes propriedades e funcionalidades do CSS Grid:
* **`display: grid`:** Define um container como um grid container, habilitando o uso das propriedades do Grid.
* **`grid-template-columns`:** Define as colunas do grid, utilizando diferentes unidades de medida e funções como:
    * `fr` (fraction): Representa uma fração do espaço disponível no grid container.
    * `repeat()`: Permite repetir um padrão de tamanhos de coluna ou linha.
    * `auto-fit`: Ajusta o número de colunas automaticamente, preenchendo o espaço disponível sem criar colunas vazias.
    * `auto-fill`: Similar ao `auto-fit`, mas tenta criar o máximo de colunas possível, mesmo que estejam vazias.
* **`grid-template-rows`:** Define as linhas do grid, utilizando as mesmas unidades de medida e funções de `grid-template-columns`.
* **`grid-template-areas`:** Permite definir um layout visual do grid, nomeando as células do grid e referenciando esses nomes na propriedade `grid-area` dos itens do grid.
* **`row-gap` (e `column-gap`):** Define o espaçamento entre as linhas do grid.
* **`display: inline-grid`:** Cria um grid container que se comporta como um elemento inline, ocupando apenas o espaço necessário para seus conteúdos.

## Aprendizados e Observações
Durante o desenvolvimento deste projeto, foram explorados os seguintes aspectos do CSS Grid:
* A flexibilidade do `fr` para distribuição de espaço entre colunas e linhas.
* A praticidade da função `repeat()` para criar grids com um grande número de colunas ou linhas com o mesmo tamanho.
* A diferença e o uso adequado de `auto-fit` e `auto-fill` para layouts responsivos que se adaptam ao tamanho do container.
* A organização e clareza proporcionadas pelo `grid-template-areas` para layouts mais estruturados.
* A importância do `row-gap` (e suas variações) para a legibilidade e espaçamento dos elementos no grid.
* O comportamento específico do `display: inline-grid` e seus casos de uso.
