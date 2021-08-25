# front-end-online-store
Aplicação React que simula uma loja online. A manipulação do estado global da aplicação é feita usando Redux.

Passo a Passo para a instalção do projeto:

- Fork o repositório
- Clone o repositório: git clone git@github.com:Vitor8/recipes-app.git
- Entre na pasta: cd front-end-online-store
- Entre em uma outra pasta: cd Portfolio
- Entre em mais uma pasta: cd front-end-online-store
- Instale as seguintes dependências:
  - npm install
- Rode a aplicação com: npm-start

- No app, primeiramente, é feito uma requisição à API do Mercado Livre, buscando todas as categorias disponíveis, o resultado é renderizado na tela.
- Caso o usuário clique em algum botão de categoria, todos os produtos daquela categoria serão renderizados na tela.
- O usuário também pode fazer uma pesquisa por um termo específico. No Header, há uma barra de pesquisa, quando o usuário digitar um termo, e clicar no
  ícone de pesquisa, é feita uma nova requisição à API, e o os produtos encontrados são renderizados na tela. 
- Com os produtos renderizados, o usuário pode adicionar aquele produto ao carrinho, ou clicar no card do produto e ir para uma página de detalhes do produto.
- No Header, há a opção de ir até a paǵina 'Cart', que renderiza todos os produtos escolhidos pelo usuário. 
- Nesta página, o usuário pode aumentar, diminuir ou deletar a quantidade dos produtos escolhidos.
- Para finalizar a compra, o usuário clica em 'Finalizar Compra', e é levado para uma nova página, mostrando o preço total final.

Link para o GitHub Pages: Vitor8.github.io/front-end-online-store

Obrigado pelo interesse!!
