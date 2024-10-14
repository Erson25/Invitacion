<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Invitación de Boda</title>
    <link rel="stylesheet" href="styles.css">
</head>
<body>
    <header>
        <h1>¡Nos Casamos!</h1>
        <h2>[Nombres de los novios]</h2>
        <p>Te invitamos a celebrar con nosotros</p>
    </header>

    <section class="details">
        <h3>Detalles del Evento</h3>
        <p><strong>Fecha:</strong> [Fecha de la boda]</p>
        <p><strong>Hora:</strong> [Hora del evento]</p>
        <p><strong>Lugar:</strong> [Lugar de la ceremonia]</p>
        <div class="map">
            <h3>Ubicación</h3>
            <iframe src="[Enlace a Google Maps]" width="600" height="450" style="border:0;" allowfullscreen="" loading="lazy"></iframe>
        </div>
    </section>

    <section class="music">
        <h3>Nuestra Playlist</h3>
        <p>Disfruta de nuestra música antes del gran día:</p>
        <iframe src="[Enlace a Spotify]" width="300" height="80" frameborder="0" allowtransparency="true" allow="encrypted-media"></iframe>
    </section>

    <section class="rsvp">
        <h3>Confirma tu Asistencia</h3>
        <form action="https://formspree.io/f/[tu-email]" method="POST">
            <label for="name">Nombre Completo:</label>
            <input type="text" id="name" name="name" required>
            <label for="email">Correo Electrónico:</label>
            <input type="email" id="email" name="email" required>
            <label for="attendance">¿Asistirás?</label>
            <select id="attendance" name="attendance" required>
                <option value="Sí">Sí</option>
                <option value="No">No</option>
            </select>
            <button type="submit">Enviar</button>
        </form>
    </section>

    <footer>
        <p>Con amor, [Nombres de los novios]</p>
    </footer>
</body>
</html>
body {
    font-family: 'Arial', sans-serif;
    background-color: #f9f9f9;
    color: #4a4a4a;
    margin: 0;
    padding: 0;
}

header {
    text-align: center;
    background-color: #ffffff;
    padding: 20px;
    border-bottom: 5px solid #6b8e23;
}

header h1 {
    font-size: 2.5em;
    color: #6b8e23;
    margin: 0;
}

header h2 {
    font-size: 2em;
    color: #4a4a4a;
}

header p {
    font-size: 1.2em;
    color: #8b8b8b;
}

.details {
    text-align: center;
    margin: 20px;
}

.details h3 {
    font-size: 1.8em;
    color: #6b8e23;
}

.map iframe {
    margin-top: 20px;
    border: 5px solid #6b8e23;
}

.music {
    text-align: center;
    margin: 20px;
}

.rsvp {
    text-align: center;
    margin: 20px;
}

form {
    display: inline-block;
    text-align: left;
}

label {
    display: block;
    font-size: 1.1em;
    color: #6b8e23;
    margin-bottom: 5px;
}

input, select, button {
    width: 100%;
    padding: 10px;
    margin-bottom: 15px;
    border-radius: 5px;
    border: 1px solid #6b8e23;
}

button {
    background-color: #6b8e23;
    color: white;
    cursor: pointer;
}

footer {
    text-align: center;
    background-color: #ffffff;
    padding: 10px;
    border-top: 5px solid #6b8e23;
}
