<div class="container">
    <!-- Barra lateral -->
    <div class="sidebar">
        <img src="../HVconfoto/img/foto.jpg" alt="Foto de perfil">
        <h2>Sindy Fonte</h2>
        <div class="contact-info">  
            <p><strong><i class="fas fa-envelope"></i> Correo:</strong> <a href="https://mail.google.com/mail/?view=cm&fs=1&to=sindy.melft05@gmail.com" target="_blank">Sindy.melft05@gmail.com</a></p>  
            <p><strong><i class="fas fa-phone"></i> Teléfono:</strong> <a href="https://wa.me/593981135571" target="_blank">+593 981135571</a></p>  
        </div>   
        <br>
        <div class="links">  
            <h3>Links Externos</h3>  
            <a href="HOJA_DE_VIDA/Hoja_de_vida.pdf"><i class="fas fa-file-pdf"></i> Hoja de vida PDF</a>  
            <a href="https://www.linkedin.com/in/sindy-fonte-mt98113/" target="_blank">  
                <i class="fab fa-linkedin"></i> LinkedIn  
            </a>  
        </div>  
    </div>

    <!-- Sección Principal -->
    <div class="main-content">
        <div class="title">HOJA DE VIDA </div>

        <div class="bio">
            <h2>Biografía</h2>
            <p>Ingeniera en Logística y Transporte graduada de la Universidad Politécnica Estatal del Carchi, con sólida formación en gestión logística, análisis de datos, y manejo de KPIs. Experta en herramientas analíticas como Power BI y en la implementación de software ERP, como Odoo, entre otros, para optimizar procesos y mejorar la eficiencia operativa. Proactiva, con habilidades en trabajo en equipo y resolución de problemas....</p>
        </div>
        <div class="interests">  
            <h2>Intereses Profesionales</h2>  
            <ul>  
                <li><i class="fas fa-cogs"></i> Consultoría en Optimización de procesos Logísticos</li>  
                <li><i class="fas fa-shopping-cart"></i> Gestión de Compras y Abastecimiento</li>  
                <li><i class="fas fa-pencil-ruler"></i> Diseño asistido por computadora CAD</li>  
                <li><i class="fas fa-truck"></i> Transporte y Operaciones</li>  
                <li><i class="fas fa-box"></i> Logística y cadena de suministro</li>  
                <li><i class="fas fa-robot"></i> Automatización y Digitalización Logística</li>  
                <li><i class="fas fa-archive"></i> Gestión de inventario y Transporte en producciones Audiovisuales</li>  
            </ul>  
        </div>  

        <div class="portfolio">
            <h2>Portafolio de Proyectos</h2>
            <div class="tabs">
                <div class="tab-btn" onclick="showTab('cursos', this)">Cursos</div>
                <div class="tab-btn" onclick="showTab('investigacion', this)">Proyectos Investigación</div>
                <div class="tab-btn" onclick="showTab('colaboraciones', this)">Colaboraciones</div>
            </div>

            <!-- Cursos-->
            <div id="cursos" class="tab-content">
                <div class="year" onclick="toggleYear('c2024')">2024</div>
                <div id="c2024" class="year-content">
                    <ul>
                        <li>Título: SUFICIENCIA EN EL IDIOMA INGLÉS-B1. . Duración: 2 semestres . Cliente o empresa: La Universidad Politécnica Estatal del Carchi - UPEC. </li>
                    </ul>
                </div>
                <div class="year" onclick="toggleYear('c2021')">2021</div>
                <div id="c2021" class="year-content">
                    <ul>
                        <li>Título: IMPORTACIONES Y EXPORTACIONES. . Duración: 30 de Agosto al 10 de septiembre . Cliente o empresa: CECAMI. </li>
                    </ul>
                </div>
                <div class="year" onclick="toggleYear('c2019')">2019</div>
                <div id="c2019" class="year-content">
                    <ul>
                        <li>Título: CONDUCTOR PROFESIONAL, Tipo C. Duración: 6 meses . Cliente o empresa: UNIVERSIDAD DE OTAVALO. </li>
                    </ul>
                </div>
            </div>

            <!-- Proyectos Investigación -->
            <div id="investigacion" class="tab-content">
                <div class="year" onclick="toggleYear('pi2025')">2025</div>
                <div id="pi2025" class="year-content">
                    <ul>
                        <li>Título del proyecto: Logística de Abastecimiento y Gestión de Inventarios en la Agencia de Publicidad Maki Creativa. Rol: Investigador y Desarrollador. Duración: 2 semestres. Cliente o empresa: La Universidad Politécnica Estatal del Carchi - UPEC</li>
                    </ul>
                </div>
            </div>

            <!-- Colaboraciones-->
            <div id="colaboraciones" class="tab-content">
                <div class="year" onclick="toggleYear('col2024')">2024</div>
                <div id="col2024" class="year-content">
                    <ul>
                        <li>Título del proyecto: Diseño de rutas para el mejoramiento del servicio de transporte comercial, modalidad escolar e institucional con las operadoras domiciliadas en la ciudad de tulcán. Rol: Investigador y Desarrollador. Duración: 140 horas. Cliente o empresa: MSC. Diego Almeida</li>
                    </ul>
                </div>
                <div class="year" onclick="toggleYear('col2023')">2023</div>
                <div id="col2023" class="year-content">
                    <ul>
                        <li>Título del proyecto: Levantamiento de procesos y procedimientos institucionales. Rol: Desarrollador. Duración: 240 horas. Cliente o empresa: Unidad de Aseguramiento de la Calidad - UPEC</li>
                    </ul>
                </div>
            </div>
        </div>
    </div>

    <!-- Archivos CSS -->
    <link rel="stylesheet" href="../HVconfoto/css/main.css" />
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.4.2/css/all.min.css">
    
<!-- Scripts -->
<script src="../HVconfoto/js/main.js"></script>
<script src="https://kit.fontawesome.com/a076d05399.js" crossorigin="anonymous"></script>
</body>
</html>
