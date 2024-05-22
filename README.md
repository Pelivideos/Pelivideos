<!DOCTYPE html>
<html>

<head>
    <meta charset="UTF-8">
    <meta name="viewport" id="viewport" content="width=device-width, initial-scale=1">
    <link rel="icon" href="https://i.ibb.co/jy8K3ZB/pelivideo-aplifan.png" type="image/x-icon">
    <title>PELIVIDEOS</title>
</head>

<body bgcolor="#71c9ce">
    <h3 style="color: blue;">¡¡¡PROMOCION ESPECIAL!!!</h3>
    <font size="1" color="red" face="Arial">ACCESO A TODO NUESTRO CONIDO DIGITAL. MUSICA, PELICULAS, SERIES, CURSOS, CORTOMETRAJES, DOCUMENTALES Y MUCHO MAS </font>
    <h2 style="color: green;">100 días por solo $99.⁰⁰ </h2>
     <iframe allow="fullscreen;autoplay" allowfullscreen height="280" src="https://streamable.com/e/sztf8j?autoplay=1" width="180" style="border:none;"></iframe> 
    <button id="aceptarBtn">ir al sitio Pelivideos </button>
    <script>
        document.getElementById('aceptarBtn').style.display = 'block';

        function redirigir() {
            window.location.href = "https://example.com/";
        }
        document.getElementById('aceptarBtn').addEventListener('click', redirigir);
    </script>
    <h6>Por favor espera</h6>
    <h4 id="countdown">30</h4>
    <script>
        let timeLeft = 30

        function updateCountdown() {
            timeLeft--;
            document.getElementById('countdown').textContent = timeLeft;
            if (timeLeft === 0) {
                clearInterval(this);
                alert('¡Cuenta regresiva finalizada!');
                window.location.href = "https://www.google.com/";
            }
        }
        setInterval(updateCountdown, 1000);
    </script>

<a href="https://www.contadorvisitasgratis.com" title="contador de visitas wordpress"><img src="https://counter4.optistats.ovh/private/contadorvisitasgratis.php?c=kdejhw4qfkzmle9wrp356lw6h21bqg32" border="0" title="contador de visitas wordpress" alt="contador de visitas wordpress"></a>
