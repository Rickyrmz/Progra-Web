# Progra-Web
Programacion web 2024 con luislao
<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Hamburguesas Chucky</title>
    
    <!-- Enlace a de Bootstrap -->
    <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.0/dist/css/bootstrap.min.css" rel="stylesheet">

    <!-- Enlace a la biblioteca de iconos que encontre por ahi -->
    <link href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.0.0/css/all.min.css" rel="stylesheet">
    <!--Enlace a la carpeta CSS-->
    <link rel="stylesheet" href="hamburguesas chucky.css">
  </head>
  <body>
      
      <header>
          <!-- Iconos a la izquierda del banner -->
          <div class="icons">
              <i class="fas fa-hamburger"></i>
              <i class="fas fa-utensils"></i>
              <i class="fas fa-hamburger"></i>
              <i class="fas fa-utensils"></i>
              <i class="fas fa-hamburger"></i>
          </div>
  
          <img src="imagen/LOGO-HAMBURGUESAS CHUCKY_page-0001.jpg" alt="Logo Chucky">
  
          <!-- Iconos a la derecha del banner -->
          <div class="icons-right">
              <i class="fas fa-hamburger"></i>
              <i class="fas fa-utensils"></i>
              <i class="fas fa-hamburger"></i>
              <i class="fas fa-utensils"></i>
              <i class="fas fa-hamburger"></i>
          </div>
      </header>
  
      <nav class="navbar" style="background-color: #ff6347;">
          <div class="container-fluid">
              <a class="navbar-brand" href="#">   </a>
              <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarSupportedContent" aria-controls="navbarSupportedContent" aria-expanded="false" aria-label="Toggle navigation">
                <span class="navbar-toggler-icon"></span>
              </button>
              <div class="collapse navbar-collapse" id="navbarSupportedContent">
                <ul class="navbar-nav me-auto mb-2 mb-lg-0">
                  <li class="nav-item">
                    <a class="nav-link active" aria-current="page" href="#">Inicio</a>
                  </li>
                  <li class="nav-item">
                    <a class="nav-link" href="#">Promociones</a>
                  </li>
                  <li class="nav-item dropdown">
                    <a class="nav-link dropdown-toggle" href="#" role="button" data-bs-toggle="dropdown" aria-expanded="false">
                      Mas informacion
                    </a>
                    <ul class="dropdown-menu">
                      <li><a class="dropdown-item" href="#">Contrataciones (se parte de nuestro equipo de trabajo )</a></li>
                      <li><a class="dropdown-item" href="#">Sucursales</a></li>
                      <li><hr class="dropdown-divider"></li>
                      <li><a class="dropdown-item" href="#">Dudas/Quejas</a></li>
                    </ul>
                  </li>
                  <li class="nav-item">
                    <a class="dropdown-item" href="#">Servicio a Domicilio</a>
                  </li>
                </ul>
                <form class="d-flex" role="search">
                  <input class="form-control me-2" type="search" placeholder="Search" aria-label="Search">
                  <button class="btn btn-outline-success" type="submit">Buscar</button> 
                </form>
              </div>
            </div>
          </nav>
      <nav>
          <a href="#menu">Menú</a>
          <a href="#about">Nosotros</a>
          <a href="#contact">Contacto</a>
      </nav>
  
  <!--catalogo de hamburguesas que ofrezco y promociones-->
      <div class="container">
          <div id="carouselExampleControls" class="carousel slide" data-bs-ride="carousel">
              <div class="carousel-inner">
                <div class="carousel-item active">
                  <img src="imagen/burguer header.png" class="d-block w-100" alt="...">
                </div>
                <div class="carousel-item">
                  <img src="imagen/burguer header 3.png" class="d-block w-100" alt="...">
                </div>
                <div class="carousel-item">
                  <img src="imagen/burguer header 3.png" class="d-block w-100" alt="...">
                </div>
              </div>
              <button class="carousel-control-prev" type="button" data-bs-target="#carouselExampleControls" data-bs-slide="prev">
                <span class="carousel-control-prev-icon" aria-hidden="true"></span>
                <span class="visually-hidden">Previous</span>
              </button>
              <button class="carousel-control-next" type="button" data-bs-target="#carouselExampleControls" data-bs-slide="next">
                <span class="carousel-control-next-icon" aria-hidden="true"></span>
                <span class="visually-hidden">Next</span>
              </button>
            </div>
          
          <section id="menu">
              <h2>Menú</h2>
              <div class="menu">
                  <div class="menu-item">
                      <img src="imagen/hamburguesa clasica .jpg" alt="Hamburguesa Clásica">
                      <h3>Hamburguesa Clásica</h3>
                      <p>$30.99</p>
                  </div>
                  <div class="menu-item">
                      <img src="imagen/hamburguesa BBQ.jpg" alt="Hamburguesa BBQ">
                      <h3>Hamburguesa BBQ</h3>
                      <p>$50.99</p>
                  </div>
                  <div class="menu-item">
                      <img src="imagen/hamburguesa doble queso.jpg" alt="Hamburguesa Doble Queso">
                      <h3>Hamburguesa Doble Queso</h3>
                      <p>$59.99</p>
                  </div>
              </div>
          </section>
  
          <div class="divider">
              <div class="icon">🍔</div>
          </div>
  
          <section               
              id="about">
                <h2><a href="historia.html">Sobre Nosotros</a></h2>
                <p>Nuestra misión es ofrecer hamburguesas de la mejor calidad, hechas con ingredientes frescos y de origen local. Nos esforzamos por brindar una experiencia gastronómica única en un ambiente amigable y acogedor.</p>
            </section>
  
          <div class="divider">
              <div class="icon">🥤</div>
          </div>
  
          <section id="contact">
              <h2>Contacto</h2>
              <p>Para consultas, reservas o más información, contáctanos en:</p>
              <p>Email: contacto@hamburguesaschucky.com</p>
              <p>Teléfono: +52 123 456 7890</p>
              <p>Visítanos en nuestras sucursales o síguenos en nuestras redes sociales.</p>
          </section>
      </div>
  
      <footer>
          <p>&copy; 2024 Hamburguesas Chucky. Todos los derechos reservados.</p>
      </footer>
  
      <!-- Enlace de Bootstrap -->
      <script src="https://cdn.jsdelivr.net/npm/bootstrap@5.3.0/dist/js/bootstrap.bundle.min.js"></script>
  
  </body>
  </html>
  
