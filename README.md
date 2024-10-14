<body>
    <h1>Concesionario Esquina del Automotor - Proyecto Web</h1>    
    <h2>Índice</h2>
    <ul>
        <li><a href="#descripción">Descripción</a></li>
        <li><a href="#estructura-del-proyecto">Estructura del Proyecto</a></li>
        <li><a href="#uso">Uso</a></li>
        <li><a href="#estilos-y-diseño">Estilos y Diseño</a></li>
        <li><a href="#mejoras">Mejoras</a></li>
        <li><a href="#con-más-tiempo">Con más tiempo</a></li>
    </ul>
    <h2 id="descripción">Descripción</h2>
    <p>El sitio web está compuesto por tres pantallas principales:</p>
    <ul>
        <li><strong>Home</strong>: Página principal que presenta el concesionario y muestra una selección de autos destacados.</li>
        <li><strong>Sign In</strong>: Página de inicio de sesión para que los usuarios puedan acceder a su cuenta.</li>
        <li><strong>Sign Up</strong>: Página de registro donde los nuevos usuarios pueden crear una cuenta.</li>
    </ul>
    <p>El objetivo principal del proyecto es crear una interfaz limpia y funcional que se ajuste a dispositivos de distintos tamaños, utilizando únicamente HTML y CSS.</p>
    <h2 id="estructura-del-proyecto">Estructura del Proyecto</h2>
    <pre>
📁 proyecto-web-concesionario
│
├── 📁 css
│   ├── index.css             # Estilos generales del sitio
│   └── styleForm.css         # Estilos específicos para los formularios
│
├── 📁 pages
│   ├── signIn.html           # Página de inicio de sesión
│   └── signUp.html           # Página de registro
│
├── index.html                # Página principal del sitio
└── README.html               # Documentación del proyecto
    </pre>
    <h2 id="uso">Uso</h2>
    <p>El sitio web permite navegar entre las distintas páginas utilizando el menú superior. Las funcionalidades clave incluyen:</p>
    <ul>
        <li><strong>Home</strong>: Presenta el concesionario y algunos vehículos destacados.</li>
        <li><strong>Sign In</strong>: Permite que los usuarios ingresen sus credenciales para iniciar sesión.</li>
        <li><strong>Sign Up</strong>: Proporciona un formulario para que los nuevos usuarios se registren.</li>
    </ul>
    <h2 id="estilos-y-diseño">Estilos y Diseño</h2>
    <p>El sitio utiliza una paleta de colores sencilla con dos variables principales en el archivo CSS: <code>--primary</code> y <code>--secondary</code>. Se implementa una tipografía sans-serif para lograr una estética moderna y limpia.</p>
    <p>El diseño del sitio es totalmente responsivo, utilizando flexbox para ajustar los elementos a diferentes tamaños de pantalla.</p>
    <h2 id="mejoras">¿Hay alguna mejora que pueda hacer en su envío?</h2>
    <p>Una mejora posible sería implementar un sistema de validación más avanzado para los formularios de <strong>Sign In</strong> y <strong>Sign Up</strong>. Actualmente, los formularios usan la validación básica de HTML5, pero agregar validación personalizada con JavaScript mejoraría la experiencia del usuario.</p>
    <p>Además, se podría añadir un diseño más complejo y visualmente atractivo en la página de inicio, tal vez incluyendo un carrusel de imágenes de autos destacados o más contenido multimedia.</p>
    <h2 id="con-más-tiempo">¿Qué haría de manera diferente si se le asignara más tiempo?</h2>
    <p>Si tuviera más tiempo, consideraría agregar las siguientes características y mejoras:</p>
    <ul>
        <li><strong>Interactividad con JavaScript</strong>: Implementaría lógica adicional para mejorar la funcionalidad del sitio, como un sistema de autenticación básico o la capacidad de filtrar autos por características en la página de inicio.</li>
        <li><strong>Optimización de imágenes</strong>: Las imágenes de autos podrían optimizarse mejor para reducir tiempos de carga, usando técnicas como el lazy loading o diferentes versiones para dispositivos móviles.</li>
        <li><strong>Más contenido</strong>: Podría agregar una sección con reseñas de clientes, más detalles sobre los autos en venta, y tal vez un blog para mantener a los usuarios informados sobre tendencias automotrices.</li>
    </ul>
    <p>Las imágenes de autos se obtuvieron de sitios web gratuitos como <strong>Pixabay</strong> y <strong>Freepik</strong>.</p>
    <p>Este proyecto fue realizado como parte de un curso de desarrollo web.</p>
</body>
</html>
