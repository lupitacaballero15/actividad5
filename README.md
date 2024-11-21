
<html>
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Menú de Navegación</title>
    <style>
        .menu {
            background-color: #f1f1f1;
            overflow: hidden;
        }
        .menu ul {
            list-style-type: none;
            margin: 0;
            padding: 0;
            display: flex;
        }
        .menu li {
            float: left;
        }
        .menu li a {
            display: block;
            color: black;
            text-align: center;
            padding: 14px 16px;
            text-decoration: none;
        }
        .menu li a:hover {
            background-color: #ddd;  
        }
        .menu li ul {
            display: none;
        }
        .menu li:hover ul {
            display: block;
        }
    </style>
</head>
<body>
    <nav class="menu">
        <ul>
            <li><a href="https://www.google.com.mx/?hl=es-419">Inicio</a></li>
            <li>
                <a href="#">Servicios</a>
                <ul>
                    <a href="https://www.facebook.com/">Diseño</a>
                    <a href="https://www.instagram.com/">Desarrollo</a>
                    <a href="https://www.tiktok.com/es/">Marketing</a>
                </ul>
            </li>
            <li><a href="https://mx.linkedin.com/">Portafolio</a></li>
            <li><a href="https://x.com/?lang=es">Contacto</a></li>
        </ul>
    </nav>
</body>
</html>

