# front-end-online-store

React application that simulates an online store. The manipulation of the application's global state is done using Redux.

Link for GitHub Pages: vitor8.github.io/front-end-online-store

Step by step to install the project:

- Clone o repositório: git clone git@github.com:Vitor8/recipes-app.git
- Entre na pasta: cd front-end-online-store
- Entre em uma outra pasta: cd Portfolio
- Entre em mais uma pasta: cd front-end-online-store
- Instale as seguintes dependências:
  - npm install
- Rode a aplicação com: npm-start

- No app, primeiramente, é feito uma requisição à API do Mercado Livre, buscando todas as categorias disponíveis, o resultado é renderizado na tela.

![Captura de tela de 2021-08-25 12-16-19](https://user-images.githubusercontent.com/24492328/130817744-2e944416-d98f-4ce4-94c3-380c30c8e47a.png)

- Caso o usuário clique em algum botão de categoria, todos os produtos daquela categoria serão renderizados na tela.

![Captura de tela de 2021-08-25 12-17-44](https://user-images.githubusercontent.com/24492328/130817990-3af8cb53-f899-4c7a-b133-aa77e22f2fbe.png)

- O usuário também pode fazer uma pesquisa por um termo específico. No Header, há uma barra de pesquisa, quando o usuário digitar um termo, e clicar no ícone de pesquisa, é feita uma nova requisição à API, e o os produtos encontrados são renderizados na tela. 

![Captura de tela de 2021-08-25 12-15-29](https://user-images.githubusercontent.com/24492328/130818218-a2bfd6eb-9e79-42b6-aa47-d990d13061ed.png)

- Com os produtos renderizados, o usuário pode adicionar aquele produto ao carrinho, ou clicar no card do produto e ir para uma página de detalhes do produto.

![Captura de tela de 2021-08-25 12-20-16](https://user-images.githubusercontent.com/24492328/130818423-94736792-2dfb-42a1-87ff-f124520c918c.png)

- No Header, há a opção de ir até a paǵina 'Cart', que renderiza todos os produtos escolhidos pelo usuário.
- Nesta página, o usuário pode aumentar, diminuir ou deletar a quantidade dos produtos escolhidos.

![Captura de tela de 2021-08-25 12-21-42](https://user-images.githubusercontent.com/24492328/130818603-69da7a18-a759-4a75-af68-a86be609e752.png)

- Para finalizar a compra, o usuário clica em 'Finalizar Compra', e é levado para uma nova página, mostrando o preço total final.

![Captura de tela de 2021-08-25 12-22-38](https://user-images.githubusercontent.com/24492328/130818765-e49b8f12-fc6c-4b77-b611-b7ef26e2fa93.png)

Link para o GitHub Pages: Vitor8.github.io/front-end-online-store

Obrigado pelo interesse!!
