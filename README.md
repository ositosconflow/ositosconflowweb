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
            /* ¡IMPORTANTE! REEMPLAZA ESTA URL CON TU IMAGEN REAL DE FONDO DE ALTA CALIDAD */
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
                ¡Mantente atento a nuestras redes sociales para más detalles y confirmaciones!
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

        <div class="bg-blue-100 rounded-2xl shadow-xl p-8 md:p-12 max-w-4xl w-full text-center mt-10">
            <h2 class="text-4xl md:text-5xl font-extrabold text-blue-700 mb-6 leading-tight">
                <span class="block text-blue-500">¡Interactúa con la Familia!</span>
                <span class="block text-blue-700 text-2xl md:text-3xl mt-2">Tu voz es importante</span>
            </h2>
            <p class="text-lg md:text-xl text-gray-700 mb-8 max-w-2xl mx-auto">
                Queremos que te sientas parte activa de Ositos con Flow. Aquí te decimos cómo puedes interactuar y hacer que tu presencia se sienta:
            </p>
            <div class="grid grid-cols-1 md:grid-cols-2 gap-6 text-left">
                <div class="bg-white p-6 rounded-xl shadow-md border-l-4 border-blue-500">
                    <h3 class="text-2xl font-bold text-gray-800 mb-2">En los Streams</h3>
                    <p class="text-gray-700">Participa en el chat, envía regalos, haz preguntas y comparte tus comentarios. ¡Tu interacción anima a nuestros emisores!</p>
                </div>
                <div class="bg-white p-6 rounded-xl shadow-md border-l-4 border-blue-500">
                    <h3 class="text-2xl font-bold text-gray-800 mb-2">Grupos de Chat</h3>
                    <p class="text-gray-700">Únete a nuestros grupos de chat en Bigo Live o en otras plataformas (si las tenemos) para conversar, compartir memes y conocer a otros ositos.</p>
                </div>
                <div class="bg-white p-6 rounded-xl shadow-md border-l-4 border-blue-500">
                    <h3 class="text-2xl font-bold text-gray-800 mb-2">Sugerencias y Feedback</h3>
                    <p class="text-gray-700">¿Tienes ideas para streams, eventos o mejoras? ¡Nos encanta escucharte! Envíanos tus sugerencias a través de nuestros canales oficiales.</p>
                </div>
                <div class="bg-white p-6 rounded-xl shadow-md border-l-4 border-blue-500">
                    <h3 class="text-2xl font-bold text-gray-800 mb-2">Eventos y Retos</h3>
                    <p class="text-gray-700">Participa en los retos y eventos que organizamos. ¡Es una excelente forma de ganar premios y divertirte con la familia!</p>
                </div>
            </div>
        </div>

        <div class="bg-purple-100 rounded-2xl shadow-xl p-8 md:p-12 max-w-4xl w-full text-center mt-10">
            <h2 class="text-4xl md:text-5xl font-extrabold text-purple-700 mb-6 leading-tight">
                <span class="block text-purple-500">Espacio con Flow</span>
                <span class="block text-purple-700 text-2xl md:text-3xl mt-2">¡Conexión y Comunidad!</span>
            </h2>
            <p class="text-lg md:text-xl text-gray-700 mb-8 max-w-2xl mx-auto">
                Este es nuestro rincón especial para relajarnos, conversar y conectar. ¡Siéntete libre de compartir y divertirte!
            </p>

            <div class="mb-8">
                <h3 class="text-2xl font-bold text-gray-800 mb-4">Chat de la Cueva</h3>
                <div id="chat-messages" class="text-left">
                    </div>
                <input type="text" id="chat-username" placeholder="Tu nombre de osito" class="w-full p-3 rounded-lg border border-gray-300 mb-2 focus:outline-none focus:ring-2 focus:ring-purple-500">
                <textarea id="chat-input" class="w-full p-3 rounded-lg border border-gray-300 mb-2 resize-y focus:outline-none focus:ring-2 focus:ring-purple-500" rows="3" placeholder="Escribe tu mensaje aquí..."></textarea>
                <button id="send-chat" class="bg-purple-500 hover:bg-purple-600 text-white font-bold py-3 px-6 rounded-full shadow-lg transition-all duration-300 transform hover:-translate-y-1">
                    Enviar Mensaje
                </button>
            </div>

            <div class="mt-8">
                <h3 class="text-2xl font-bold text-gray-800 mb-4">¡Conéctate con Nosotros!</h3>
                <p class="text-gray-700 text-lg mb-6">
                    Aquí tienes algunas formas de interactuar directamente con la familia Ositos con Flow:
                </p>
                <div class="flex flex-col sm:flex-row justify-center items-center gap-4">
                    <button id="copy-family-id" class="bg-pink-500 hover:bg-pink-600 text-white font-bold py-3 px-6 rounded-full shadow-lg transition-all duration-300 transform hover:-translate-y-1">
                        Copiar ID de Familia
                    </button>
                    <a href="https://www.bigo.tv/" target="_blank" class="inline-block bg-blue-500 hover:bg-blue-600 text-white font-bold py-3 px-6 rounded-full shadow-lg transition-all duration-300 transform hover:-translate-y-1">
                        Visita Bigo Live
                    </a>
                </div>
                <p id="copy-message" class="text-green-600 mt-4 hidden">¡ID de Familia copiado!</p>

                <div class="mt-8">
                    <h3 class="text-2xl font-bold text-gray-800 mb-4">Comparte el Flow</h3>
                    <div class="flex justify-center gap-4">
                        <a href="https://www.facebook.com/sharer/sharer.php?u=TU_URL_DE_LA_PAGINA" target="_blank" class="bg-blue-700 hover:bg-blue-800 text-white p-3 rounded-full shadow-md transition-colors duration-300">Facebook</a>
                        <a href="https://twitter.com/intent/tweet?url=TU_URL_DE_LA_PAGINA&text=Únete a la familia Ositos con Flow en Bigo Live!" target="_blank" class="bg-blue-400 hover:bg-blue-500 text-white p-3 rounded-full shadow-md transition-colors duration-300">Twitter</a>
                        <a href="https://www.instagram.com/" target="_blank" class="bg-pink-600 hover:bg-pink-700 text-white p-3 rounded-full shadow-md transition-colors duration-300">Instagram</a>
                    </div>
                    <p class="text-sm text-gray-500 mt-4">
                        (Recuerda reemplazar "TU_URL_DE_LA_PAGINA" con la URL real de esta página para compartir correctamente.)
                    </p>
                </div>
            </div>
        </div>

        <div class="bg-red-100 rounded-2xl shadow-xl p-8 md:p-12 max-w-4xl w-full text-center mt-10">
            <h2 class="text-4xl md:text-5xl font-extrabold text-red-700 mb-6 leading-tight">
                <span class="block text-red-500">Reglas de la Familia</span>
                <span class="block text-red-700 text-2xl md:text-3xl mt-2">Convivencia en Armonía</span>
            </h2>
            <p class="text-lg md:text-xl text-gray-700 mb-8 max-w-2xl mx-auto">
                Para mantener un ambiente positivo y respetuoso en Ositos con Flow, te pedimos que sigas estas sencillas reglas:
            </p>
            <ul class="list-decimal list-inside text-left text-gray-700 text-lg md:text-xl mx-auto max-w-xl mb-8">
                <li class="mb-2">**Respeto:** Trata a todos los miembros y emisores con respeto, sin importar sus opiniones o diferencias.</li>
                <li class="mb-2">**No al Odio:** No se tolerará ningún tipo de discurso de odio, acoso o discriminación.</li>
                <li class="mb-2">**Positivismo:** Fomenta un ambiente positivo y de apoyo. ¡Somos una familia!</li>
                <li class="mb-2">**Privacidad:** Respeta la privacidad de los demás. No compartas información personal sin consentimiento.</li>
                <li class="mb-2">**Contenido Apropiado:** Asegúrate de que tu contenido y comentarios sean apropiados para todas las edades.</li>
                <li class="mb-2">**No Spam:** Evita el spam o la promoción no autorizada de otros canales o productos.</li>
                <li>**Disfruta:** Lo más importante es que te diviertas y disfrutes siendo parte de Ositos con Flow.</li>
            </ul>
            <p class="text-md text-gray-600 mt-6">
                El incumplimiento de estas reglas puede resultar en la expulsión de la familia.
            </p>
        </div>

        <div class="bg-gray-100 rounded-2xl shadow-xl p-8 md:p-12 max-w-4xl w-full text-center mt-10">
            <h2 class="text-4xl md:text-5xl font-extrabold text-gray-700 mb-6 leading-tight">
                <span class="block text-gray-500">Información Importante</span>
                <span class="block text-gray-700 text-2xl md:text-3xl mt-2">Sobre la Familia y Bigo Live</span>
            </h2>
            <p class="text-lg md:text-xl text-gray-700 mb-8 max-w-2xl mx-auto">
                En Ositos con Flow, nos esforzamos por crear un ambiente seguro y divertido para todos. Aquí algunos puntos clave:
            </p>
            <ul class="list-disc list-inside text-left text-gray-700 text-lg md:text-xl mx-auto max-w-xl mb-8">
                <li class="mb-2">**Sobre la Familia:** Somos una comunidad de apoyo mutuo, dedicada a la diversión y el crecimiento en Bigo Live. Valoramos la amistad, el respeto y la buena onda entre todos nuestros miembros.</li>
                <li class="mb-2">**Bigo Live:** Es una plataforma global de streaming en vivo. Es importante recordar que, según sus términos de servicio, **Bigo Live está destinado a usuarios mayores de 18 años.** Te pedimos que respetes esta normativa al unirte y participar en nuestra familia.</li>
                <li>**Privacidad:** Tu privacidad es importante para nosotros. Consulta las políticas de privacidad de Bigo Live para más información sobre el manejo de tus datos.</li>
            </ul>
        </div>

        <div class="bg-purple-100 rounded-xl p-6 shadow-inner mt-10">
            <h2 class="text-3xl md:text-4xl font-bold text-purple-600 mb-4">¿Listo para unirte al Flow?</h2>
            <p class="text-lg text-gray-800 mb-6">
                Encuéntranos en Bigo Live buscando "Ositos con Flow" o el ID de nuestra familia. ¡Te esperamos con los brazos abiertos (y las patitas listas para bailar)!
            </p>
            <a href="https://www.bigo.tv/" target="_blank" class="inline-block bg-pink-500 hover:bg-pink-600 text-white font-bold py-3 px-8 rounded-full shadow-lg transition-all duration-300 transform hover:-translate-y-1">
                ¡Síguenos en Bigo Live!
            </a>
        </div>

    </div>
