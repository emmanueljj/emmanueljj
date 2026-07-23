    <style>
        :root {
            --bg-color: #121212;
            --surface-color: #1e1e1e;
            --text-primary: #e0e0e0;
            --text-secondary: #a0a0a0;
            --accent-color: #61afef;
            --border-color: #333;
        }

        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
            font-family: 'Segoe UI', system-ui, -apple-system, sans-serif;
        }

        body {
            background-color: var(--bg-color);
            color: var(--text-primary);
            line-height: 1.6;
            padding: 0 20px;
        }

        .container {
            max-width: 800px;
            margin: 0 auto;
            padding: 60px 0;
        }

        header {
            margin-bottom: 50px;
            border-bottom: 1px solid var(--border-color);
            padding-bottom: 30px;
        }

        h1 {
            font-size: 2.5rem;
            color: var(--text-primary);
            margin-bottom: 10px;
        }

        h2 {
            font-size: 1.5rem;
            color: var(--accent-color);
            margin-bottom: 20px;
            font-weight: 500;
        }

        p {
            color: var(--text-secondary);
            margin-bottom: 15px;
        }

        .section-title {
            font-size: 1.5rem;
            color: var(--text-primary);
            margin: 40px 0 20px 0;
            border-bottom: 2px solid var(--accent-color);
            display: inline-block;
            padding-bottom: 5px;
        }

        .skills-grid {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(200px, 1fr));
            gap: 20px;
            margin-bottom: 40px;
        }

        .skill-category {
            background-color: var(--surface-color);
            padding: 20px;
            border-radius: 8px;
            border: 1px solid var(--border-color);
        }

        .skill-category h3 {
            color: var(--accent-color);
            margin-bottom: 10px;
            font-size: 1.1rem;
        }

        .skill-category ul {
            list-style-type: none;
        }

        .skill-category li {
            color: var(--text-secondary);
            margin-bottom: 5px;
            font-size: 0.95rem;
        }

        .project-card {
            background-color: var(--surface-color);
            padding: 25px;
            border-radius: 8px;
            border: 1px solid var(--border-color);
            transition: transform 0.2s ease, border-color 0.2s ease;
            margin-bottom: 20px;
        }

        .project-card:hover {
            transform: translateY(-2px);
            border-color: var(--accent-color);
        }

        .project-card h3 {
            color: var(--text-primary);
            margin-bottom: 10px;
        }

        .tags {
            display: flex;
            flex-wrap: wrap;
            gap: 10px;
            margin-top: 15px;
        }

        .tag {
            background-color: rgba(97, 175, 239, 0.1);
            color: var(--accent-color);
            padding: 4px 10px;
            border-radius: 4px;
            font-size: 0.85rem;
            border: 1px solid rgba(97, 175, 239, 0.2);
        }

        .contact-links {
            display: flex;
            gap: 15px;
            margin-top: 20px;
        }

        .contact-links a {
            color: var(--text-primary);
            text-decoration: none;
            padding: 8px 16px;
            border: 1px solid var(--border-color);
            border-radius: 4px;
            background-color: var(--surface-color);
            transition: background-color 0.2s;
        }

        .contact-links a:hover {
            background-color: var(--border-color);
        }
    </style>
</head>

    <div class="container">
        <header>
            <h1>Emmanuel</h1>
            <h2>Desarrollador Full Stack | Enfoque Remoto</h2>
            <p>Estudiante de 3do semestre en Ingeniería de Datos e Inteligencia Artificial (LIDIA) en la Universidad de Guanajuato y Técnico en Programación. Apasionado por el diseño de sistemas, eficiencia y desarrollo de aplicaciones multipataforma.</p>
            <div class="contact-links">
                <a href="https://github.com/tu-usuario" target="_blank">GitHub</a>
                <a href="mailto:tu-correo@email.com">Contacto</a>
            </div>
        </header>

        <p align="center">
        <a href="https://skillicons.dev">
            <img src="https://skillicons.dev/icons?i=linux,git,vscode,css,js,html,react,laravel,mysql,bootstrap,python,c,r,perline=14" />
        </a>
        </p>

        <section>
            <h2 class="section-title">Stack Tecnológico</h2>
            <div class="skills-grid">
                <div class="skill-category">
                    <h3>Backend & API</h3>
                    <ul>
                        <li>PHP</li>
                        <li>Laravel</li>
                        <li>Principios SOLID (POO)</li>
                    </ul>
                </div>
                <div class="skill-category">
                    <h3>Frontend & Móvil</h3>
                    <ul>
                        <li>React Native (expo)</li>
                        <li>JavaScript</li>
                        <li>HTML5 / CSS3</li>
                        <li>Bootstrap</li>
                    </ul>
                </div>
                <div class="skill-category">
                    <h3>Bases de Datos</h3>
                    <ul>
                        <li>MySQL</li>
                        <li>Diseño Relacional</li>
                        <li>Normalización</li>
                    </ul>
                </div>
                <div class="skill-category">
                    <h3>Entorno & Herramientas</h3>
                    <ul>
                        <li>Linux (Debian / Sway WM)</li>
                        <li>Git / GitHub</li>
                        <li>Terminal (Zsh)</li>
                    </ul>
                </div>
            </div>
        </section>

        <section>
            <h2 class="section-title">Proyectos Destacados</h2>
            <div class="project-card">
                <h3>Sistema de Gestión de Reportes</h3>
                <p>Plataforma integral para la administración y seguimiento de reportes. Diseñada con una arquitectura escalable, separando la lógica de negocio y aplicando normalización estricta en la base de datos para garantizar la integridad de la información.</p>
                <div class="tags">
                    <span class="tag">Laravel</span>
                    <span class="tag">PHP</span>
                    <span class="tag">MySQL</span>
                    <span class="tag">API REST</span>
                    <span class="tag">React Native (En progreso)</span>
                </div>
            </div>
        </section>

        <section>
            <h2 class="section-title">Intereses Actuales</h2>
            <p>Actualmente expandiendo mis conocimientos hacia el área de <strong>Ciberseguridad</strong>, buscando integrar prácticas de desarrollo seguro (DevSecOps) en mis aplicaciones web y móviles, mientras continúo mi formación universitaria.</p>
        </section>
    </div>
