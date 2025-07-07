# Mercado Online

![Logo Mercado](https://cdn-icons-png.flaticon.com/128/3081/3081559.png)

![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=fff)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=fff)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=222)
![Bootstrap](https://img.shields.io/badge/Bootstrap-5.3.7-7952B3?style=for-the-badge&logo=bootstrap&logoColor=fff)

Experiência de compra prática, moderna e intuitiva, focada em produtos frescos e de qualidade.

**Site responsivo**, elegante e com recursos visuais modernos para uma navegação agradável.

![Google Fonts](https://img.shields.io/badge/Google%20Fonts-Poppins-2d6cdf?style=for-the-badge&logo=googlefonts)
![Design Responsivo](https://img.shields.io/badge/Design-Responsivo-20bf6b?style=for-the-badge&logo=responsive-design)
![Bootstrap](https://img.shields.io/badge/Bootstrap-5.3.7-f7b731?style=for-the-badge&logo=bootstrap)

---

## ✨ Funcionalidades do Projeto

O Mercado Online é um site moderno para compras de produtos frescos, com navegação intuitiva e visual elegante. Abaixo, cada funcionalidade principal é apresentada com uma breve explicação e o código completo relacionado.

### 🏠 Página Inicial

A página inicial apresenta uma navegação clara, ofertas em destaque e categorias de produtos para facilitar a experiência do usuário.

- **Navbar elegante:**
  Utiliza o Bootstrap para criar uma barra de navegação responsiva e estilizada.

  ```html
  <nav class="navbar navbar-expand-lg navbar-light bg-light shadow-sm">
    <div class="container">
      <a class="navbar-brand" href="#">Mercado Online</a>
      <button
        class="navbar-toggler"
        type="button"
        data-bs-toggle="collapse"
        data-bs-target="#navbarNav"
        aria-controls="navbarNav"
        aria-expanded="false"
        aria-label="Toggle navigation"
      >
        <span class="navbar-toggler-icon"></span>
      </button>
      <div class="collapse navbar-collapse" id="navbarNav">
        <ul class="navbar-nav ms-auto">
          <li class="nav-item">
            <a class="nav-link" href="index.html">Início</a>
          </li>
          <li class="nav-item">
            <a class="nav-link" href="apresentacao.html">Sobre</a>
          </li>
          <li class="nav-item">
            <a class="nav-link" href="compra.html">Comprar</a>
          </li>
          <li class="nav-item">
            <a class="nav-link" href="login.html">Login</a>
          </li>
        </ul>
      </div>
    </div>
  </nav>
  ```

- **Carrossel de ofertas:**
  Exibe promoções e produtos em destaque de forma dinâmica.

  ```html
  <div id="carouselOfertas" class="carousel slide" data-bs-ride="carousel">
    <div class="carousel-inner">
      <div class="carousel-item active">
        <img
          src="img/tomate img.jpg"
          class="d-block w-100"
          alt="Tomate Fresco"
        />
        <div class="carousel-caption d-none d-md-block">
          <h5>Tomate Fresco</h5>
          <p>Oferta especial da semana!</p>
        </div>
      </div>
      <div class="carousel-item">
        <img src="img/pimentão img.png" class="d-block w-100" alt="Pimentão" />
        <div class="carousel-caption d-none d-md-block">
          <h5>Pimentão</h5>
          <p>Direto do produtor para sua mesa.</p>
        </div>
      </div>
      <div class="carousel-item">
        <img src="img/Rabanete img.jpg" class="d-block w-100" alt="Rabanete" />
        <div class="carousel-caption d-none d-md-block">
          <h5>Rabanete</h5>
          <p>Frescor e qualidade garantidos.</p>
        </div>
      </div>
    </div>
    <button
      class="carousel-control-prev"
      type="button"
      data-bs-target="#carouselOfertas"
      data-bs-slide="prev"
    >
      <span class="carousel-control-prev-icon" aria-hidden="true"></span>
      <span class="visually-hidden">Anterior</span>
    </button>
    <button
      class="carousel-control-next"
      type="button"
      data-bs-target="#carouselOfertas"
      data-bs-slide="next"
    >
      <span class="carousel-control-next-icon" aria-hidden="true"></span>
      <span class="visually-hidden">Próximo</span>
    </button>
  </div>
  ```

- **Categorias e produtos em destaque:**
  Seções separadas para categorias e produtos populares.

  ```html
  <section class="container section-highlight" id="categorias">
    <h2>Categorias</h2>
    <div class="row">
      <div class="col"><div class="card">Frutas</div></div>
      <div class="col"><div class="card">Verduras</div></div>
      <div class="col"><div class="card">Legumes</div></div>
    </div>
  </section>
  <section class="container section-highlight" id="produtos">
    <h2>Produtos em Destaque</h2>
    <div class="row">
      <div class="col"><div class="card">Tomate</div></div>
      <div class="col"><div class="card">Pimentão</div></div>
      <div class="col"><div class="card">Rabanete</div></div>
    </div>
  </section>
  ```

### 🧑‍💼 Página de Apresentação

Apresenta a missão, valores e diferenciais do mercado, reforçando a proposta de valor ao cliente.

- **Missão e diferenciais:**
  Estrutura visual para destacar os pontos fortes do negócio.

  ```html
  <div class="apresentacao-hero">
    <h1>Nossa Missão</h1>
    <p>
      Oferecer produtos frescos, saudáveis e de qualidade, com atendimento ágil
      e personalizado.
    </p>
    <ul>
      <li>Entrega rápida</li>
      <li>Produtos selecionados</li>
      <li>Atendimento humanizado</li>
    </ul>
  </div>
  ```

### 🛒 Página de Compra

Permite ao usuário buscar produtos, adicionar ao carrinho e simular uma compra de forma prática.

- **Busca dinâmica:**
  Campo de busca que filtra produtos em tempo real.

  ```html
  <form class="d-flex mb-4" id="form-busca">
    <input
      class="form-control me-2"
      type="search"
      placeholder="Buscar produtos..."
      aria-label="Buscar"
      id="input-busca"
    />
    <button class="btn btn-success" type="submit">Buscar</button>
  </form>
  ```

- **Cards de produtos e modal de quantidade:**
  Produtos são exibidos em cards interativos, com opção de escolher quantidade.

  ```html
  <div class="row" id="produtos-lista">
    <!-- Os cards são renderizados dinamicamente pelo JS -->
  </div>
  ```

  ```javascript
  // scripts.js
  const produtos = [
    { nome: "Tomate", preco: 4.99, imagem: "img/tomate img.jpg" },
    { nome: "Pimentão", preco: 5.99, imagem: "img/pimentão img.png" },
    { nome: "Rabanete", preco: 3.99, imagem: "img/Rabanete img.jpg" },
  ];

  function renderizarProdutos(lista) {
    const container = document.getElementById("produtos-lista");
    container.innerHTML = "";
    lista.forEach((produto) => {
      container.innerHTML += `
        <div class="col-md-4 mb-3">
          <div class="card h-100">
            <img src="${produto.imagem}" class="card-img-top" alt="${
        produto.nome
      }">
            <div class="card-body">
              <h5 class="card-title">${produto.nome}</h5>
              <p class="card-text">R$ ${produto.preco.toFixed(2)}</p>
              <button class="btn btn-primary" onclick="adicionarAoCarrinho('${
                produto.nome
              }')">Adicionar</button>
            </div>
          </div>
        </div>
      `;
    });
  }

  renderizarProdutos(produtos);
  ```

- **Carrinho e pagamento:**
  Gerenciamento do carrinho e simulação de pagamento.

  ```html
  <div id="carrinho" class="carrinho-flutuante">
    <h4>Carrinho</h4>
    <ul id="carrinho-lista"></ul>
    <button class="btn btn-success" onclick="finalizarCompra()">
      Finalizar Compra
    </button>
  </div>
  ```

  ```javascript
  // scripts.js
  let carrinho = [];

  function adicionarAoCarrinho(nomeProduto) {
    const produto = produtos.find((p) => p.nome === nomeProduto);
    if (produto) {
      carrinho.push(produto);
      atualizarCarrinho();
    }
  }

  function atualizarCarrinho() {
    const lista = document.getElementById("carrinho-lista");
    lista.innerHTML = "";
    carrinho.forEach((item, idx) => {
      lista.innerHTML += `<li>${item.nome} - R$ ${item.preco.toFixed(
        2
      )} <button onclick="removerDoCarrinho(${idx})">Remover</button></li>`;
    });
  }

  function removerDoCarrinho(idx) {
    carrinho.splice(idx, 1);
    atualizarCarrinho();
  }

  function finalizarCompra() {
    alert("Compra finalizada! Obrigado por comprar conosco.");
    carrinho = [];
    atualizarCarrinho();
  }
  ```

### 🔐 Página de Login

Área de autenticação para acesso seguro ao sistema.

- **Formulário de autenticação:**
  Estrutura simples e intuitiva para login.

  ```html
  <form id="login-form">
    <div class="mb-3">
      <label for="usuario" class="form-label">Usuário</label>
      <input type="text" class="form-control" id="usuario" required />
    </div>
    <div class="mb-3">
      <label for="senha" class="form-label">Senha</label>
      <input type="password" class="form-control" id="senha" required />
    </div>
    <button type="submit" class="btn btn-primary">Entrar</button>
  </form>
  ```

- **Validação e redirecionamento:**
  Código para validar o login e redirecionar o usuário.

  ```javascript
  // scripts.js
  document
    .getElementById("login-form")
    .addEventListener("submit", function (e) {
      e.preventDefault();
      const usuario = document.getElementById("usuario").value;
      const senha = document.getElementById("senha").value;
      if (usuario === "admin" && senha === "1234") {
        alert("Login realizado com sucesso!");
        window.location.href = "index.html";
      } else {
        alert("Usuário ou senha inválidos.");
      }
    });
  ```

---

## 🎨 Destaques Visuais

- **Cards animados e responsivos** para produtos.
- **Barra de navegação com gradiente** e sombra.
- **Carrinho flutuante** para fácil acesso.
- **Layout adaptado** para dispositivos móveis.

---

> O projeto pode ser expandido com novas funcionalidades, integração com sistemas de pagamento e melhorias contínuas na experiência do usuário.
