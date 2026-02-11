# Emma-Market
Pagina web del almacen Emma Market con catalogo y contacto por WhatsApp
<!DOCTYPE html>
<html lang="es">
<head>
<meta charset="UTF-8">
<title>Emma Market</title>
<link href="https://fonts.googleapis.com/css2?family=Poppins:wght@300;400;600&display=swap" rel="stylesheet">

<style>
body{
  font-family:'Poppins',sans-serif;
  margin:0;
  background:linear-gradient(135deg,#f8bbd0,#e1bee7);
  color:#333;
}

header{
  background:#8e24aa;
  color:white;
  text-align:center;
  padding:25px;
}

img{
  max-width:100%;
}

.section{
  padding:40px 20px;
  text-align:center;
}

.foto-principal img{
  width:100%;
  max-height:500px;
  object-fit:cover;
}

.productos{
  display:flex;
  flex-wrap:wrap;
  gap:20px;
  justify-content:center;
}

.card{
  background:white;
  width:210px;
  padding:15px;
  border-radius:15px;
  box-shadow:0 6px 12px rgba(0,0,0,0.15);
  text-align:center;
}

.precio{
  font-weight:bold;
  color:#8e24aa;
  margin:5px 0;
}

button{
  background:#ec407a;
  color:white;
  border:none;
  padding:8px;
  width:100%;
  border-radius:20px;
  cursor:pointer;
}

.categoria{
  width:100%;
  margin-top:40px;
  font-size:22px;
  color:#8e24aa;
  font-weight:600;
}

.whatsapp{
  position:fixed;
  bottom:20px;
  right:20px;
  background:#25d366;
  color:white;
  font-size:28px;
  padding:15px;
  border-radius:50%;
  text-decoration:none;
  box-shadow:0 4px 10px rgba(0,0,0,0.3);
}
</style>
</head>

<body>

<header>
<h1>Emma Market</h1>
<p>Pedidos por WhatsApp - 095563602</p>
</header>

<section class="foto-principal">
<img src="fachada.jpg">
</section>

<section class="section">
<h2>Nuestro Local</h2>
<img src="interior.jpg">
</section>

<section class="section">
<h2>🎟 Súper Rifa</h2>
<img src="rifa.jpg">
<p><strong>Costo del boleto: $100</strong></p>
<p>Midinero: 3701668133<br>
Titular: Jurema Noemi Paisal</p>
</section>

<section class="section">
<h2>Catálogo Completo</h2>
<div class="productos">

<div class="categoria">Aceites</div>
<div class="card"><h4>Aceite Condesa</h4><div class="precio">$80</div><button onclick="window.open('https://wa.me/59895563602?text=Quiero Aceite Condesa')">Comprar</button></div>
<div class="card"><h4>Aceite Uruguay Girasol</h4><div class="precio">$110</div><button onclick="window.open('https://wa.me/59895563602?text=Quiero Aceite Uruguay')">Comprar</button></div>
<div class="card"><h4>Aceite Cañuelas</h4><div class="precio">$120</div><button onclick="window.open('https://wa.me/59895563602?text=Quiero Aceite Cañuelas')">Comprar</button></div>

<div class="categoria">Almacén</div>
<div class="card"><h4>Azúcar</h4><div class="precio">$75</div><button onclick="window.open('https://wa.me/59895563602?text=Quiero Azucar')">Comprar</button></div>
<div class="card"><h4>Arroz Saman</h4><div class="precio">$75</div><button onclick="window.open('https://wa.me/59895563602?text=Quiero Arroz Saman')">Comprar</button></div>
<div class="card"><h4>Arroz Blue Patna</h4><div class="precio">$80</div><button onclick="window.open('https://wa.me/59895563602?text=Quiero Arroz Blue Patna')">Comprar</button></div>
<div class="card"><h4>Arroz Chef</h4><div class="precio">$80</div><button onclick="window.open('https://wa.me/59895563602?text=Quiero Arroz Chef')">Comprar</button></div>
<div class="card"><h4>Arvejas</h4><div class="precio">$55</div><button onclick="window.open('https://wa.me/59895563602?text=Quiero Arvejas')">Comprar</button></div>
<div class="card"><h4>Arvejas con Maiz</h4><div class="precio">$55</div><button onclick="window.open('https://wa.me/59895563602?text=Quiero Arvejas con Maiz')">Comprar</button></div>
<div class="card"><h4>Harina</h4><div class="precio">$60</div><button onclick="window.open('https://wa.me/59895563602?text=Quiero Harina')">Comprar</button></div>
<div class="card"><h4>Fideos</h4><div class="precio">$65</div><button onclick="window.open('https://wa.me/59895563602?text=Quiero Fideos')">Comprar</button></div>
<div class="card"><h4>Porotos</h4><div class="precio">$65</div><button onclick="window.open('https://wa.me/59895563602?text=Quiero Porotos')">Comprar</button></div>
<div class="card"><h4>Pan Rallado 1k</h4><div class="precio">$160</div><button onclick="window.open('https://wa.me/59895563602?text=Quiero Pan Rallado 1k')">Comprar</button></div>
<div class="card"><h4>Sal</h4><div class="precio">$65</div><button onclick="window.open('https://wa.me/59895563602?text=Quiero Sal')">Comprar</button></div>

<div class="categoria">Bebidas</div>
<div class="card"><h4>Coca-Cola 250ml</h4><div class="precio">$40</div><button onclick="window.open('https://wa.me/59895563602?text=Quiero Coca-Cola 250ml')">Comprar</button></div>
<div class="card"><h4>Coca-Cola 600ml</h4><div class="precio">$70</div><button onclick="window.open('https://wa.me/59895563602?text=Quiero Coca-Cola 600ml')">Comprar</button></div>
<div class="card"><h4>Coca-Cola 2L</h4><div class="precio">$180</div><button onclick="window.open('https://wa.me/59895563602?text=Quiero Coca-Cola 2L')">Comprar</button></div>
<div class="card"><h4>Monster</h4><div class="precio">$120</div><button onclick="window.open('https://wa.me/59895563602?text=Quiero Monster')">Comprar</button></div>
<div class="card"><h4>Vino Faisan</h4><div class="precio">$130</div><button onclick="window.open('https://wa.me/59895563602?text=Quiero Vino Faisan')">Comprar</button></div>
<div class="card"><h4>Vino Roses</h4><div class="precio">$160</div><button onclick="window.open('https://wa.me/59895563602?text=Quiero Vino Roses')">Comprar</button></div>

</div>
</section>

<a href="https://wa.me/59895563602" class="whatsapp">💬</a> }

</body>
</html>
