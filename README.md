# Evolução dos Layouts Web - Das Tabelas ao Grid CSS

## Sobre mim

30 anos e 8 anos de experiência como fullstack em desenvolvimento web. Atualmente trabalhando na Escola Senai de Informática como frontend, sou professora da {reprograma} e casada com um programador. Amo codar, ler, Christina Aguilera e jogar Overwatch.

## Tópicos
- Na pré-história - TABELAS
- O alvorecer da civilização - TABLELESS
- A revolução industrial - Grid Systems e Bootstrap
- A era pré-moderna - Flexbox
- O presente e futuro  - CSS Grid
  
### Grid CSS - Conceitos

- display : grid | inline-grid
- grid track : grid-template-columns e grid-template-rows
- tamanho usando fr (fração)  
- grid-template-areas : Constrói o template do grid usando o nome das areas
  
        .item-a {
            grid-area: header;
        }
        .item-b {
            grid-area: main;
        }
        .item-c {
            grid-area: sidebar;
        }
        .item-d {
            grid-area: footer;
        }

        .container {
            grid-template-columns: 50px 50px 50px 50px;
            grid-template-rows: auto;
            grid-template-areas: 
                "header header header header"
                "main main ` sidebar"
                "footer footer footer footer";
        }

### Hands on

## Referencias

- https://en.wikipedia.org/wiki/Web_design#1988–2001
- https://www.codigofonte.com.br/codigos/estrutura-de-uma-pagina-para-sites-em-tabelas
- https://tableless.com.br/introducao-sobre-media-queries/
- https://getbootstrap.com/docs/4.1/layout/grid/
- https://getbootstrap.com/docs/3.3/css/#grid
- https://960.gs
- https://css-tricks.com/snippets/css/a-guide-to-flexbox/
- https://www.youtube.com/watch?v=7kVeCqQCxlk
- https://caniuse.com/#feat=css-grid
- https://gridbyexample.com

## Slides

[Apresentação](https://docs.google.com/presentation/d/1_U1YlfWCLgmcg6pBinm-Lq6AjpDY9473wDJ1RrPW3ok/edit?usp=sharing)
