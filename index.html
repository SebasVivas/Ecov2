<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Ecosistema de Aplicaciones Empresariales - Microsoft 365</title>
    <script src="https://cdn.tailwindcss.com"></script>
    <style>
        @import url('https://fonts.googleapis.com/css2?family=Inter:wght@300;400;500;600;700&display=swap');
        body { font-family: 'Inter', sans-serif; }
        .gradient-bg { background: #1e41ff; }
        .card-hover { transition: all 0.3s ease; }
        .card-hover:hover { transform: translateY(-5px); box-shadow: 0 20px 40px rgba(30, 65, 255, 0.15); }
        .search-highlight { background-color: rgba(30, 65, 255, 0.1); }
        .category-tab { transition: all 0.3s ease; }
        .category-tab.active { background: #1e41ff; color: white; }
    </style>
</head>
<body class="bg-gray-50">
    <!-- Header -->
<header class="gradient-bg text-white py-8">
    <div class="container mx-auto px-6">
        <div class="flex items-center justify-center gap-4">
            <!-- Logo -->
            

            <!-- Título -->
            <div class="text-left">
                <h1 class="text-4xl font-bold mb-2">Ecosistema de Aplicaciones Empresariales</h1>
                <p class="text-xl opacity-90 max-w-4xl">
                    Benká creó un ecosistema de aplicaciones pensado para facilitar el trabajo de todo el equipo, integrando las herramientas más útiles en un solo lugar.
                </p>
            </div>
        </div>
    </div>
</header>


    <!-- Search and Filter Section -->
    <div class="overflow-x-auto whitespace-nowrap">
        <div class="flex gap-2 w-max">
            <div class="flex flex-col md:flex-row gap-4 items-center">
                <div class="flex-1">
                    <input 
                        type="text" 
                        id="searchInput" 
                        placeholder="Buscar" 
                        class="w-full px-4 py-3 border border-gray-300 rounded-lg focus:ring-2 focus:ring-[#1e41ff] focus:border-transparent"
                    >
                </div>
                <div class="flex gap-2">
                    <button class="category-tab active px-3 py-1.5 rounded-lg font-medium" data-category="all">
                        Todas
                    </button>
                    <button class="category-tab px-3 py-1.5 rounded-lg font-medium bg-gray-100 text-gray-700" data-category="Kit basico Benka">
                        Kit basico Benka
                    </button>
                    <button class="category-tab px-3 py-1.5 rounded-lg font-medium bg-gray-100 text-gray-700" data-category="Ofimática">
                        Ofimática
                    </button>
                    <button class="category-tab px-3 py-1.5 rounded-lg font-medium bg-gray-100 text-gray-700" data-category="Colaboración">
                        Colaboración 
                    </button>
                    </button>
                    <button class="category-tab px-3 py-1.5 rounded-lg font-medium bg-gray-100 text-gray-700" data-category="Notas">
                        Notas 
                    </button>
                    <button class="category-tab px-3 py-1.5 rounded-lg font-medium bg-gray-100 text-gray-700" data-category="Tareas">
                        Tareas 
                    </button>
                    <button class="category-tab px-3 py-1.5 rounded-lg font-medium bg-gray-100 text-gray-700" data-category="Automatización">
                        Automatización
                    </button>
                    <button class="category-tab px-3 py-1.5 rounded-lg font-medium bg-gray-100 text-gray-700" data-category="Multimedia">
                        Multimedia
                    </button>
                    <button class="category-tab px-3 py-1.5 rounded-lg font-medium bg-gray-100 text-gray-700" data-category="Proyectos">
                        Proyectos
                    </button>
                    <button class="category-tab px-3 py-1.5 rounded-lg font-medium bg-gray-100 text-gray-700" data-category="Comunicación">
                        Comunicación
                    </button>
                    <button class="category-tab px-3 py-1.5 rounded-lg font-medium bg-gray-100 text-gray-700" data-category="Bienestar">
                        Bienestar
                    </button>
                </div>
            </div>
        </div>

        <!-- Applications Grid -->
        <div id="applicationsGrid" class="grid grid-cols-1 md:grid-cols-2 lg:grid-cols-3 xl:grid-cols-4 gap-6">
            <!-- Microsoft 365 Applications -->
        </div>

        <!-- No Results Message -->
        <div id="noResults" class="hidden text-center py-12">
            <div class="text-gray-400 text-6xl mb-4">🔍</div>
            <h3 class="text-xl font-semibold text-gray-600 mb-2">No se encontraron resultados</h3>
            <p class="text-gray-500">Intenta con otros términos de búsqueda</p>
        </div>
    </div>

    <!-- Application Modal -->
    <div id="appModal" class="hidden fixed inset-0 bg-black bg-opacity-50 z-50 flex items-center justify-center p-4">
        <div class="bg-white rounded-xl max-w-2xl w-full max-h-[90vh] overflow-y-auto">
            <div class="p-6">
                <div class="flex justify-between items-start mb-4">
                    <div class="flex items-center gap-3">
                        <span id="modalIcon" class="text-3xl"></span>
                        <h2 id="modalTitle" class="text-2xl font-bold text-gray-800"></h2>
                    </div>
                    <button id="closeModal" class="text-gray-400 hover:text-gray-600 text-2xl">&times;</button>
                </div>
                <div id="modalCategory" class="inline-block px-3 py-1 rounded-full text-sm font-medium mb-4"></div>
                <p id="modalDescription" class="text-gray-600 leading-relaxed mb-6"></p>
                <div id="modalFeatures" class="space-y-2"></div>
            </div>
        </div>
    </div>

    <script>
const applications = [
{ name: "Bookings", icon: "", category: ["Ofimática", "Kit basico Benka"], description: "Gestión de citas y reservas de manera eficiente. Ideal para agendar reuniones internas o con clientes.", features: ["Programación automática", "Recordatorios por email", "Integración con Outlook", "Personalización de servicios"] },{ name: "Calendario", icon: "", category: "Ofimática", description: "Organiza tu tiempo y eventos personales y corporativos en sincronía con Outlook.", features: ["Sincronización multiplataforma", "Recordatorios inteligentes", "Compartir calendarios", "Integración con Teams"] },
    { name: "Clipchamp", icon: "", category: "Multimedia", description: "Editor de video en línea fácil de usar para crear contenido multimedia profesional.", features: ["Edición sin instalación", "Plantillas profesionales", "Efectos y transiciones", "Exportación HD"] },
    { name: "Connections", icon: "", category: "Comunicación", description: "Acceso centralizado a noticias, recursos y herramientas personalizadas para los colaboradores.", features: ["Portal personalizado", "Noticias corporativas", "Recursos centralizados", "Dashboard personalizable"] },
    { name: "Contactos", icon: "", category: "Comunicación", description: "Gestión y administración de contactos internos y externos.", features: ["Sincronización automática", "Grupos de contactos", "Integración con Outlook", "Búsqueda avanzada"] },
    { name: "Engage", icon: "", category: "Comunicación", description: "Conecta y compromete a tu equipo con eventos, encuestas y comunicación interna.", features: ["Encuestas interactivas", "Eventos corporativos", "Comunicación bidireccional", "Analytics de engagement"] },
    { name: "Excel", icon: "", category: ["Ofimática", "Kit basico Benka"], description: "Hoja de cálculo poderosa para análisis, presupuestos, modelos financieros y reportes.", features: ["Fórmulas avanzadas", "Tablas dinámicas", "Colaboración en tiempo real", "Macros y automatización"] },
    { name: "Forms", icon: "", category: "Tareas", description: "Crea encuestas, cuestionarios y formularios con resultados en tiempo real.", features: ["Diseño intuitivo", "Lógica condicional", "Análisis automático", "Integración con Excel"] },
    { name: "Insights", icon: "", category: "Bienestar", description: "Mejora el bienestar y productividad de los empleados con Viva Insights.", features: ["Métricas de productividad", "Análisis de bienestar", "Recomendaciones personalizadas", "Dashboards ejecutivos"] },
    { name: "Kaizala", icon: "", category: "Comunicación", description: "Aplicación de mensajería móvil segura para la comunicación empresarial.", features: ["Mensajería segura", "Grupos de trabajo", "Acciones personalizadas", "Integración móvil"] },
    { name: "Learning", icon: "", category: "Bienestar", description: "Plataforma de formación continua integrada con Viva Learning.", features: ["Cursos personalizados", "Tracking de progreso", "Certificaciones", "Contenido curado"] },
    { name: "Lists", icon: "", category: "Tareas", description: "Gestión y seguimiento de datos estructurados dentro de equipos o proyectos.", features: ["Listas personalizables", "Automatización de flujos", "Vistas múltiples", "Colaboración en equipo"] },
    { name: "Loop", icon: "", category: "Colaboración", description: "Herramienta colaborativa para planificación y desarrollo conjunto en tiempo real.", features: ["Colaboración en tiempo real", "Componentes reutilizables", "Sincronización automática", "Integración con Office"] },
    { name: "OneDrive", icon: "", category: "Ofimática", description: "Almacenamiento en la nube seguro para archivos personales y compartidos.", features: ["Sincronización automática", "Compartir seguro", "Versionado de archivos", "Acceso offline"] },
    { name: "OneNote", icon: "", category: "Notas", description: "Bloc de notas digital para capturar ideas, hacer resúmenes y colaborar.", features: ["Organización flexible", "Búsqueda en texto", "Colaboración en tiempo real", "Sincronización multiplataforma"] },
    { name: "Outlook", icon: "", category: ["Ofimática", "Kit basico Benka"], description: "Correo electrónico corporativo con calendario, tareas y contactos integrados.", features: ["Gestión de email avanzada", "Calendario integrado", "Tareas y recordatorios", "Reglas automáticas"] },
    { name: "Planner", icon: "", category: ["Tareas", "Kit basico Benka"], description: "Planificación de tareas, asignación de actividades y seguimiento de proyectos.", features: ["Tableros Kanban", "Asignación de tareas", "Seguimiento de progreso", "Integración con Teams"] },
    { name: "Power Apps", icon: "", category: "Automatización", description: "Crea aplicaciones personalizadas sin necesidad de programación avanzada.", features: ["Desarrollo sin código", "Conectores predefinidos", "Aplicaciones móviles", "Integración con datos"] },
    { name: "Power Automate", icon: "", category: "Automatización", description: "Automatización de flujos de trabajo entre aplicaciones y servicios.", features: ["Flujos automatizados", "Conectores múltiples", "Triggers inteligentes", "Aprobaciones digitales"] },
    { name: "Power BI", icon: "", category: "Automatización", description: "Visualización de datos e inteligencia empresarial mediante dashboards interactivos.", features: ["Dashboards interactivos", "Análisis en tiempo real", "Conectores de datos", "Reportes automáticos"] },
    { name: "Power Pages", icon: "", category: "Automatización", description: "Creación de sitios web empresariales internos o externos sin código.", features: ["Desarrollo sin código", "Plantillas profesionales", "Integración con datos", "Responsive design"] },
    { name: "PowerPoint", icon: "", category: ["Ofimática", "Kit basico Benka"], description: "Herramienta para crear presentaciones visuales y profesionales.", features: ["Plantillas profesionales", "Animaciones avanzadas", "Colaboración en tiempo real", "Presentación en línea"] },
    { name: "Project", icon: "", category: "Proyectos", description: "Gestión completa de proyectos, asignación de recursos y seguimiento de avances.", features: ["Diagramas de Gantt", "Gestión de recursos", "Seguimiento de costos", "Reportes ejecutivos"] },
    { name: "SharePoint", icon: "", category: ["Colaboración", "Kit basico Benka"], description: "Portal de intranet para compartir documentos, procesos y recursos internos.", features: ["Sitios de equipo", "Gestión documental", "Flujos de trabajo", "Búsqueda empresarial"] },
    { name: "Stream", icon: "", category: "Multimedia", description: "Plataforma para subir, compartir y ver videos corporativos o formativos.", features: ["Streaming seguro", "Transcripciones automáticas", "Analytics de visualización", "Integración con Teams"] },
    { name: "Sway", icon: "", category: "Notas", description: "Presentaciones interactivas y documentos visuales dinámicos.", features: ["Diseño adaptativo", "Contenido interactivo", "Plantillas modernas", "Compartir fácil"] },
    { name: "Teams", icon: "", category: ["Colaboración", "Kit basico Benka"], description: "Centro de colaboración: chat, videollamadas, tareas, archivos y más.", features: ["Chat y videollamadas", "Canales organizados", "Integración de apps", "Colaboración en archivos"] },
    { name: "To Do", icon: "", category: "Tareas", description: "Lista de tareas personales con integración a Outlook y Planner.", features: ["Listas inteligentes", "Recordatorios", "Sincronización con Outlook", "Colaboración en tareas"] },
    { name: "Visio", icon: "", category: "Proyectos", description: "Diagramas y flujos de trabajo visuales para representar procesos.", features: ["Diagramas profesionales", "Plantillas especializadas", "Colaboración en tiempo real", "Integración con datos"] },
    { name: "Viva", icon: "", category: "Bienestar", description: "Ecosistema de bienestar, cultura y desarrollo profesional para empleados.", features: ["Insights de productividad", "Learning integrado", "Conexiones de equipo", "Temas corporativos"] },
    { name: "Whiteboard", icon: "", category: "Notas", description: "Pizarra digital colaborativa para sesiones creativas y lluvias de ideas.", features: ["Colaboración en tiempo real", "Herramientas de dibujo", "Plantillas creativas", "Integración con Teams"] },
    { name: "Word", icon: "", category: ["Ofimática", "Kit basico Benka"], description: "Procesador de texto para redacción, colaboración y edición en línea.", features: ["Edición colaborativa", "Comentarios y revisiones", "Plantillas profesionales", "Integración con referencias"] },
    // External Tools
    { name: "Jira", icon: "", category: ["Proyectos", "Kit basico Benka"], description: "Gestión ágil de proyectos, tareas y seguimiento de bugs. Ideal para equipos técnicos.", features: ["Metodologías ágiles", "Seguimiento de bugs", "Tableros Scrum/Kanban", "Reportes avanzados"] },
    { name: "Odoo", icon: "", category: "Proyectos", description: "Odoo es un ERP (Enterprise Resource Planning) de código abierto que centraliza todos los procesos empresariales en una sola plataforma. Permite gestionar operaciones clave como ventas, finanzas, inventarios, compras, recursos humanos y más. Su arquitectura modular permite adaptarse fácilmente a las necesidades de empresas de cualquier tamaño.", features: ["CRM integrado para gestionar oportunidades y relaciones con clientes", "Módulo de ventas y cotizaciones automatizadas", "Contabilidad completa con reportes financieros y conciliaciones bancarias", "Gestión de inventarios y almacenes con trazabilidad de productos", "Compras automatizadas y gestión de proveedores", "Módulos de Recursos Humanos: nómina, asistencia, evaluaciones", "Sitio web y eCommerce totalmente integrados", "Aplicaciones móviles y personalización mediante desarrollo propio", "Marketplace con cientos de módulos adicionales", "Interfaz intuitiva y completamente web"] },
    { name: "Siigo", icon: "", category: "Tareas", description: "Plataforma contable y administrativa para pymes con facturación electrónica integrada.", features: ["Facturación electrónica", "Contabilidad NIIF", "Nómina integrada", "Reportes fiscales"] },
    { name: "Notion", icon: "", category: ["Notas", "Kit basico Benka"], description: "Espacio de trabajo todo-en-uno: notas, bases de datos, tareas, wikis y proyectos.", features: ["Bases de datos relacionales", "Wikis colaborativos", "Gestión de tareas", "Plantillas personalizables"] },
    { name: "ChatGPT", icon: "", category: "Automatización", description: "Asistente inteligente para redacción, generación de ideas, automatización de contenido y más.", features: ["Generación de contenido", "Asistencia en redacción", "Análisis de datos", "Automatización inteligente"] },
    { name: "Perplexity", icon: "", category: ["Automatización", "Kit basico Benka"], description: "Plataforma de inteligencia artificial especializada en búsqueda web y generación de respuestas precisas y actualizadas, ideal para investigación y análisis en tiempo real.", features: ["Respuestas con citas y fuentes", "Interfaz conversacional", "Actualización en tiempo real", "Multimodalidad", "Modos especializados para investigaciones", "Gestión de proyectos y colaboración", "Planes gratuitos y de pago"] }
];


        let filteredApps = [...applications];
        let currentCategory = 'all';

        function renderApplications() {
            const grid = document.getElementById('applicationsGrid');
            const noResults = document.getElementById('noResults');
            
            if (filteredApps.length === 0) {
                grid.innerHTML = '';
                noResults.classList.remove('hidden');
                return;
            }
            
            noResults.classList.add('hidden');
            
            grid.innerHTML = filteredApps.map(app => `
                <div class="bg-white rounded-xl shadow-md card-hover cursor-pointer p-6 border border-gray-100" onclick="openModal('${app.name}')">
                    <div class="flex items-center gap-3 mb-4">
                        <img src="${app.icon}" alt="${app.name}" class="w-8 h-8" onerror="this.style.display='none'; this.nextElementSibling.style.display='inline';">
                        <span class="text-3xl hidden"></span>
                        <div>
                            <h3 class="font-semibold text-gray-800 text-lg">${app.name}</h3>
                            <span class="text-xs px-2 py-1 rounded-full ${app.category === 'microsoft' ? 'bg-blue-50 text-[#1e41ff]' : 'bg-gray-100 text-gray-700'}">
                                ${app.category === 'microsoft' ? 'Microsoft 365' : 'App'}
                            </span>
                        </div>
                    </div>
                    <p class="text-gray-600 text-sm leading-relaxed line-clamp-3">${app.description}</p>
                    <div class="mt-4 flex items-center text-[#1e41ff] text-sm font-medium">
                        Ver detalles →
                    </div>
                </div>
            `).join('');
        }

function filterApplications() {
    const searchTerm = document.getElementById('searchInput').value.toLowerCase();
    
    filteredApps = applications.filter(app => {
        const matchesSearch = app.name.toLowerCase().includes(searchTerm) || 
                              app.description.toLowerCase().includes(searchTerm) ||
                              app.features.some(feature => feature.toLowerCase().includes(searchTerm));
        
        const matchesCategory = currentCategory === 'all' || 
            (Array.isArray(app.category) ? app.category.includes(currentCategory) : app.category === currentCategory);
        
        return matchesSearch && matchesCategory;
    });
    
    renderApplications();
}

        function openModal(appName) {
            const app = applications.find(a => a.name === appName);
            if (!app) return;
            
            const modalIcon = document.getElementById('modalIcon');
            modalIcon.innerHTML = `<img src="${app.icon}" alt="${app.name}" class="w-8 h-8" onerror="this.style.display='none'; this.innerHTML='📱';">`;
            document.getElementById('modalTitle').textContent = app.name;
            document.getElementById('modalDescription').textContent = app.description;
            
            const categoryBadge = document.getElementById('modalCategory');
            categoryBadge.textContent = app.category === 'microsoft' ? 'Microsoft 365' : 'Herramienta Externa';
            categoryBadge.className = `inline-block px-3 py-1 rounded-full text-sm font-medium mb-4 ${
                app.category === 'microsoft' ? 'bg-blue-50 text-[#1e41ff]' : 'bg-gray-100 text-gray-700'
            }`;
            
            document.getElementById('modalFeatures').innerHTML = `
                <h4 class="font-semibold text-gray-800 mb-3">Características principales:</h4>
                <ul class="space-y-2">
                    ${app.features.map(feature => `
                        <li class="flex items-center gap-2">
                            <span class="text-[#1e41ff]">✓</span>
                            <span class="text-gray-700">${feature}</span>
                        </li>
                    `).join('')}
                </ul>
            `;
            
            document.getElementById('appModal').classList.remove('hidden');
        }

        function closeModal() {
            document.getElementById('appModal').classList.add('hidden');
        }

        // Event Listeners
        document.getElementById('searchInput').addEventListener('input', filterApplications);
        document.getElementById('closeModal').addEventListener('click', closeModal);

        document.querySelectorAll('.category-tab').forEach(tab => {
            tab.addEventListener('click', (e) => {
                document.querySelectorAll('.category-tab').forEach(t => {
                    t.classList.remove('active');
                    t.classList.add('bg-gray-100', 'text-gray-700');
                });
                
                e.target.classList.add('active');
                e.target.classList.remove('bg-gray-100', 'text-gray-700');
                
                currentCategory = e.target.dataset.category;
                filterApplications();
            });
        });

        // Close modal when clicking outside
        document.getElementById('appModal').addEventListener('click', (e) => {
            if (e.target.id === 'appModal') {
                closeModal();
            }
        });

        // Initialize
        renderApplications();
    </script>
<script>(function(){function c(){var b=a.contentDocument||a.contentWindow.document;if(b){var d=b.createElement('script');d.innerHTML="window.__CF$cv$params={r:'963c319142b5370c',t:'MTc1MzI4NDM1OS4wMDAwMDA='};var a=document.createElement('script');a.nonce='';a.src='/cdn-cgi/challenge-platform/scripts/jsd/main.js';document.getElementsByTagName('head')[0].appendChild(a);";b.getElementsByTagName('head')[0].appendChild(d)}}if(document.body){var a=document.createElement('iframe');a.height=1;a.width=1;a.style.position='absolute';a.style.top=0;a.style.left=0;a.style.border='none';a.style.visibility='hidden';document.body.appendChild(a);if('loading'!==document.readyState)c();else if(window.addEventListener)document.addEventListener('DOMContentLoaded',c);else{var e=document.onreadystatechange||function(){};document.onreadystatechange=function(b){e(b);'loading'!==document.readyState&&(document.onreadystatechange=e,c())}}}})();</script></body>
</html>

