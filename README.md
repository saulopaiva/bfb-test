# Basic Front Boilerplate (BFB)

Boilerplate básico para projetos front-end com ênfase em HTML/CSS.

## Pré-requisitos

- Node.js

## Uso

Apesar de este boilerplate contar com uma das mais atuais arquiteturas CSS possíveis atualmente -- SMACSS, BEM e Namespaces CSS --, seu uso é recomendado mais para testes e estudos.

Todos os estilos são pré-processados usando [Sass](https://sass-lang.com/). O arquivo `sass/style.scss` importa todos os demais (partials), gerando um arquivo único na raiz do projeto (`style.css`).

### Como compilar Sass (watch)

`npx node-sass-chokidar --watch ./sass -o ./`


## Licença

Este projeto usa a licença WTFPL. Consulte o arquivo [LICENSE.md](LICENSE.md) para mais detalhes.
