
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
            <li><a href="index_caballero.html">Inicio</a></li>
            <li>
                <a href="#">Servicios</a>
                <ul>
                    <a href="galeria.html">Diseño</a>
                    <a href="formulario.html">Desarrollo</a>
                    <a href="listas2.html">Marketing</a>
                </ul>
            </li>
            <li><a href="modelocaja.html">Portafolio</a></li>
            <li><a href="barranaveg.html">Contacto</a></li>
        </ul>
    </nav>
</body>
</html>
