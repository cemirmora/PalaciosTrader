<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Palacios Trader</title>
    <!-- Enlace a Tailwind CSS CDN -->
    <script src="https://cdn.tailwindcss.com"></script>
    <style>
        /* Configuración de la fuente Inter */
        @import url('https://fonts.googleapis.com/css2?family=Inter:wght@300;400;500;600;700&display=swap');
        body {
            font-family: 'Inter', sans-serif;
            background-color: #121212; /* Negro muy oscuro para el fondo */
            color: #e0e0e0; /* Gris claro para el texto principal */
        }
        /* Colores personalizados para el azul neón y su hover */
        .text-neon-blue { color: #00FFFF; } /* Azul neón (Cyan) */
        .bg-neon-blue { background-color: #00FFFF; }
        .hover\:bg-neon-blue-darker:hover { background-color: #00BFFF; } /* Azul cielo profundo para hover */
        .border-neon-blue { border-color: #00FFFF; }

        /* Estilos adicionales para una apariencia más web */
        .section-container {
            max-width: 1200px; /* Ancho máximo para el contenido */
            margin-left: auto;
            margin-right: auto;
            padding-left: 1.5rem; /* px-6 */
            padding-right: 1.5rem; /* px-6 */
        }
    </style>
</head>
<body class="antialiased">

    <!-- Hero Section / Encabezado principal -->
    <section class="bg-gray-900 py-20 text-center border-b border-gray-800">
        <div class="section-container">
            <h1 class="text-6xl font-extrabold text-neon-blue mb-6 tracking-wide">
                Palacios Trader
            </h1>
            <p class="mt-4 text-2xl text-gray-300 max-w-2xl mx-auto leading-relaxed">
                Señales de trading para traders inteligentes. Únete al canal privado y actúa con confianza en el mercado.
            </p>
            <!-- Botón de Llamada a la Acción -->
            <a href="https://t.me/PalaciosTrader" target="_blank" rel="noopener noreferrer"
               class="mt-10 inline-flex items-center justify-center px-10 py-5 border border-transparent text-lg font-medium rounded-full shadow-lg text-gray-900 bg-neon-blue hover:bg-neon-blue-darker focus:outline-none focus:ring-2 focus:ring-offset-2 focus:ring-neon-blue transition duration-300 ease-in-out transform hover:scale-105">
                Solicitar acceso
            </a>
        </div>
    </section>

    <!-- Sección de Características de la Suscripción -->
    <section class="py-16 bg-gray-900 border-b border-gray-800">
        <div class="section-container">
            <h2 class="text-4xl font-bold text-gray-100 text-center mb-12">
                ¿Qué incluye tu suscripción?
            </h2>
            <div class="grid grid-cols-1 md:grid-cols-2 lg:grid-cols-3 gap-8">
                <div class="flex flex-col items-center bg-gray-800 p-6 rounded-xl shadow-lg border border-gray-700 hover:border-neon-blue transition duration-300 ease-in-out">
                    <h3 class="text-xl font-semibold text-gray-100 mb-2">Señales Claras</h3>
                    <p class="text-gray-300 text-center">Entradas con puntos claros, TP1, TP2, TP3 y SL definidos.</p>
                </div>
                <div class="flex flex-col items-center bg-gray-800 p-6 rounded-xl shadow-lg border border-gray-700 hover:border-neon-blue transition duration-300 ease-in-out">
                    <h3 class="text-xl font-semibold text-gray-100 mb-2">Canal Exclusivo</h3>
                    <p class="text-gray-300 text-center">Acceso a nuestro canal privado exclusivo en Telegram.</p>
                </div>
                <div class="flex flex-col items-center bg-gray-800 p-6 rounded-xl shadow-lg border border-gray-700 hover:border-neon-blue transition duration-300 ease-in-out">
                    <h3 class="text-xl font-semibold text-gray-100 mb-2">Revisión Semanal</h3>
                    <p class="text-gray-300 text-center">Análisis y revisión detallada de los resultados cada semana.</p>
                </div>
                <div class="flex flex-col items-center bg-gray-800 p-6 rounded-xl shadow-lg border border-gray-700 hover:border-neon-blue transition duration-300 ease-in-out">
                    <h3 class="text-xl font-semibold text-gray-100 mb-2">Comunidad Enfocada</h3>
                    <p class="text-gray-300 text-center">Forma parte de una comunidad seria y enfocada en el trading.</p>
                </div>
                <div class="flex flex-col items-center bg-gray-800 p-6 rounded-xl shadow-lg border border-gray-700 hover:border-neon-blue transition duration-300 ease-in-out">
                    <h3 class="text-xl font-semibold text-gray-100 mb-2">Soporte Continuo</h3>
                    <p class="text-gray-300 text-center">Resuelve tus dudas y recibe soporte directo del equipo.</p>
                </div>
            </div>
        </div>
    </section>

    <!-- Sección de Precios -->
    <section class="py-16 bg-gray-950 border-b border-gray-800 text-center">
        <div class="section-container">
            <h2 class="text-4xl font-bold text-gray-100 mb-12">Precio</h2>
            <div class="bg-gray-800 p-8 rounded-xl shadow-xl inline-block border-2 border-neon-blue">
                <p class="text-6xl font-extrabold text-neon-blue mb-4">
                    $20 USD
                </p>
                <p class="text-2xl text-gray-200 mt-2">
                    mensual
                </p>
                <p class="text-lg text-gray-400 mt-4 max-w-sm mx-auto">
                    Acceso completo al canal privado de señales, revisiones y comunidad.
                </p>
            </div>
        </div>
    </section>

    <!-- Sección de Opiniones de Miembros -->
    <section class="py-16 bg-gray-900 border-b border-gray-800">
        <div class="section-container">
            <h2 class="text-4xl font-bold text-gray-100 text-center mb-12">Opiniones de miembros</h2>
            <div class="grid grid-cols-1 md:grid-cols-2 gap-8">
                <div class="bg-gray-800 p-6 rounded-xl shadow-lg border border-gray-700">
                    <p class="text-gray-300 italic mb-4">
                        "Un servicio excelente! Las señales son claras y me han ayudado a operar con más confianza. La comunidad es un gran apoyo."
                    </p>
                    <p class="text-gray-400 font-semibold text-right">- Miembro Satisfecho</p>
                </div>
                <div class="bg-gray-800 p-6 rounded-xl shadow-lg border border-gray-700">
                    <p class="text-gray-300 italic mb-4">
                        "La revisión semanal de resultados es clave para entender el mercado. Palacios Trader es profesional y confiable."
                    </p>
                    <p class="text-gray-400 font-semibold text-right">- Trader Pro</p>
                </div>
            </div>
        </div>
    </section>

    <!-- Sección de Contacto -->
    <section class="py-16 bg-gray-950 text-center">
        <div class="section-container">
            <h2 class="text-4xl font-bold text-gray-100 mb-12">
                ¿Dudas o quieres saber más?
            </h2>
            <div class="space-y-6 text-xl">
                <p class="flex flex-col sm:flex-row items-center justify-center text-gray-200">
                    <span class="text-neon-blue mr-0 sm:mr-3 mb-2 sm:mb-0 text-3xl">📬</span>
                    Contáctame en Telegram:
                    <a href="https://t.me/PalaciosTrader" target="_blank" rel="noopener noreferrer"
                       class="ml-0 sm:ml-2 text-neon-blue hover:text-blue-400 font-semibold transition duration-200 ease-in-out">
                        @PalaciosTrader
                    </a>
                </p>
                <p class="flex flex-col sm:flex-row items-center justify-center text-gray-200">
                    <span class="text-neon-blue mr-0 sm:mr-3 mb-2 sm:mb-0 text-3xl">🌐</span>
                    Sitio oficial:
                    <a href="https://www.palaciostrader.com" target="_blank" rel="noopener noreferrer"
                       class="ml-0 sm:ml-2 text-neon-blue hover:text-blue-400 font-semibold transition duration-200 ease-in-out">
                        www.palaciostrader.com
                    </a>
                </p>
            </div>
        </div>
    </section>

    <!-- Pie de Página -->
    <footer class="py-8 bg-gray-900 border-t border-gray-800 text-center text-sm text-gray-600">
        <div class="section-container">
            <p>© 2025 Palacios Trader. Todos los derechos reservados.</p>
            <p class="mt-2 text-xs">Este servicio no constituye asesoría financiera.</p>
        </div>
    </footer>
</body>
</html>
