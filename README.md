# ositosconflowweb
Página web para la familia Ositos con Flow en Bigo Live
<head>
    <!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Ositos con Flow - Tu Familia en Bigo Live</title>
    <script src="https://cdn.tailwindcss.com"></script>
    <style>
        /* Fuente Inter para una apariencia limpia y moderna */
        body {
            font-family: 'Inter', sans-serif;
            /* Fondo temático de ositos con flow */
        ![image](https://github.com/user-attachments/assets/de75dbf6-0ecc-484b-880f-cb5710bd9946)

            background-image: url('https://placehold.co/1920x1080/FFD1DC/6B46C1?text=Ositos+con+Flow+Background');
            background-size: cover; /* Cubre todo el área */
            background-position: center; /* Centra la imagen de fondo */
            background-attachment: fixed; /* Hace que el fondo sea fijo al hacer scroll */
            background-color: #f0f4f8; /* Color de fallback si la imagen no carga */
        }
        /* Estilos específicos para el área de mensajes del chat */
        #chat-messages {
            height: 200px; /* Altura fija para el área de mensajes */
            overflow-y: auto; /* Permite scroll vertical si hay muchos mensajes */
            border: 1px solid #e2e8f0; /* Borde suave */
            padding: 1rem; /* Espaciado interno */
            border-radius: 0.5rem; /* Bordes redondeados */
            background-color: #f8fafc; /* Color de fondo claro */
            margin-bottom: 1rem; /* Margen inferior */
        }
        /* Estilo para cada mensaje individual en el chat */
        .chat-message {
            margin-bottom: 0.5rem; /* Espacio entre mensajes */
        }
        /* Estilo para el nombre de usuario en el chat */
        .chat-message strong {
            color: #6d28d9; /* Color morado para el nombre de usuario */
        }
    </style>
</head>
<body class="min-h-screen flex flex-col items-center justify-center p-4">

    <div class="bg-white rounded-2xl shadow-xl p-8 md:p-12 max-w-4xl w-full text-center my-8 transform transition-all duration-300 hover:scale-105">

        <h1 class="text-5xl md:text-6xl font-extrabold text-purple-700 mb-6 leading-tight">
            <span class="block text-pink-500">Ositos con Flow</span>
            <span class="block text-purple-700 text-3xl md:text-4xl mt-2">¡Tu Familia en Bigo Live!</span>
        </h1>

        <p class="text-lg md:text-xl text-gray-700 mb-8 max-w-2xl mx-auto">
            ¡Bienvenidos a la familia más tierna y con más ritmo de Bigo Live! Somos los Ositos con Flow, un grupo de amigos y streamers que comparten risas, buena onda y momentos inolvidables. Únete a nuestra cueva de diversión y sé parte de esta increíble comunidad.
        </p>

        <div class="grid grid-cols-1 sm:grid-cols-2 lg:grid-cols-3 gap-6 mb-10">
            <div class="bg-blue-100 p-4 rounded-xl shadow-md transform hover:scale-105 transition-transform">
                <img src="https://placehold.co/400x300/87CEEB/FFFFFF?text=Osito+Cool" alt="Osito Cool" class="w-full h-48 object-cover rounded-lg mb-4">
                <p class="text-md font-semibold text-blue-800">¡Siempre con la mejor actitud!</p>
            </div>
            <div class="bg-green-100 p-4 rounded-xl shadow-md transform hover:scale-105 transition-transform">
                <img src="https://placehold.co/400x300/90EE90/FFFFFF?text=Osita+Divertida" alt="Osita Divertida" class="w-full h-48 object-cover rounded-lg mb-4">
                <p class="text-md font-semibold text-green-800">Risas garantizadas en cada stream.</p>
            </div>
            <div class="bg-red-100 p-4 rounded-xl shadow-md transform hover:scale-105 transition-transform">
                <img src="https://placehold.co/400x300/F08080/FFFFFF?text=Osito+Amigable" alt="Osito Amigable" class="w-full h-48 object-cover rounded-lg mb-4">
                <p class="text-md font-semibold text-red-800">¡Únete a nuestra manada!</p>
            </div>
        </div>

        <div class="bg-yellow-100 rounded-2xl shadow-xl p-8 md:p-12 max-w-4xl w-full text-center mt-10">
            <h2 class="text-4xl md:text-5xl font-extrabold text-yellow-700 mb-6 leading-tight">
                <span class="block text-yellow-500">Eventos Familiar</span>
                <span class="block text-yellow-700 text-2xl md:text-3xl mt-2">¡No te pierdas la diversión!</span>
            </h2>
            <p class="text-lg md:text-xl text-gray-700 mb-8 max-w-2xl mx-auto">
                Aquí te mantendremos al tanto de todas nuestras reuniones especiales, streams temáticos y actividades exclusivas para la familia Ositos con Flow. ¡Marca tu calendario!
            </p>

            <div class="grid grid-cols-1 md:grid-cols-2 gap-6 text-left">
                <div class="bg-white p-6 rounded-xl shadow-md border-l-4 border-yellow-500">
                    <h3 class="text-2xl font-bold text-gray-800 mb-2">Noche de Juegos con Ositos</h3>
                    <p class="text-gray-600 mb-2">**Fecha:** 15 de Junio, 20:00 (GMT-3)</p>
                    <p class="text-gray-600 mb-2">**Lugar:** Canal de Bigo Live de [Nombre del Anfitrión]</p>
                    <p class="text-gray-700">¡Prepárate para una noche llena de risas y desafíos con tus juegos favoritos! Habrá premios sorpresa para los ganadores.</p>
                </div>
                <div class="bg-white p-6 rounded-xl shadow-md border-l-4 border-yellow-500">
                    <h3 class="text-2xl font-bold text-gray-800 mb-2">Stream de Preguntas y Respuestas con la Familia</h3>
                    <p class="text-gray-600 mb-2">**Fecha:** 22 de Junio, 19:00 (GMT-3)</p>
                    <p class="text-gray-600 mb-2">**Lugar:** Canal oficial de Ositos con Flow en Bigo Live</p>
                    <p class="text-gray-700">Envía tus preguntas y conoce más a fondo a los miembros de la familia. ¡Será una noche de confesiones y mucha buena onda!</p>
                </div>
                </div>
            <p class="text-md text-gray-600 mt-6">
                ¡Mantente atento a nuestras redes sociales para más detalles y confirmaciones!ositos con flow
            </p>
        </div>

        <div class="bg-green-100 rounded-2xl shadow-xl p-8 md:p-12 max-w-4xl w-full text-center mt-10">
            <h2 class="text-4xl md:text-5xl font-extrabold text-green-700 mb-6 leading-tight">
                <span class="block text-green-500">¡Conviértete en Emisor Oficial!</span>
                <span class="block text-green-700 text-2xl md:text-3xl mt-2">Lleva tu Flow al siguiente nivel</span>
            </h2>
            <p class="text-lg md:text-xl text-gray-700 mb-8 max-w-2xl mx-auto">
                ¿Sueñas con brillar en Bigo Live y ser reconocido por tu talento? En Ositos con Flow te apoyamos para que te conviertas en un emisor oficial. ¡Descubre los beneficios y cómo podemos ayudarte a crecer!
            </p>
            <ul class="list-disc list-inside text-left text-gray-700 text-lg md:text-xl mx-auto max-w-xl mb-8">
                <li class="mb-2">Acceso a programas exclusivos de Bigo Live.</li>
                <li class="mb-2">Mayores oportunidades de monetización.</li>
                <li class="mb-2">Soporte y mentoría de la familia Ositos con Flow.</li>
                <li class="mb-2">Visibilidad amplificada dentro de la plataforma.</li>
                <li>Participación en eventos especiales para emisores.</li>
            </ul>
            <a href="#" class="inline-block bg-green-500 hover:bg-green-600 text-white font-bold py-3 px-8 rounded-full shadow-lg transition-all duration-300 transform hover:-translate-y-1">
                ¡Quiero ser Emisor Oficial!
            </a>
        </div>

        <div class="bg-blue-100 rounded-2xl shadow-xl p-8 md:p-12 max-w-4xl w-full text-center mt
