# WebProject ![Logo Mercado](https://cdn-icons-png.flaticon.com/128/3081/3081559.png)

---

<p align="center">
  <img src="https://cdn-icons-png.flaticon.com/128/3081/3081559.png" width="80" alt="Logo Mercado"/>
</p>

<p align="center" style="color:#20bf6b; font-size:1.5rem; font-weight:700; font-family:Poppins,Segoe UI,Arial,sans-serif;">
  Mercado Online
</p>

<p align="center" style="color:#222f3e; font-size:1.1rem; max-width:600px;">
  Experiência de compra prática, moderna e intuitiva, focada em produtos frescos e de qualidade.<br>
  Site responsivo, elegante e com recursos visuais modernos para uma navegação agradável.
</p>

---

## Funcionalidades & Código

### Página Inicial ![Home](https://cdn-icons-png.flaticon.com/128/609/609803.png)

- **Navbar elegante:**
  ```html
  <nav class="navbar navbar-expand-lg">...</nav>
  ```
- **Carrossel de ofertas:**
  ```html
  <div id="carouselOfertas" class="carousel slide">...</div>
  ```
- **Categorias e produtos em destaque:**
  ```html
  <section class="container section-highlight" id="categorias">...</section>
  <section class="container section-highlight" id="produtos">...</section>
  ```

### Página de Apresentação ![Apresentação](https://cdn-icons-png.flaticon.com/128/3135/3135715.png)

- **Missão e diferenciais:**
  ```html
  <div class="apresentacao-hero">...</div>
  ```

### Página de Compra ![Compra](https://cdn-icons-png.flaticon.com/128/1170/1170678.png)

- **Busca dinâmica:**
  ```html
  <form class="d-flex ...">...</form>
  ```
- **Cards de produtos e modal de quantidade:**
  ```javascript
  const produtos = [ ... ];
  function renderizarProdutos(lista) { ... }
  ```
- **Carrinho e pagamento:**
  ```javascript
  const carrinho = [];
  function atualizarCarrinho() { ... }
  ```

### Página de Login ![Login](https://cdn-icons-png.flaticon.com/128/747/747545.png)

- **Formulário de autenticação:**
  ```html
  <form>...</form>
  ```
- **Validação e redirecionamento:**
  ```javascript
  document.querySelector("form").addEventListener("submit", function (e) { ... });
  ```

---

## Destaques Visuais

<p align="center">
  <img src="https://img.shields.io/badge/Google%20Fonts-Poppins-2d6cdf?style=for-the-badge&logo=googlefonts"/>
  <img src="https://img.shields.io/badge/Design-Responsivo-20bf6b?style=for-the-badge&logo=responsive-design"/>
  <img src="https://img.shields.io/badge/Bootstrap-5.3.7-f7b731?style=for-the-badge&logo=bootstrap"/>
</p>

- **Cards animados e responsivos** para produtos.
- **Barra de navegação com gradiente** e sombra.
- **Carrinho flutuante** para fácil acesso.
- **Layout adaptado** para dispositivos móveis.

---

> O projeto pode ser expandido com novas funcionalidades, integração com sistemas de pagamento e melhorias contínuas na experiência do usuário.
