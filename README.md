<!DOCTYPE html>
<html lang="es">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>JILG Management</title>
  <style>
    :root {
      --primary-color: #0d47a1;
      --secondary-color: #ffffff;
      --accent-color: #000000;
    }

    * {
      box-sizing: border-box;
    }

    body {
      font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
      margin: 0;
      background-color: var(--secondary-color);
      color: var(--accent-color);
      animation: fadeIn 1s ease-in;
    }

    @keyframes fadeIn {
      from { opacity: 0; transform: translateY(10px); }
      to { opacity: 1; transform: translateY(0); }
    }

    header {
      background-color: var(--primary-color);
      color: var(--secondary-color);
      padding: 2rem;
      text-align: center;
      box-shadow: 0 4px 10px rgba(0, 0, 0, 0.2);
    }

    header h1 {
      margin-bottom: 0.5rem;
    }

    header p {
      font-style: italic;
      color: #bbdefb;
    }

    section {
      padding: 2rem;
      max-width: 900px;
      margin: auto;
    }

    h2 {
      color: var(--primary-color);
      border-left: 4px solid var(--primary-color);
      padding-left: 0.5rem;
    }

    ul {
      list-style: square;
      padding-left: 1.5rem;
    }

    .contact {
      background-color: #e3f2fd;
      padding: 1.5rem;
      border-radius: 8px;
      border: 1px solid var(--primary-color);
      box-shadow: 0 2px 5px rgba(0, 0, 0, 0.1);
    }

    form {
      display: flex;
      flex-direction: column;
      gap: 1rem;
      margin-top: 1rem;
    }

    input, textarea {
      padding: 0.8rem;
      border: 1px solid #ccc;
      border-radius: 4px;
      font-size: 1rem;
    }

    button {
      background-color: var(--primary-color);
      color: white;
      border: none;
      padding: 0.8rem;
      border-radius: 4px;
      cursor: pointer;
    }

    button:hover {
      background-color: #08306b;
    }

    a {
      color: var(--primary-color);
      text-decoration: none;
    }

    a:hover {
      text-decoration: underline;
    }

    footer {
      background-color: var(--accent-color);
      color: var(--secondary-color);
      text-align: center;
      padding: 1rem;
      font-size: 0.9rem;
    }

    .logo {
      font-size: 2rem;
      font-weight: bold;
      margin-bottom: 0.3rem;
    }
  </style>
</head>
<body>
  <header>
    <div class="logo">🔷 JILG Management</div>
    <p>Automatización con IA, gestión de ventas digitales y más</p>
  </header>

  <section>
    <h2>¿Quiénes somos?</h2>
    <p>En <strong>JILG Management</strong> nos especializamos en crear sistemas inteligentes de chat automático, automatización de tareas y gestión de ventas para servicios digitales y software. Operamos 100% en línea y ayudamos a empresas a escalar de forma eficiente mediante el uso de inteligencia artificial.</p>
  </section>

  <section>
    <h2>Servicios</h2>
    <ul>
      <li>Desarrollo de chats automáticos (chatbots IA)</li>
      <li>Automatización de tareas empresariales</li>
      <li>Gestión de ventas y funnels digitales</li>
      <li>Optimización de operaciones con inteligencia artificial</li>
    </ul>
  </section>

  <section>
    <h2>Contacto</h2>
    <div class="contact">
      <p>Correo: <a href="mailto:jilgmanagement@gmail.com">jilgmanagement@gmail.com</a></p>
      <p>Muy pronto con correo corporativo profesional.</p>

      <form action="https://formspree.io/f/moqgkkjo" method="POST">
        <input type="text" name="name" placeholder="Tu nombre" required>
        <input type="email" name="email" placeholder="Tu correo electrónico" required>
        <textarea name="message" placeholder="Tu mensaje" rows="5" required></textarea>
        <button type="submit">Enviar mensaje</button>
      </form>
    </div>
  </section>

  <footer>
    <p>&copy; 2025 JILG Management LLC. Todos los derechos reservados.</p>
  </footer>
</body>
</html>
