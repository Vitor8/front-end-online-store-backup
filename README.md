# front-end-online-store

React application that simulates an online store. The manipulation of the application's global state is done using Redux.

Link for GitHub Pages: vitor8.github.io/front-end-online-store

Step by step to install the project:

- Clone the repository: `git clone git@github.com:Vitor8/recipes-app.git`
- Enter the folder: cd front-end-online-store
- Install dependencies:
  - `npm install`
- Run the application with: `npm-start

- In the app, firstly, a request is made to the Mercado Livre API, searching for all available categories, the result is rendered on the screen.

![Captura de tela de 2021-08-25 12-16-19](https://user-images.githubusercontent.com/24492328/130817744-2e944416-d98f-4ce4-94c3-380c30c8e47a.png)

- If the user clicks on any category button, all products in that category will be rendered on the screen.

![Captura de tela de 2021-08-25 12-17-44](https://user-images.githubusercontent.com/24492328/130817990-3af8cb53-f899-4c7a-b133-aa77e22f2fbe.png)

- User can also do a search for a specific term. In the Header, there is a search bar, when the user types a term, and clicks on the search icon, a new request is made to the API, and the products found are rendered on the screen.

![Captura de tela de 2021-08-25 12-15-29](https://user-images.githubusercontent.com/24492328/130818218-a2bfd6eb-9e79-42b6-aa47-d990d13061ed.png)

- With the products rendered, the user can add that product to the cart, or click on the product card and go to a product detail page.

![Captura de tela de 2021-08-25 12-20-16](https://user-images.githubusercontent.com/24492328/130818423-94736792-2dfb-42a1-87ff-f124520c918c.png)

- In the Header, there is the option to go to the 'Cart' page, which renders all the products chosen by the user.

- On this page, the user can increase, decrease or delete the quantity of the chosen products.

![Captura de tela de 2021-08-25 12-21-42](https://user-images.githubusercontent.com/24492328/130818603-69da7a18-a759-4a75-af68-a86be609e752.png)

- To complete the purchase, the user clicks on 'Checkout', and is taken to a new page, showing the final total price.

![Captura de tela de 2021-08-25 12-22-38](https://user-images.githubusercontent.com/24492328/130818765-e49b8f12-fc6c-4b77-b611-b7ef26e2fa93.png)

Link para o GitHub Pages: Vitor8.github.io/front-end-online-store

Thanks for your interest!!
