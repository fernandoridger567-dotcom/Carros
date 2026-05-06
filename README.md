<!DOCTYPE html>
<html lang="pt-br">
<head>
<meta charset="UTF-8">
<title>AutoMarket</title>

<style>
body {
  margin: 0;
  font-family: Arial, sans-serif;
  background: #f5f5f5;
}

header {
  background: #c40000;
  color: white;
  padding: 15px;
  display: flex;
  justify-content: space-between;
}

header h1 {
  margin: 0;
}

nav a {
  color: white;
  margin-left: 15px;
  text-decoration: none;
}

.hero {
  background: url('https://images.unsplash.com/photo-1511919884226-fd3cad34687c') center/cover;
  height: 300px;
  display: flex;
  align-items: center;
  justify-content: center;
  color: white;
  text-align: center;
}

.search-box {
  background: white;
  padding: 15px;
  border-radius: 10px;
}

.container {
  display: flex;
  margin: 20px;
}

.sidebar {
  width: 250px;
  background: white;
  padding: 15px;
  border-radius: 10px;
}

.listings {
  flex: 1;
  margin-left: 20px;
}

.card {
  background: white;
  padding: 15px;
  margin-bottom: 15px;
  border-radius: 10px;
}

.card img {
  width: 100%;
  border-radius: 10px;
}

.price {
  color: #c40000;
  font-size: 20px;
  font-weight: bold;
}

button {
  background: #c40000;
  color: white;
  border: none;
  padding: 10px;
  margin-top: 10px;
  cursor: pointer;
}
</style>
</head>

<body>

<header>
  <h1>AutoMarket 🚗</h1>
  <nav>
    <a href="#">Início</a>
    <a href="#">Anunciar</a>
    <a href="#">Login</a>
  </nav>
</header>

<section class="hero">
  <div>
    <h2>Compre e venda veículos com facilidade</h2>
    <div class="search-box">
      <input type="text" placeholder="Buscar veículo...">
      <button>Buscar</button>
    </div>
  </div>
</section>

<div class="container">

  <div class="sidebar">
    <h3>Filtros</h3>
    <p>Marca</p>
    <p>Preço</p>
    <p>Ano</p>
  </div>

  <div class="listings">

    <div class="card">
      <img src="https://images.unsplash.com/photo-1552519507-da3b142c6e3d">
      <h3>BMW 320i 2019</h3>
      <p class="price">R$ 120.000</p>
      <button>Ver detalhes</button>
    </div>

    <div class="card">
      <img src="https://images.unsplash.com/photo-1549924231-f129b911e442">
      <h3>HB20 2020</h3>
      <p class="price">R$ 55.000</p>
      <button>Ver detalhes</button>
    </div>

  </div>

</div>

</body>
</html>
