<html><head><base href="javascript:void(0)" />

<meta charset="UTF-8">

<meta name="viewport" content="width=device-width, initial-scale=1.0">

<title>ADIDAS Collection - ZapatoStyle</title>



<link href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.2/dist/css/bootstrap.min.css" rel="stylesheet">

<script src="https://cdn.jsdelivr.net/npm/bootstrap@5.3.2/dist/js/bootstrap.bundle.min.js"></script>

<link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.0.0/css/all.min.css">



<style>

:root {

--adidas-blue: #0A3B7C;

--adidas-black: #000000;

}



body {

background: linear-gradient(135deg, #f5f5f5 0%, white 100%); font-family: 'Helvetica', Arial, sans-serif;

}



.navbar {

background-color: var(--adidas-black) !important;

}



.product-card {

transition: transform 0.3s; background: white; border-radius: 10px;

box-shadow: 0 4px 8px rgba(0,0,0,0.1); margin-bottom: 20px;

}



.product-card:hover { transform: translateY(-5px);

}



.product-price {

color: var(--adidas-blue); font-size: 1.25rem;

font-weight: bold;

}



.adidas-btn {

background-color: var(--adidas-blue); color: white;

 

border: none;

}



.adidas-btn:hover { background-color: #052a5c; color: white;

}



#cart-counter { position: relative; top: -10px;

right: -5px;

background-color: var(--adidas-blue); color: white;

border-radius: 50%; padding: 2px 6px; font-size: 12px;

}



.footer {

background-color: var(--adidas-black); color: white;

padding: 20px 0; margin-top: 40px;

}



.sale-badge { position: absolute; top: 10px;

right: 10px;

background-color: var(--adidas-blue); color: white;

padding: 5px 10px; border-radius: 5px;

}

</style>

</head>

<body>



<nav class="navbar navbar-expand-lg navbar-dark">

<div class="container">

<a class="navbar-brand" href="">

<img src="https://images.unsplash.com/photo-1551116198-01d550c9809c" alt="ADIDAS Logo, three stripes in white" width="40" height="40" class="d-inline-block align-text-top me-2">

ADIDAS Collection

</a>

 

<button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarNav">

<span class="navbar-toggler-icon"></span>

</button>



<div class="collapse navbar-collapse" id="navbarNav">

<ul class="navbar-nav me-auto">

<li class="nav-item">

<a class="nav-link" href="https://jd-354.github.io/z/"><i class="fas fa-home"></i> Inicio</a>

</li>

<li class="nav-item">

<a class="nav-link" href="https://jd-354.github.io/N/"><i class="fas fa-fire"></i> Nuevos Lanzamientos</a>

</li>

<li class="nav-item">

<a class="nav-link" href="https://jd-354.github.io/DPT/"><i class="fas fa-running"></i> Deportivos</a>

</li>
<a class="nav-link" href="https://jd-354.github.io/Cpr/"><i class="fas fa-fire"></i>Envios</a>


</ul>



<div class="cart-container">

<button class="btn btn-outline-light">

<i class="fas fa-shopping-cart"></i>

<span id="cart-counter">0</span>

</button>

</div>

</div>

</div>

</nav>



<div class="container mt-4">

<h1 class="text-center mb-4">Colección ADIDAS</h1>



<div class="row">

<!-- Adidas Ultraboost -->

<div class="col-md-4">

<div class="product-card p-3">

<div class="position-relative">

<img src="https://images.unsplash.com/photo-1587563871167-1ee9c731aefb" alt="Adidas Ultraboost, premium running shoe" class="img-fluid mb-3" width="100%" height="300">

<span class="sale-badge">Nuevo</span>

</div>

<h5>Adidas Ultraboost</h5>

<p class="product-price">$179.99</p>

<div class="d-flex justify-content-between">

<select class="form-select w-50 me-2">

 

<option>Talla 7</option>

<option>Talla 8</option>

<option>Talla 9</option>

<option>Talla 10</option>

</select>

<button class="btn adidas-btn flex-grow-1">Añadir al carrito</button>

</div>

</div>

</div>



<!-- Adidas Superstar -->

<div class="col-md-4">

<div class="product-card p-3">

<img src="https://images.unsplash.com/photo-1588361861040-ac9b1018f6d5" alt="Adidas Superstar, classic white with black stripes" class="img-fluid mb-3" width="100%" height="300">

<h5>Adidas Superstar</h5>

<p class="product-price">$89.99</p>

<div class="d-flex justify-content-between">

<select class="form-select w-50 me-2">

<option>Talla 7</option>

<option>Talla 8</option>

<option>Talla 9</option>

<option>Talla 10</option>

</select>

<button class="btn adidas-btn flex-grow-1">Añadir al carrito</button>

</div>

</div>

</div>



<!-- Adidas NMD -->

<div class="col-md-4">

<div class="product-card p-3">

<img src="https://images.unsplash.com/photo-1551116198-01d550c9809c" alt="Adidas NMD, modern streetwear design" class="img-fluid mb-3" width="100%" height="300">

<h5>Adidas NMD</h5>

<p class="product-price">$139.99</p>

<div class="d-flex justify-content-between">

<select class="form-select w-50 me-2">

<option>Talla 7</option>

<option>Talla 8</option>

<option>Talla 9</option>

<option>Talla 10</option>

</select>

<button class="btn adidas-btn flex-grow-1">Añadir al carrito</button>

</div>

</div>

 

</div>



<!-- Adidas Stan Smith -->

<div class="col-md-4">

<div class="product-card p-3">

<img src="https://images.unsplash.com/photo-1603787081207-362bcef7c144" alt="Adidas Stan Smith, classic tennis shoe" class="img-fluid mb-3" width="100%" height="300">

<h5>Adidas Stan Smith</h5>

<p class="product-price">$79.99</p>

<div class="d-flex justify-content-between">

<select class="form-select w-50 me-2">

<option>Talla 7</option>

<option>Talla 8</option>

<option>Talla 9</option>

<option>Talla 10</option>

</select>

<button class="btn adidas-btn flex-grow-1">Añadir al carrito</button>

</div>

</div>

</div>



<!-- Adidas Gazelle -->

<div class="col-md-4">

<div class="product-card p-3">

<img src="https://images.unsplash.com/photo-1585232004423-244e0e6904e3" alt="Adidas Gazelle, retro suede sneaker" class="img-fluid mb-3" width="100%" height="300">

<h5>Adidas Gazelle</h5>

<p class="product-price">$99.99</p>

<div class="d-flex justify-content-between">

<select class="form-select w-50 me-2">

<option>Talla 7</option>

<option>Talla 8</option>

<option>Talla 9</option>

<option>Talla 10</option>

</select>

<button class="btn adidas-btn flex-grow-1">Añadir al carrito</button>

</div>

</div>

</div>

</div>

</div>



<footer class="footer">

<div class="container">

<div class="row">

<div class="col-md-4">

 

<h5>Contacto</h5>

<p><i class="fas fa-phone"></i> +1 234 567 890</p>

<p><i class="fas fa-envelope"></i> adidas@zapatostyle.com</p>

</div>

<div class="col-md-4">

<h5>Síguenos</h5>

<a href="https://facebook.com/adidas" class="text-white me-3"><i class="fab fa-facebook"></i></a>

<a href="https://instagram.com/adidas" class="text-white me-3"><i class="fab fa-instagram"></i></a>

<a href="https://twitter.com/adidas" class="text-white"><i class="fab fa-twitter"></i></a>

</div>

<div class="col-md-4">

<h5>Newsletter</h5>

<p>Recibe las últimas novedades de ADIDAS</p>

<form class="d-flex">

<input type="email" class="form-control me-2" placeholder="Tu email">

<button class="btn adidas-btn">Suscribir</button>

</form>

</div>

</div>

</div>

</footer>



<script>

let cartCount = 0;



document.querySelectorAll('.adidas-btn').forEach(button => { button.addEventListener('click', () => {

if(button.textContent.includes('Añadir al carrito')) { cartCount++;

document.getElementById('cart-counter').textContent = cartCount;



 













}

});

});

 

const counter = document.getElementById('cart-counter'); counter.style.transform = 'scale(1.5)';

setTimeout(() => { counter.style.transform = 'scale(1)';

}, 200);

 

</script>



</body>

</html>

