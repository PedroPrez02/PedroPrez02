<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <meta name="description" content="Portafolio personal con proyectos, habilidades y formulario de contacto.">
  <title>Mi Portafolio</title>
  <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.0/dist/css/bootstrap.min.css" rel="stylesheet">
</head>
<body>
  <header class="bg-primary text-white text-center py-4">
    <h1>Pedro Pérez</h1>
  </header>
  <main>
    <!-- Página de Inicio -->
    <section id="inicio" class="text-center py-5">
      <div class="container">
        <h2>Sobre mí</h2>
        <p>Hola, soy Pedro, un estudiante de ASIR. Me encantaría trabajar en proyectos innovadores y siempre estoy buscando aprender cosas nuevas.</p>
        <img src="img/perfil.jpg" alt="Imagen representativa de mi perfil" class="img-fluid rounded-circle" style="max-width: 150px;">
      </div>
    </section>
    <!-- Proyectos -->
    <section id="proyectos" class="py-5 bg-light">
      <div class="container">
        <h2 class="text-center">Mis Proyectos</h2>
        <div class="row">
          <!-- Proyecto 1 -->
          <div class="col-md-4">
            <div class="card">
              <img src="img/proyecto1.jpg" class="card-img-top" alt="github">
              <div class="card-body">
                <h5 class="card-title">Github</h5>
                <p class="card-text">Creación y configuración de un perfil en Github.</p>
                <a href="#" class="btn btn-primary">Inicio</a>
              </div>
            </div>
          </div>
          <!-- Proyecto 2 -->
          <div class="col-md-4">
            <div class="card">
              <img src="img/proyecto1.jpg" class="card-img-top" alt="xampp">
              <div class="card-body">
                  <h5 class="card-title">XAMPP</h5>
                <p class="card-text">Instalación y configuración de XAMPP.</p>
                <a href="#" class="btn btn-primary">Inicio</a>
              </div>
            </div>
          </div>
          <!-- Proyecto 3 -->
          <div class="col-md-4">
            <div class="card">
              <img src="img/proyecto1.jpg" class="card-img-top" alt="infografias">
              <div class="card-body">
                <h5 class="card-title">Infografías</h5>
                <p class="card-text">Creación de inforgrafías.</p>
                <a href="#" class="btn btn-primary">Inicio</a>
              </div>
            </div>
          </div>
        </div>
      </div>
    </section>
    <!-- Habilidades -->
    <section id="habilidades" class="py-5">
      <div class="container">
        <h2 class="text-center">Habilidades</h2>
        <div class="row">
          <div class="col-md-4 text-center">
            <i class="bi bi-code-slash" style="font-size: 2rem;"></i>
            <h4>Programación</h4>
          </div>
          <div class="col-md-4 text-center">
            <i class="bi bi-database" style="font-size: 2rem;"></i>
            <h4>Bases de Datos</h4>
          </div>
          <div class="col-md-4 text-center">
            <i class="bi bi-layout-text-sidebar-reverse" style="font-size: 2rem;"></i>
            <h4>Diseño Web</h4>
          </div>
        </div>
      </div>
    </section>
    <!-- Contacto -->
    <section id="contacto" class="py-5 bg-light">
      <div class="container">
        <h2 class="text-center">Contacto</h2>
        <form>
          <div class="mb-3">
            <label for="nombre" class="form-label">Nombre</label>
            <input type="text" class="form-control" id="nombre" placeholder="Ingresa tu nombre">
          </div>
          <div class="mb-3">
            <label for="correo" class="form-label">Correo Electrónico</label>
            <input type="email" class="form-control" id="correo" placeholder="Ingresa tu correo">
          </div>
          <div class="mb-3">
            <label for="mensaje" class="form-label">Mensaje</label>
            <textarea class="form-control" id="mensaje" rows="3" placeholder="Escribe tu mensaje"></textarea>
          </div>
          <button type="submit" class="btn btn-primary">Enviar</button>
        </form>
      </div>
    </section>
  </main>
  <footer class="text-center py-4 bg-dark text-white">
    <p>&copy; 2025 Mi Página Web</p>
  </footer>
</body>
</html>

