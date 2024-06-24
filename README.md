# ANIMALES-DEL-MUNDO
<!DOCTYPE html>
<html lang="es">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Animales del Mundo</title>
  <!-- Bootstrap CSS -->
  <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.0/dist/css/bootstrap.min.css" rel="stylesheet">
  <!-- Custom CSS -->
  <style>
    body {
      padding-top: 3rem;
      background-color: #f8f9fa;
    }
    .animal-card {
      margin-bottom: 20px;
    }
  </style>
</head>
<body>
  <header>
    <nav class="navbar navbar-expand-md navbar-dark bg-primary">
      <div class="container">
        <a class="navbar-brand" href="#">Animales del Mundo</a>
        <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarNav" aria-controls="navbarNav" aria-expanded="false" aria-label="Toggle navigation">
          <span class="navbar-toggler-icon"></span>
        </button>
        <div class="collapse navbar-collapse" id="navbarNav">
          <ul class="navbar-nav ms-auto">
            <li class="nav-item">
              <a class="nav-link" href="#terrestres">Terrestres</a>
            </li>
            <li class="nav-item">
              <a class="nav-link" href="#acuaticos">Acuáticos</a>
            </li>
            <li class="nav-item">
              <a class="nav-link" href="#mamiferos">Mamíferos</a>
            </li>
            <li class="nav-item">
              <a class="nav-link" href="#aereos">Aéreos</a>
            </li>
          </ul>
        </div>
      </div>
    </nav>
  </header>

  <main class="container py-4">
    <section id="terrestres">
      <h2 class="mb-4">Animales Terrestres</h2>
      <div class="row row-cols-1 row-cols-md-3 g-4">
        <div class="col">
          <div class="card h-100">
            <img src="gettyimages-1241971351.jpg" class="card-img-top" alt="...">
            <div class="card-body">
              <h5 class="card-title">Elefante</h5>
              <p class="card-text">Los elefantes son los mamíferos terrestres más grandes y herbívoros.</p>
            </div>
          </div>
        </div>
        <div class="col">
          <div class="card h-100">
            <img src="1.jpg" class="card-img-top" alt="...">
            <div class="card-body">
              <h5 class="card-title">León</h5>
              <p class="card-text">El león es el rey de la selva y un poderoso depredador.</p>
            </div>
          </div>
        </div>
        <div class="col">
          <div class="card h-100">
            <img src="oso.jpeg" class="card-img-top" alt="...">
            <div class="card-body">
              <h5 class="card-title">Oso</h5>
              <p class="card-text">Los osos son grandes mamíferos omnívoros que viven en diversas regiones del mundo.</p>
            </div>
          </div>
        </div>
      </div>
    </section>

    <section id="acuaticos" class="mt-5">
      <h2 class="mb-4">Animales Acuáticos</h2>
      <div class="row row-cols-1 row-cols-md-3 g-4">
        <div class="col">
          <div class="card h-100">
            <img src="delfin.jpg" class="card-img-top" alt="...">
            <div class="card-body">
              <h5 class="card-title">Delfín</h5>
              <p class="card-text">Los delfines son mamíferos marinos conocidos por su inteligencia y comportamiento juguetón.</p>
            </div>
          </div>
        </div>
        <div class="col">
          <div class="card h-100">
            <img src="tiburones-e1588033520746.jpg" class="card-img-top" alt="...">
            <div class="card-body">
              <h5 class="card-title">Tiburón</h5>
              <p class="card-text">Los tiburones son peces cartilaginosos que ocupan un lugar destacado en el ecosistema marino.</p>
            </div>
          </div>
        </div>
        <div class="col">
          <div class="card h-100">
            <img src="ballena.webp" class="card-img-top" alt="...">
            <div class="card-body">
              <h5 class="card-title">Ballena</h5>
              <p class="card-text">Las ballenas son mamíferos marinos enormes y algunos de los animales más grandes del planeta.</p>
            </div>
          </div>
        </div>
      </div>
    </section>

    <section id="mamiferos" class="mt-5">
      <h2 class="mb-4">Mamíferos</h2>
      <div class="row row-cols-1 row-cols-md-3 g-4">
        <div class="col">
          <div class="card h-100">
            <img src="gato.jpeg" class="card-img-top" alt="...">
            <div class="card-body">
              <h5 class="card-title">Gato</h5>
              <p class="card-text">Los gatos son felinos domésticos apreciados por su independencia y habilidades cazadoras.</p>
            </div>
          </div>
        </div>
        <div class="col">
          <div class="card h-100">
            <img src="perro.jpg" class="card-img-top" alt="...">
            <div class="card-body">
              <h5 class="card-title">Perro</h5>
              <p class="card-text">Los perros son conocidos por ser leales compañeros de los humanos y por su variedad de razas y tamaños.</p>
            </div>
          </div>
        </div>
        <div class="col">
          <div class="card h-100">
            <img src="Mono-especies-min-e1534428646276.jpg" class="card-img-top" alt="...">
            <div class="card-body">
              <h5 class="card-title">Mono</h5>
              <p class="card-text">Los monos son primates muy inteligentes y sociales, que se encuentran en diversas partes del mundo.</p>
            </div>
          </div>
        </div>
      </div>
    </section>

    <section id="aereos" class="mt-5">
      <h2 class="mb-4">Animales Aéreos</h2>
      <div class="row row-cols-1 row-cols-md-3 g-4">
        <div class="col">
          <div class="card h-100">
            <img src="aguila.jpg" class="card-img-top" alt="...">
            <div class="card-body">
              <h5 class="card-title">Águila</h5>
              <p class="card-text">Las águilas son aves rapaces conocidas por su agudeza visual y habilidades de caza.</p>
            </div>
          </div>
        </div>
        <div class="col">
          <div class="card h-100">
            <img src="colibri.avif" class="card-img-top" alt="...">
            <div class="card-body">
              <h5 class="card-title">Colibrí</h5>
              <p class="card-text">Los colibríes son las aves más pequeñas y tienen un vuelo rápido y ágil.</p>
            </div>
          </div>
        </div>
        <div class="col">
          <div class="card h-100">
            <img src="buho.jpg" class="card-img-top" alt="...">
            <div class="card-body">
              <h5 class="card-title">Búho</h5>
              <p class="card-text">Los búhos son aves nocturnas que están asociadas con la sabiduría y la inteligencia en muchas culturas.</
