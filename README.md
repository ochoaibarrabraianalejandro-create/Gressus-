<!DOCTYPE html>
<html lang="es">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">

  <title>GRESSUS | Avanza a tu manera</title>

  <link rel="stylesheet" href="style.css">
</head>

<body>

  <!-- MENÚ -->
  <header>
    <div class="logo">GRESSUS</div>

    <nav>
      <a href="#inicio">Inicio</a>
      <a href="#coleccion">Colección</a>
      <a href="#nosotros">Nosotros</a>
      <a href="#contacto">Contacto</a>
    </nav>
  </header>


  <!-- INICIO -->
  <section id="inicio" class="hero">

    <div class="hero-text">

      <p class="small-title">ESTILO · CLASE · IDENTIDAD</p>

      <h1>Avanza<br>a tu manera.</h1>

      <p>
        Gressus nace para quienes quieren avanzar,
        expresar su estilo y construir su propia identidad.
      </p>

      <a href="#coleccion" class="button">
        VER COLECCIÓN
      </a>

    </div>

  </section>


  <!-- COLECCIÓN -->
  <section id="coleccion" class="collection">

    <p class="small-title">NUESTRA COLECCIÓN</p>

    <h2>Encuentra tu estilo</h2>

    <div class="products">

      <div class="product">

        <div class="shoe">
          <span>GRESSUS</span>
        </div>

        <h3>Air Jordan 4 Retro</h3>

        <p>
          Diseño urbano para destacar
          a tu manera.
        </p>

        <button onclick="verProducto('Air Jordan 4 Retro')">
          VER PRODUCTO
        </button>

      </div>


      <div class="product">

        <div class="shoe">
          <span>GRESSUS</span>
        </div>

        <h3>White Thunder</h3>

        <p>
          Estilo moderno con personalidad
          y presencia.
        </p>

        <button onclick="verProducto('White Thunder')">
          VER PRODUCTO
        </button>

      </div>


      <div class="product">

        <div class="shoe">
          <span>GRESSUS</span>
        </div>

        <h3>Edición Gressus</h3>

        <p>
          Una colección pensada para
          expresar quién eres.
        </p>

        <button onclick="verProducto('Edición Gressus')">
          VER PRODUCTO
        </button>

      </div>

    </div>

  </section>


  <!-- NOSOTROS -->
  <section id="nosotros" class="about">

    <p class="small-title">GRESSUS</p>

    <h2>Un paso.<br>Tu estilo.</h2>

    <p>
      Gressus representa movimiento, identidad y libertad.
      No se trata solamente de lo que llevas,
      sino de cómo decides avanzar.
    </p>

  </section>


  <!-- CONTACTO -->
  <section id="contacto" class="contact">

    <p class="small-title">CONTACTO</p>

    <h2>Da el siguiente paso.</h2>

    <p>
      Conoce nuestros productos y descubre
      el estilo que va contigo.
    </p>

    <a class="button" href="mailto:contacto@gressus.com">
      CONTACTARNOS
    </a>

  </section>


  <!-- PIE DE PÁGINA -->
  <footer>

    <h3>GRESSUS</h3>

    <p>Avanza a tu manera.</p>

    <p>© 2026 Gressus</p>

  </footer>


  <script src="script.js"></script>

</body>
</html>
