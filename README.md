<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <meta name="description" content="Portafolio de servicios profesionales y blog personal de Raquel. Zona de debate y educación financiera.">
    <title>Raquel - Portafolio y Blog</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            background-color: #f4f4f9;
            color: #333;
            margin: 0;
            padding: 0;
        }
        header {
            background-color: #0056b3;
            color: white;
            padding: 1em;
            text-align: center;
        }
        nav {
            display: flex;
            justify-content: center;
            background-color: #007bff;
            padding: 1em;
        }
        nav a {
            color: white;
            text-decoration: none;
            margin: 0 15px;
            font-weight: bold;
        }
        nav a:hover {
            text-decoration: underline;
        }
        section {
            padding: 2em;
            margin: 1em auto;
            max-width: 1000px;
            background-color: white;
            box-shadow: 0 2px 10px rgba(0, 0, 0, 0.1);
        }
        h1, h2 {
            color: #0056b3;
        }
        footer {
            text-align: center;
            padding: 1em;
            background-color: #0056b3;
            color: white;
        }
        .blog-section, .info-section {
            background-color: #e9f5ff;
        }
        .contact-section {
            background-color: #f9f9f9;
        }
        .services, .blog, .info, .finance {
            margin: 1.5em 0;
        }
        input, textarea {
            width: 100%;
            padding: 0.5em;
            margin: 0.5em 0;
            border: 1px solid #ddd;
            border-radius: 5px;
        }
        button {
            background-color: #0056b3;
            color: white;
            padding: 0.7em 1.2em;
            border: none;
            border-radius: 5px;
            cursor: pointer;
        }
        button:hover {
            background-color: #004099;
        }
    </style>
</head>
<body>
    <header>
        <h1>Raquel - Portafolio Profesional y Blog</h1>
        <p>Servicios financieros y espacio para compartir ideas</p>
    </header>

    <nav>
        <a href="#servicios">Servicios</a>
        <a href="#blog">Blog</a>
        <a href="#informativa">Zona Informativa</a>
        <a href="#educacion">Educación Financiera</a>
        <a href="#contacto">Contacto</a>
    </nav>

    <section id="servicios" class="services-section">
        <h2>Servicios Profesionales</h2>
        <p>Ofrezco asesoramiento financiero personalizado, planificación de inversiones, gestión de carteras y consultoría en ahorro y planificación fiscal.</p>
        <ul>
            <li>Asesoramiento financiero personalizado</li>
            <li>Planificación de inversiones</li>
            <li>Gestión de carteras</li>
            <li>Consultoría en ahorro y planificación fiscal</li>
        </ul>
    </section>

    <section id="blog" class="blog-section">
        <h2>Blog Personal</h2>
        <p>En mi blog comparto reflexiones sobre temas financieros y personales. ¡Déjame tu opinión!</p>
        <article class="blog">
            <h3>Último post: La importancia del ahorro</h3>
            <p>El ahorro es esencial para una buena salud financiera. Aquí te explico cómo empezar...</p>
            <textarea rows="4" placeholder="Escribe un comentario..."></textarea>
            <button>Enviar comentario</button>
        </article>
    </section>

    <section id="informativa" class="info-section">
        <h2>Zona Informativa</h2>
        <p>Este es un espacio para el debate sobre temas financieros con otros profesionales. ¡Únete a la conversación!</p>
        <article class="info">
            <h3>Último debate: ¿Cómo afectarán las nuevas regulaciones financieras?</h3>
            <textarea rows="4" placeholder="Escribe tu opinión..."></textarea>
            <button>Participar</button>
        </article>
    </section>

    <section id="educacion" class="finance-section">
        <h2>Educación Financiera</h2>
        <p>Recursos y consejos prácticos para mejorar tu educación financiera y tomar decisiones más informadas.</p>
        <ul>
            <li>Introducción a la inversión</li>
            <li>Conceptos básicos de finanzas personales</li>
            <li>Herramientas para la planificación financiera</li>
        </ul>
    </section>

    <section id="contacto" class="contact-section">
        <h2>Contacto</h2>
        <p>Puedes ponerte en contacto conmigo a través del siguiente formulario:</p>
        <form>
            <label for="name">Nombre:</label>
            <input type="text" id="name" name="name" required>
            <label for="email">Correo electrónico:</label>
            <input type="email" id="email" name="email" required>
            <label for="message">Mensaje:</label>
            <textarea id="message" name="message" rows="4" required></textarea>
            <button type="submit">Enviar mensaje</button>
        </form>
    </section>

    <footer>
        <p>&copy; 2024 Raquel. Todos los derechos reservados.</p>
    </footer>
</body>
</html>
