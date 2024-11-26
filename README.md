
<html>
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Formulario</title>
    <style>
        .contenedor-formulario {
            width: 400px;
            margin: 0 auto;
            background-color: #fff;
            padding: 20px;
            border-radius: 10px;
            box-shadow: 0 0 5px rgba(0,0,0,0.3);
        }
        label {
            display: block;
            margin-bottom: 5px;
        }
        input, textarea {
            width: 100%;
            padding: 10px;
            margin-bottom: 15px;
            border: 1px solid #ccc;
            border-radius: 5px;
        }
        button {
            background-color: #4CAF50;
            color: white;
            padding: 10px 20px;
            border: none;
            border-radius: 5px;
            cursor: pointer;
        }
        button:hover {
            background-color: #3e8e41;
        }
    </style>
</head>
<body>
    <div class="contenedor-formulario">
        <h1>Formulario de Contacto</h1>
        <p>Por favor completa este formulario para contactarnos.</p>
        <form action="#" method="post">
            <label for="nombre">Nombre:</label>
            <input type="text" id="nombre" name="nombre" required>

            <label for="email">Correo electrónico:</label>
            <input type="email" id="email" name="email" required>

            <label for="telefono">Teléfono:</label>
            <input type="tel" id="telefono" name="telefono">

            <label for="pais">País:</label>
            <select id="pais" name="pais">
                <option value="es">España</option>
                <option value="mx">México</option>
                </select>

            <label for="mensaje">Mensaje:</label>
            <textarea id="mensaje" name="mensaje" rows="5"></textarea>

            <button type="submit">Enviar</button>
        </form>
    </div>
</body>
</html>
