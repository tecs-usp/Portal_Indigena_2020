# Portal_Indigena_2021

Projeto no qual se pretende desenvolver um portal centralizador de sites de algumas aldeias indígenas no estado de São Paulo. Posteriormente, pretende-se dar continuidade a esse portal através da confecção dos próprios sites individuais dos diferentes grupos e construção de ferramentas específicas para atender as demandas particulares das aldeias - tradutores Português-Guarani, site de vendas de mercadoria, calendário de atividades e agenda organizadora de eventos para turismo.

Num apanhado rápido das etapas inicias já planejadas até então, o portal indígena será apenas um site central expositor dos sites individuais de cada um dos grupos. Os sites de cada uma das aldeias, por sua vez, irão dispor de conteúdo escolhido pelos próprios indígenas - textos, imagens e vídeos - para apresentar um pouco da aldeia e tratar da questão da visibilidade diante do estado e da sociedade.

## Instruções

### - Sobre o Jekyll

O projeto utiliza o Jekyll para gerar o conteúdo do site. Para iniciar o servidor, entrar na pasta `Portal` e rodar o comando `bundle exec jekyll serve`. O servidor abre automaticamneente no endereço http://localhost:4000".

Instruções para instalar o Jekyll em https://jekyllrb.com/docs/

_-> Dica: rodar "bundle exec jekyll serve --livereload" para ativar o live reload do servidor._

### - Sobre a Multi-Linguagem

Para a disponibilização de múltiplas línguas no projeto, utilizamos o plugin Jekyll Multiple Languages Plugin (https://github.com/kurtsson/jekyll-multiple-languages-plugin). 

Há documentação no git fornecido, mas conceitos básicos: 
- Arquivos `.yml` de línguas dentro da pasta `_i18n`, com as diferentes traduções e suas chaves (ex: `pt.yml`, `en.yml`, `gn.yml`)
- Para incuir o texto traduzido de uma chave, utilizar a sintaxe `{% t chave %}` 
- Serão criadas pastas para as diferentes línguas, que podem ser acessadas pela url como: `www.site.com/en` ( para língua en )

### - Sobre o GitDuck

Nós utilizamos o GitDuck (https://gitduck.com) para desenvolvimento em grupo. Com essa ferramenta, é possível compartilhar uma sessão, e assim todos acessarem os mesmos arquivos e _codarem_ em conjunto. Para tal, adicionem a extensão homônima ao VSCode(ium).

### - Sobre o Prettier

Prettier se trata de um formatador de código _opinionado_. Com ele é possível padronizarmos mais facilmente o estilo do código, indentações etc., mesmo com diversas pessoas mexendo em um mesmo projeto. Para utilizá-lo, basta instalar a extensão de mesmo nome ao VSCode(ium) ( https://marketplace.visualstudio.com/items?itemName=esbenp.prettier-vscode ) e rodar o comando `npm install` na pasta do projeto - que instalará a dependência javascript do Prettier. Em caso de dúvidas com o npm consultar: https://www.npmjs.com/get-npm

### - Sobre o sass/SCSS

O sass/SCSS (https://sass-lang.com/guide) é um CSS com _superpoderes_. Adiciona-se assim várias ferramentas ao projeto, que facilitam a organização e permitem novos usos do CSS.
