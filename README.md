# Asesores-Culturales
<!DOCTYPE html>
<html lang="es">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Asesores Culturales</title>
  <style>
    body { font-family: Arial, sans-serif; margin: 0; padding: 0; background: #f4f4f4; color: #333; }
    header, footer { background: #003366; color: white; padding: 1em 2em; display: flex; align-items: center; justify-content: space-between; }
    header h1 { margin: 0; }
    nav a { color: white; margin: 0 15px; text-decoration: none; }
    .hero { background: url('banner-salud.jpg') no-repeat center center/cover; color: white; text-align: center; padding: 4em 2em; }
    .section { padding: 2em; background: white; margin-bottom: 1em; }
    .catalogo { display: grid; grid-template-columns: repeat(auto-fit, minmax(250px, 1fr)); gap: 1.5em; }
    .libro { background: #fff; border: 1px solid #ddd; padding: 1em; text-align: center; }
    .libro img { max-width: 100%; height: auto; }
    .btn-wa { background: #25d366; color: white; padding: 0.5em 1em; display: inline-block; text-decoration: none; border-radius: 5px; margin-top: 0.5em; }
    footer p { margin: 0.5em 0; }
    .logo { height: 60px; }
  </style>
</head>
<body>
  <header>
    <img src="/mnt/data/f349140f-635d-4caf-8ccd-2eba91a8c9ca.png" alt="Logotipo Asesores Culturales" class="logo">
    <nav>
      <a href="#sobre">Sobre Nosotros</a>
      <a href="#editoriales">Editoriales</a>
      <a href="#catalogo">Catálogo</a>
      <a href="#contacto">Contacto</a>
    </nav>
  </header>

  <div class="hero">
    <h2>Más de 30 años distribuyendo conocimiento</h2>
    <p>Especialistas en libros de ciencias de la salud</p>
  </div>

  <section class="section" id="sobre">
    <h2>Sobre Nosotros</h2>
    <p>Con más de 30 años de experiencia, Asesores Culturales es una distribuidora especializada en libros de ciencias de la salud. Trabajamos con las principales editoriales de México y también conseguimos libros de editoriales internacionales. Atendemos bibliotecas universitarias en todo el país y realizamos envíos a través de FedEx.</p>
  </section>

  <section class="section" id="editoriales">
    <h2>Editoriales que Distribuimos</h2>
    <ul>
      <li>Amolca</li>
      <li>Trillas</li>
      <li>Porrúa</li>
      <li>Panamericana</li>
      <li>Manual Moderno</li>
      <li>Lisermed</li>
    </ul>
  </section>

  <section class="section" id="catalogo">
    <h2>Catálogo de Libros</h2>
    <div class="catalogo">
      <div class="libro">
        <img src="libro1.jpg" alt="Libro 1">
        <h3>Fundamentos de Anatomía Humana</h3>
        <p>Editorial: AMOLCA</p>
        <a class="btn-wa" href="https://wa.me/524871048531?text=Hola,%20me%20interesa%20el%20siguiente%20libro:%0A📘%20Título:%20Fundamentos%20de%20Anatomía%20Humana%0A🏢%20Editorial:%20AMOLCA%0A¿Podrían%20darme%20más%20información%20y%20cotización,%20por%20favor?" target="_blank">Solicitar cotización</a>
      </div>
      <!-- Agrega más libros aquí -->
    </div>
  </section>

  <section class="section" id="contacto">
    <h2>Contacto</h2>
    <p><strong>Dirección:</strong> San Francisco #1417, Fracc. Santa Mónica, Soledad de Graciano Sánchez, SLP</p>
    <p><strong>WhatsApp:</strong> <a href="https://wa.me/524871048531" target="_blank">487 104 85 31</a></p>
    <p><strong>Facebook:</strong> <a href="https://www.facebook.com/profile.php?id=100063658427362" target="_blank">Asesores Culturales</a></p>
  </section>

  <footer>
    <p>&copy; 2025 Asesores Culturales. Todos los derechos reservados.</p>
  </footer>
</body>
</html>
