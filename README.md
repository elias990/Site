# Vitrine - projeto final de HTML5 e CSS3

Site demonstrativo de compra e venda feito somente com HTML5 e CSS3, backend ou dependencias. Para abrir, carregue `html/index.html` no navegador.

## Estrutura

- `html/`: cinco paginas HTML distintas e ligadas pelo mesmo menu.
- `css/styles.css`: estilos externos, BEM, Flexbox, Grid, tema escuro e media queries.
- `images/`: ilustracoes SVG locais usadas nos anuncios.
- `screenshots/`: pasta das capturas exigidas pelo enunciado.
- `ROTEIRO-VIDEO.md`: roteiro para uma gravacao de aproximadamente 15 minutos.

## Requisitos do PDF

- **HTML semantico:** todas as paginas usam `header`, `nav`, `main`, `section` e `footer` conforme o conteudo.
- **Cinco paginas:** Inicio, Categorias, Favoritos, Chat e Minha conta estao em arquivos separados e interligados.
- **CSS externo e identidade:** as paginas carregam `css/styles.css` e compartilham a mesma identidade.
- **BEM:** exemplos de classes: `.listing-card__title`, `.listing-card__meta` e `.feature-card--theme`.
- **Flexbox:** cabecalho/menu, lista de anuncios (`.listing-grid`), hero, paineis e rodape. A lista usa `flex-wrap`.
- **Grid:** categorias, beneficios e atalhos usam `display: grid`, `grid-template-columns`, `gap`, `repeat()`, `minmax()` e areas nomeadas.
- **Responsividade:** tres blocos `@media screen` para acima de 768 px, de 481 a 768 px e ate 480 px.
- **Interacao CSS:** estados `:hover` e `:focus-visible`; o controle do tema claro/escuro usa checkbox e CSS. O tema vale enquanto a pagina esta aberta e reinicia ao navegar.
- **Organizacao:** HTML, CSS e imagens estao em pastas separadas.

## Prints de testes diferentes (Flexbox teste)

- 375
 
  <img width="375" height="810" alt="tela-375png" src="https://github.com/user-attachments/assets/b3536096-c26a-4abb-b240-819d06a020f3" />

- 768

  <img width="663" height="879" alt="tela-768png" src="https://github.com/user-attachments/assets/a90fec11-2f49-44f8-8546-de0ec14f7921" />
  
- 1366

  <img width="1309" height="734" alt="tela-1366" src="https://github.com/user-attachments/assets/c649e419-76aa-427d-b655-ff681bbf8b9f" />



## Limites da versao sem JavaScript

Busca e filtros automaticos, favoritos salvos, login, envio de chat e publicacao de anuncios precisam de JavaScript ou de um servico e nao estao ativos nesta versao. A pagina Favoritos mostra uma selecao estatica. Links e menu funcionam com HTML.

## repositorio github
 - https://github.com/elias990/site
