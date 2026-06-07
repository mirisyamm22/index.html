<!DOCTYPE html>
<html lang="es" class="scroll-smooth">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>La Crisis del Agua - Proyecto Escolar Informativo</title>
    <!-- Tailwind CSS para el diseño rápido, responsivo y moderno -->
    <script src="https://cdn.tailwindcss.com"></script>
    <script>
        tailwind.config = {
            theme: {
                extend: {
                    colors: {
                        agua: {
                            50: '#f0f9ff',
                            100: '#e0f2fe',
                            200: '#bae6fd',
                            300: '#7dd3fc',
                            400: '#38bdf8',
                            500: '#0ea5e9',
                            600: '#0284c7',
                            700: '#0369a1',
                            800: '#075985',
                            900: '#0c4a6e',
                            950: '#082f49',
                        },
                        mar: {
                            50: '#f4fbfd',
                            100: '#e0f7fa',
                            200: '#b2ebf2',
                            300: '#80deea',
                            400: '#26c6da',
                            500: '#00bcd4',
                            600: '#00acc1',
                            700: '#0097a7',
                            800: '#00838f',
                            900: '#006064',
                        }
                    },
                    fontFamily: {
                        sans: ['Inter', 'system-ui', '-apple-system', 'sans-serif'],
                    }
                }
            }
        }
    </script>
    <link href="https://fonts.googleapis.com/css2?family=Inter:wght@300;400;500;600;700;800&display=swap" rel="stylesheet">
    <style>
        /* Estilos personalizados para animaciones y elementos visuales específicos */
        .glass-header {
            background-color: rgba(12, 74, 110, 0.85);
            backdrop-filter: blur(12px);
            -webkit-backdrop-filter: blur(12px);
        }
        .hero-gradient {
            background: linear-gradient(to bottom, rgba(8, 47, 73, 0.4), rgba(8, 47, 73, 0.9)), url('https://images.unsplash.com/photo-1518156677180-95a2893f3e9f?auto=format&fit=crop&w=1920&q=80') no-repeat center center;
            background-size: cover;
        }
        .bg-pattern {
            background-color: #f8fafc;
            background-image: radial-gradient(#bae6fd 0.75px, transparent 0.75px), radial-gradient(#bae6fd 0.75px, #f8fafc 0.75px);
            background-size: 30px 30px;
            background-position: 0 0, 15px 15px;
        }
        .text-shadow-custom {
            text-shadow: 2px 2px 8px rgba(0, 0, 0, 0.7);
        }
    </style>
</head>
<body class="bg-slate-50 text-slate-800 font-sans leading-relaxed">

    <!-- MENÚ DE NAVEGACIÓN FIJO -->
    <header class="fixed top-0 left-0 w-full z-50 glass-header border-b border-agua-800/50 shadow-lg transition-all duration-300">
        <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8">
            <div class="flex items-center justify-between h-20">
                <div class="flex items-center space-x-3">
                    <!-- Icono de gota SVG -->
                    <svg class="h-9 w-9 text-agua-400 fill-current" viewBox="0 0 24 24">
                        <path d="M12,2.69C12,2.69 19,10.15 19,15A7,7 0 0,1 12,22A7,7 0 0,1 5,15C5,10.15 12,2.69 12,2.69Z" />
                    </svg>
                    <div>
                        <span class="text-white font-extrabold text-xl tracking-tight block">ALERTA AZUL</span>
                        <span class="text-agua-300 text-xs font-semibold tracking-widest block -mt-1 uppercase">Proyecto Escolar</span>
                    </div>
                </div>
                <!-- Menú Desktop -->
                <nav class="hidden lg:flex space-x-1 xl:space-x-2">
                    <a href="#inicio" class="text-slate-100 hover:text-white hover:bg-agua-900/50 px-3 py-2 rounded-md text-sm font-medium transition-colors">Inicio</a>
                    <a href="#que-es" class="text-slate-100 hover:text-white hover:bg-agua-900/50 px-3 py-2 rounded-md text-sm font-medium transition-colors">¿Qué es?</a>
                    <a href="#causas" class="text-slate-100 hover:text-white hover:bg-agua-900/50 px-3 py-2 rounded-md text-sm font-medium transition-colors">Causas</a>
                    <a href="#consecuencias" class="text-slate-100 hover:text-white hover:bg-agua-900/50 px-3 py-2 rounded-md text-sm font-medium transition-colors">Consecuencias</a>
                    <a href="#soluciones" class="text-slate-100 hover:text-white hover:bg-agua-900/50 px-3 py-2 rounded-md text-sm font-medium transition-colors">Soluciones</a>
                    <a href="#galeria" class="text-slate-100 hover:text-white hover:bg-agua-900/50 px-3 py-2 rounded-md text-sm font-medium transition-colors">Galería</a>
                    <a href="#infografia" class="text-slate-100 hover:text-white hover:bg-agua-900/50 px-3 py-2 rounded-md text-sm font-medium transition-colors">Infografía</a>
                    <a href="#cartel" class="text-slate-100 hover:text-white hover:bg-agua-900/50 px-3 py-2 rounded-md text-sm font-medium transition-colors">Cartel</a>
                    <a href="#juego" class="text-slate-100 hover:text-white hover:bg-agua-900/50 px-3 py-2 rounded-md text-sm font-medium transition-colors">Juego Interactivo</a>
                    <a href="#reflexion" class="text-slate-100 hover:text-white hover:bg-agua-900/50 px-3 py-2 rounded-md text-sm font-medium transition-colors">Reflexión</a>
                </nav>
                <!-- Botón de Menú Móvil -->
                <div class="lg:hidden">
                    <button id="mobile-menu-btn" class="text-agua-200 hover:text-white focus:outline-none p-2 rounded-md hover:bg-agua-900" aria-label="Abrir menú">
                        <svg class="h-6 w-6" fill="none" stroke="currentColor" viewBox="0 0 24 24">
                            <path id="menu-icon" stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M4 6h16M4 12h16M4 18h16" />
                        </svg>
                    </button>
                </div>
            </div>
        </div>
        <!-- Menú Móvil Desplegable -->
        <div id="mobile-menu" class="hidden lg:hidden bg-agua-950 border-t border-agua-900 px-4 pt-2 pb-6 space-y-1">
            <a href="#inicio" class="block text-slate-100 hover:bg-agua-900 px-3 py-2.5 rounded-md text-base font-medium">Inicio</a>
            <a href="#que-es" class="block text-slate-100 hover:bg-agua-900 px-3 py-2.5 rounded-md text-base font-medium">¿Qué es la problemática?</a>
            <a href="#causas" class="block text-slate-100 hover:bg-agua-900 px-3 py-2.5 rounded-md text-base font-medium">Causas</a>
            <a href="#consecuencias" class="block text-slate-100 hover:bg-agua-900 px-3 py-2.5 rounded-md text-base font-medium">Consecuencias</a>
            <a href="#soluciones" class="block text-slate-100 hover:bg-agua-900 px-3 py-2.5 rounded-md text-base font-medium">Soluciones</a>
            <a href="#galeria" class="block text-slate-100 hover:bg-agua-900 px-3 py-2.5 rounded-md text-base font-medium">Galería de Imágenes</a>
            <a href="#infografia" class="block text-slate-100 hover:bg-agua-900 px-3 py-2.5 rounded-md text-base font-medium">Infografía</a>
            <a href="#cartel" class="block text-slate-100 hover:bg-agua-900 px-3 py-2.5 rounded-md text-base font-medium">Cartel Digital</a>
            <a href="#juego" class="block text-slate-100 hover:bg-agua-900 px-3 py-2.5 rounded-md text-base font-medium">Juego Interactivo</a>
            <a href="#reflexion" class="block text-slate-100 hover:bg-agua-900 px-3 py-2.5 rounded-md text-base font-medium">Reflexión Final</a>
        </div>
    </header>

    <!-- PORTADA / HERO SECTION -->
    <section id="inicio" class="hero-gradient min-h-screen flex items-center justify-center pt-20 relative text-white">
        <div class="absolute inset-0 bg-gradient-to-t from-agua-950/90 via-slate-950/40 to-slate-900/30"></div>
        <div class="relative z-10 max-w-5xl mx-auto px-4 text-center">
            <span class="inline-block bg-agua-500/20 text-agua-300 border border-agua-400/40 px-4 py-1.5 rounded-full text-xs sm:text-sm font-semibold tracking-wider uppercase mb-6 backdrop-blur-sm animate-pulse">
                Acción por el Planeta · Meta de Desarrollo Sostenible 6
            </span>
            <h1 class="text-4xl sm:text-6xl lg:text-7xl font-extrabold tracking-tight mb-6 leading-tight text-shadow-custom">
                La Crisis del Agua y la <span class="text-agua-400">Contaminación</span>
            </h1>
            <p class="text-lg sm:text-2xl text-slate-200 max-w-3xl mx-auto mb-10 leading-relaxed font-light text-shadow-custom">
                Un análisis profundo sobre el agotamiento y la degradación del recurso más valioso de nuestro planeta, enfocado en los desafíos urgentes que enfrenta México.
            </p>
            <div class="flex flex-col sm:flex-row justify-center items-center gap-4">
                <a href="#que-es" class="w-full sm:w-auto bg-agua-500 hover:bg-agua-600 text-white font-semibold px-8 py-4 rounded-xl shadow-lg hover:shadow-agua-500/30 transition-all duration-300 transform hover:-translate-y-0.5 text-center">
                    Comenzar Lectura
                </a>
                <a href="#juego" class="w-full sm:w-auto bg-white/10 hover:bg-white/20 text-white font-semibold px-8 py-4 rounded-xl border border-white/20 hover:border-white/40 backdrop-blur-sm transition-all duration-300 text-center">
                    ¡Jugar al Guardián!
                </a>
            </div>
        </div>
        <!-- Indicador para bajar -->
        <div class="absolute bottom-8 left-1/2 -translate-x-1/2 flex flex-col items-center animate-bounce">
            <span class="text-slate-400 text-xs tracking-wider mb-2">Desplázate hacia abajo</span>
            <svg class="w-6 h-6 text-agua-400" fill="none" stroke="currentColor" viewBox="0 0 24 24">
                <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M19 14l-7 7m0 0l-7-7m7 7V3" />
            </svg>
        </div>
    </section>

    <!-- ¿QUÉ ES LA PROBLEMÁTICA? -->
    <section id="que-es" class="py-24 bg-white scroll-mt-20">
        <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8">
            <div class="lg:text-center mb-16">
                <h2 class="text-base text-agua-600 font-semibold tracking-wide uppercase">Definición General</h2>
                <p class="mt-2 text-3xl leading-8 font-extrabold tracking-tight text-slate-900 sm:text-4xl">
                    ¿Qué es la crisis del agua?
                </p>
                <div class="w-24 h-1 bg-agua-500 lg:mx-auto mt-4 rounded-full"></div>
            </div>

            <div class="grid grid-cols-1 lg:grid-cols-12 gap-12 items-center">
                <div class="lg:col-span-7 space-y-6">
                    <p class="text-lg text-slate-700 leading-relaxed">
                        La <strong>crisis del agua</strong> es un fenómeno global caracterizado por la escasez física de agua limpia y potable, el estrés hídrico extremo provocado por una sobreexplotación desmedida, y la acelerada degradación ecológica de las fuentes de agua debido a descargas domésticas, industriales y agrícolas no tratadas. No se trata simplemente de la falta del recurso, sino de la deficiente gestión técnica, social y económica del mismo.
                    </p>
                    <div class="bg-agua-50 border-l-4 border-agua-500 p-6 rounded-r-xl">
                        <h4 class="font-bold text-agua-950 text-lg mb-2">¿Por qué afecta gravemente a México?</h4>
                        <p class="text-slate-700 text-sm md:text-base">
                            México vive una alarmante dualidad geográfica y climática. Mientras que el norte y centro del territorio son semiáridos y concentran la mayor cantidad de la población y del PIB, el sur goza de abundancia de agua pero con menor desarrollo económico e infraestructura. El país enfrenta serios desafíos: más de la mitad del territorio nacional reporta sequías severas, extremas o excepcionales, y grandes urbes como la Ciudad de México o Monterrey enfrentan de manera reiterada el riesgo del temido "Día Cero", el momento en el que el suministro libre de agua se vuelva inviable para la población.
                        </p>
                    </div>
                    <p class="text-slate-700">
                        La contaminación de los ríos de México es otra faceta crítica. Alrededor del 70% de los cuerpos de agua dulce del país presentan algún grado de contaminación orgánica o química, lo que restringe dramáticamente su aprovechamiento y pone en constante riesgo sanitario a las comunidades rurales y suburbanas colindantes.
                    </p>
                </div>
                <!-- Columna de imagen / Datos destacados -->
                <div class="lg:col-span-5">
                    <div class="relative bg-gradient-to-br from-agua-100 to-white rounded-3xl p-8 border border-agua-200/60 shadow-xl overflow-hidden">
                        <!-- Círculos de adorno -->
                        <div class="absolute -right-16 -top-16 w-32 h-32 bg-agua-300/20 rounded-full blur-xl"></div>
                        <div class="absolute -left-16 -bottom-16 w-32 h-32 bg-agua-200/30 rounded-full blur-xl"></div>
                        
                        <h3 class="font-bold text-xl text-slate-900 mb-6 flex items-center gap-2">
                            <span class="p-2 bg-agua-500 text-white rounded-lg block">
                                <svg class="w-5 h-5 fill-current" viewBox="0 0 24 24"><path d="M13,9H11V7H13M13,17H11V11H13M12,2A10,10 0 0,0 2,12A10,10 0 0,0 12,22A10,10 0 0,0 22,12A10,10 0 0,0 12,2Z" /></svg>
                            </span>
                            Datos Clave de México
                        </h3>
                        <ul class="space-y-6 relative z-10">
                            <li class="flex items-start gap-4">
                                <div class="text-3xl font-extrabold text-agua-600 shrink-0">77%</div>
                                <div>
                                    <h4 class="font-bold text-slate-800 text-sm">Población vulnerable</h4>
                                    <p class="text-xs text-slate-600">De los mexicanos habitan en las regiones del norte y centro, las zonas más áridas y propensas al desabasto.</p>
                                </div>
                            </li>
                            <li class="flex items-start gap-4">
                                <div class="text-3xl font-extrabold text-agua-600 shrink-0">157</div>
                                <div>
                                    <h4 class="font-bold text-slate-800 text-sm">Acuíferos sobreexplotados</h4>
                                    <p class="text-xs text-slate-600">De los 653 acuíferos principales del territorio ya no disponen de volumen de agua para concesiones.</p>
                                </div>
                            </li>
                            <li class="flex items-start gap-4">
                                <div class="text-3xl font-extrabold text-agua-600 shrink-0">60%</div>
                                <div>
                                    <h4 class="font-bold text-slate-800 text-sm">Pérdidas por fugas</h4>
                                    <p class="text-xs text-slate-600">Del agua potable suministrada a la red de distribución urbana en México se pierde en fugas antes de llegar al hogar.</p>
                                </div>
                            </li>
                        </ul>
                    </div>
                </div>
            </div>

            <!-- Botones de Navegación Rápida -->
            <div class="mt-16 flex justify-between items-center border-t border-slate-100 pt-8">
                <a href="#inicio" class="text-sm font-semibold text-slate-500 hover:text-agua-600 flex items-center gap-1">
                    &larr; Volver al inicio
                </a>
                <a href="#causas" class="bg-agua-50 hover:bg-agua-100 text-agua-700 font-semibold px-5 py-2.5 rounded-lg text-sm transition-colors flex items-center gap-1">
                    Ver Causas de la Crisis &rarr;
                </a>
            </div>
        </div>
    </section>

    <!-- SECCIÓN CAUSAS -->
    <section id="causas" class="py-24 bg-pattern scroll-mt-20">
        <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8">
            <div class="lg:text-center mb-16">
                <h2 class="text-base text-agua-600 font-semibold tracking-wide uppercase">Factores Desencadenantes</h2>
                <p class="mt-2 text-3xl leading-8 font-extrabold tracking-tight text-slate-900 sm:text-4xl">
                    Causas Principales del Desastre Hídrico
                </p>
                <div class="w-24 h-1 bg-agua-500 lg:mx-auto mt-4 rounded-full"></div>
            </div>

            <div class="grid grid-cols-1 md:grid-cols-2 gap-8">
                <!-- Causa 1: Contaminación de ríos -->
                <div class="bg-white rounded-2xl p-8 border border-agua-100 shadow-md hover:shadow-xl transition-shadow duration-300 flex flex-col justify-between">
                    <div>
                        <div class="w-12 h-12 bg-red-100 rounded-xl flex items-center justify-center text-red-500 mb-6">
                            <!-- Icono de río/onda contaminado -->
                            <svg class="w-6 h-6 fill-current" viewBox="0 0 24 24"><path d="M12,2A10,10 0 0,0 2,12A10,10 0 0,0 12,22A10,10 0 0,0 22,12A10,10 0 0,0 12,2M12,4A8,8 0 0,1 20,12A8,8 0 0,1 12,20A8,8 0 0,1 4,12A8,8 0 0,1 12,4M11,6V13H13V11H15V9H13V6H11M11,15V17H13V15H11Z" /></svg>
                        </div>
                        <h3 class="text-xl font-bold text-slate-900 mb-3">1. Contaminación de Ríos y Cuerpos de Agua</h3>
                        <p class="text-slate-600 text-sm md:text-base leading-relaxed">
                            Gran parte de las industrias y municipios vierten sus residuos químicos y aguas fecales directamente en el cauce de ríos, lagos y lagunas sin ningún proceso previo de purificación. Metales pesados, detergentes, pesticidas agrícolas y microplásticos destruyen la capacidad biológica de autodepuración de la naturaleza, convirtiendo caudales limpios en focos severos de infección y muerte ecológica.
                        </p>
                    </div>
                    <div class="mt-6 pt-4 border-t border-slate-100">
                        <span class="text-xs font-semibold text-red-600 bg-red-50 px-2.5 py-1 rounded-md uppercase">Alto Impacto Ambiental</span>
                    </div>
                </div>

                <!-- Causa 2: Desperdicio de agua -->
                <div class="bg-white rounded-2xl p-8 border border-agua-100 shadow-md hover:shadow-xl transition-shadow duration-300 flex flex-col justify-between">
                    <div>
                        <div class="w-12 h-12 bg-orange-100 rounded-xl flex items-center justify-center text-orange-500 mb-6">
                            <!-- Icono de grifo/desperdicio -->
                            <svg class="w-6 h-6 fill-current" viewBox="0 0 24 24"><path d="M12,2A10,10 0 0,0 2,12A10,10 0 0,0 12,22A10,10 0 0,0 22,12A10,10 0 0,0 12,2M10,17H8V15H10V17M14,17H12V15H14V17M16,13H8V11H16V13M16,9H8V7H16V9Z" /></svg>
                        </div>
                        <h3 class="text-xl font-bold text-slate-900 mb-3">2. Desperdicio Sistemático de Agua</h3>
                        <p class="text-slate-600 text-sm md:text-base leading-relaxed">
                            El desperdicio ocurre tanto a nivel doméstico como en la infraestructura pública y agrícola. En México, los anticuados métodos de riego por inundación para la agricultura desperdician más del 55% del agua extraída. Adicionalmente, las deficiencias técnicas y las constantes fugas en la infraestructura de tuberías públicas de las ciudades provocan la pérdida de millones de litros por segundo.
                        </p>
                    </div>
                    <div class="mt-6 pt-4 border-t border-slate-100">
                        <span class="text-xs font-semibold text-orange-600 bg-orange-50 px-2.5 py-1 rounded-md uppercase">Problema Estructural</span>
                    </div>
                </div>

                <!-- Causa 3: Sobreexplotación de acuíferos -->
                <div class="bg-white rounded-2xl p-8 border border-agua-100 shadow-md hover:shadow-xl transition-shadow duration-300 flex flex-col justify-between">
                    <div>
                        <div class="w-12 h-12 bg-amber-100 rounded-xl flex items-center justify-center text-amber-500 mb-6">
                            <!-- Icono de excavación/bomba de pozo -->
                            <svg class="w-6 h-6 fill-current" viewBox="0 0 24 24"><path d="M12 2C6.5 2 2 6.5 2 12s4.5 10 10 10 10-4.5 10-10S17.5 2 12 2zm1 14h-2v-2h2v2zm0-4h-2V7h2v5z" /></svg>
                        </div>
                        <h3 class="text-xl font-bold text-slate-900 mb-3">3. Sobreexplotación de Acuíferos Subterráneos</h3>
                        <p class="text-slate-600 text-sm md:text-base leading-relaxed">
                            Al consumirse progresivamente las reservas de agua superficiales, se perforan pozos más profundos para extraer de los acuíferos subterráneos una cantidad de agua que supera con creces su tasa natural de recarga por lluvias. Este vaciado sistemático causa subsidencia (hundimiento del suelo urbano), la salinización de la tierra y la extracción nociva de arsénico y fluoruros de capas geológicas profundas.
                        </p>
                    </div>
                    <div class="mt-6 pt-4 border-t border-slate-100">
                        <span class="text-xs font-semibold text-amber-600 bg-amber-50 px-2.5 py-1 rounded-md uppercase">Vulnerabilidad Crítica</span>
                    </div>
                </div>

                <!-- Causa 4: Cambio climático -->
                <div class="bg-white rounded-2xl p-8 border border-agua-100 shadow-md hover:shadow-xl transition-shadow duration-300 flex flex-col justify-between">
                    <div>
                        <div class="w-12 h-12 bg-sky-100 rounded-xl flex items-center justify-center text-sky-500 mb-6">
                            <!-- Icono de sol/clima -->
                            <svg class="w-6 h-6 fill-current" viewBox="0 0 24 24"><path d="M12,18C11.11,18 10.26,17.8 9.5,17.45C11.56,16.5 13,14.42 13,12C13,9.58 11.56,7.5 9.5,6.55C10.26,6.2 11.11,6 12,6A6,6 0 0,1 18,12A6,6 0 0,1 12,18M20,8.69V4H15.31L12,0.69L8.69,4H4V8.69L0.69,12L4,15.31V20H8.69L12,23.31L15.31,20H20V15.31L23.31,12L20,8.69Z" /></svg>
                        </div>
                        <h3 class="text-xl font-bold text-slate-900 mb-3">4. Aceleración del Cambio Climático</h3>
                        <p class="text-slate-600 text-sm md:text-base leading-relaxed">
                            El aumento global de la temperatura altera drásticamento los ciclos hidrológicos. El cambio de patrones climáticos genera sequías prolongadas que impiden la reposición de presas de distribución, olas de calor extremo que aumentan la evaporación del agua superficial, y lluvias torrenciales desordenadas que no se filtran al subsuelo sino que provocan deslaves e inundaciones contaminantes.
                        </p>
                    </div>
                    <div class="mt-6 pt-4 border-t border-slate-100">
                        <span class="text-xs font-semibold text-sky-600 bg-sky-50 px-2.5 py-1 rounded-md uppercase">Crisis Sistémica</span>
                    </div>
                </div>
            </div>

            <!-- Botones de Navegación Rápida -->
            <div class="mt-16 flex justify-between items-center border-t border-slate-200 pt-8">
                <a href="#que-es" class="text-sm font-semibold text-slate-500 hover:text-agua-600 flex items-center gap-1">
                    &larr; Sección Anterior
                </a>
                <a href="#consecuencias" class="bg-agua-600 hover:bg-agua-700 text-white font-semibold px-5 py-2.5 rounded-lg text-sm transition-colors flex items-center gap-1">
                    Ver Consecuencias &rarr;
                </a>
            </div>
        </div>
    </section>

    <!-- SECCIÓN CONSECUENCIAS -->
    <section id="consecuencias" class="py-24 bg-slate-900 text-white scroll-mt-20">
        <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8">
            <div class="lg:text-center mb-16">
                <h2 class="text-base text-agua-400 font-semibold tracking-wide uppercase">Impactos Reales</h2>
                <p class="mt-2 text-3xl leading-8 font-extrabold tracking-tight text-white sm:text-4xl">
                    Consecuencias Devastadoras de la Escasez
                </p>
                <div class="w-24 h-1 bg-agua-400 lg:mx-auto mt-4 rounded-full"></div>
            </div>

            <div class="grid grid-cols-1 md:grid-cols-2 lg:grid-cols-4 gap-8">
                <!-- Consecuencia 1: Escasez de agua potable -->
                <div class="bg-slate-800/50 border border-slate-700/50 rounded-2xl p-6 hover:bg-slate-800 transition-all duration-300">
                    <span class="text-agua-400 text-xs font-extrabold uppercase tracking-wider block mb-3">01. Abasto</span>
                    <h3 class="text-lg font-bold mb-3 text-white">Falta de Agua Potable</h3>
                    <p class="text-slate-300 text-xs sm:text-sm leading-relaxed">
                        Provoca la interrupción del servicio mediante el "tandeo" de agua, obligando a millones de personas a racionar y almacenar agua bajo condiciones insalubres, o a depender de pipas privadas de alto costo.
                    </p>
                </div>

                <!-- Consecuencia 2: Problemas de salud -->
                <div class="bg-slate-800/50 border border-slate-700/50 rounded-2xl p-6 hover:bg-slate-800 transition-all duration-300">
                    <span class="text-agua-400 text-xs font-extrabold uppercase tracking-wider block mb-3">02. Salud Pública</span>
                    <h3 class="text-lg font-bold mb-3 text-white">Crisis Epidemiológica</h3>
                    <p class="text-slate-300 text-xs sm:text-sm leading-relaxed">
                        El consumo de agua contaminada detona de forma inmediata infecciones estomacales agudas, cólera, fiebre tifoidea y hepatitis. A largo plazo, genera toxicidad crónica o cáncer por arsénico y plomo.
                    </p>
                </div>

                <!-- Consecuencia 3: Daños al medio ambiente -->
                <div class="bg-slate-800/50 border border-slate-700/50 rounded-2xl p-6 hover:bg-slate-800 transition-all duration-300">
                    <span class="text-agua-400 text-xs font-extrabold uppercase tracking-wider block mb-3">03. Ecosistemas</span>
                    <h3 class="text-lg font-bold mb-3 text-white">Ecocidio y Extinción</h3>
                    <p class="text-slate-300 text-xs sm:text-sm leading-relaxed">
                        Los ríos y lagos contaminados sufren eutrofización (crecimiento desmesurado de algas tóxicas por nutrientes químicos), matando la biodiversidad acuática autóctona y destruyendo humedales clave.
                    </p>
                </div>

                <!-- Consecuencia 4: Impacto económico -->
                <div class="bg-slate-800/50 border border-slate-700/50 rounded-2xl p-6 hover:bg-slate-800 transition-all duration-300">
                    <span class="text-agua-400 text-xs font-extrabold uppercase tracking-wider block mb-3">04. Productividad</span>
                    <h3 class="text-lg font-bold mb-3 text-white">Inestabilidad Económica</h3>
                    <p class="text-slate-300 text-xs sm:text-sm leading-relaxed">
                        Detiene la agricultura de riego comercial, frena la producción industrial de bienes esenciales y aumenta drásticamente los gastos públicos para la remediación médica de epidemias y desastres.
                    </p>
                </div>
            </div>

            <!-- Botones de Navegación Rápida -->
            <div class="mt-16 flex justify-between items-center border-t border-slate-800 pt-8">
                <a href="#causas" class="text-sm font-semibold text-slate-400 hover:text-agua-400 flex items-center gap-1">
                    &larr; Sección Anterior
                </a>
                <a href="#soluciones" class="bg-agua-500 hover:bg-agua-600 text-white font-semibold px-5 py-2.5 rounded-lg text-sm transition-colors flex items-center gap-1">
                    Ver Soluciones &rarr;
                </a>
            </div>
        </div>
    </section>

    <!-- SECCIÓN SOLUCIONES -->
    <section id="soluciones" class="py-24 bg-white scroll-mt-20">
        <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8">
            <div class="lg:text-center mb-16">
                <h2 class="text-base text-agua-600 font-semibold tracking-wide uppercase">Líneas de Acción</h2>
                <p class="mt-2 text-3xl leading-8 font-extrabold tracking-tight text-slate-900 sm:text-4xl">
                    Soluciones Reales para un Futuro Sostenible
                </p>
                <div class="w-24 h-1 bg-agua-500 lg:mx-auto mt-4 rounded-full"></div>
            </div>

            <div class="grid grid-cols-1 lg:grid-cols-2 gap-12">
                <!-- Columna Soluciones 1 y 2 -->
                <div class="space-y-10">
                    <!-- Solución 1 -->
                    <div class="flex gap-4">
                        <div class="shrink-0 flex items-center justify-center w-12 h-12 rounded-xl bg-agua-100 text-agua-600 font-bold text-lg">
                            A
                        </div>
                        <div>
                            <h3 class="text-xl font-bold text-slate-900 mb-2">Uso Responsable y Eficiente del Agua</h3>
                            <p class="text-slate-600 text-sm md:text-base leading-relaxed">
                                Rediseñar hábitos cotidianos mediante duchas de menos de 5 minutos, la captación directa de lluvia para las labores del hogar, y el lavado de vehículos mediante cubetas en vez de manguera. A nivel social, esto requiere la correcta instalación de medidores y la aplicación de tarifas justas pero disuasorias contra el desperdicio del agua.
                            </p>
                        </div>
                    </div>

                    <!-- Solución 2 -->
                    <div class="flex gap-4">
                        <div class="shrink-0 flex items-center justify-center w-12 h-12 rounded-xl bg-agua-100 text-agua-600 font-bold text-lg">
                            B
                        </div>
                        <div>
                            <h3 class="text-xl font-bold text-slate-900 mb-2">Tratamiento y Reutilización de Aguas Residuales</h3>
                            <p class="text-slate-600 text-sm md:text-base leading-relaxed">
                                Fomentar la construcción y correcto mantenimiento operativo de plantas de tratamiento en ciudades y zonas industriales. Al limpiar las aguas grises y negras, estas pueden reincorporarse con seguridad al riego agrícola de áreas verdes urbanas, procesos de enfriamiento fabriles y recargas ecológicas en acuíferos.
                            </p>
                        </div>
                    </div>
                </div>

                <!-- Columna Soluciones 3 y 4 -->
                <div class="space-y-10">
                    <!-- Solución 3 -->
                    <div class="flex gap-4">
                        <div class="shrink-0 flex items-center justify-center w-12 h-12 rounded-xl bg-agua-100 text-agua-600 font-bold text-lg">
                            C
                        </div>
                        <div>
                            <h3 class="text-xl font-bold text-slate-900 mb-2">Educación y Cultura Ambiental</h3>
                            <p class="text-slate-600 text-sm md:text-base leading-relaxed">
                                Fortalecer los planes de estudio y campañas de comunicación masiva para sensibilizar a la población civil sobre el valor estratégico del agua. Modificar el paradigma social de ver el agua como un recurso infinito y consolidar una ciudadanía activa e informada que denuncie fugas urbanas e ilícitos ecológicos.
                            </p>
                        </div>
                    </div>

                    <!-- Solución 4 -->
                    <div class="flex gap-4">
                        <div class="shrink-0 flex items-center justify-center w-12 h-12 rounded-xl bg-agua-100 text-agua-600 font-bold text-lg">
                            D
                        </div>
                        <div>
                            <h3 class="text-xl font-bold text-slate-900 mb-2">Tecnologías Innovadoras de Ahorro</h3>
                            <p class="text-slate-600 text-sm md:text-base leading-relaxed">
                                Implementar sistemas avanzados de riego agrícola inteligente por goteo localizado guiado por sensores de humedad en el suelo. Promover el uso masivo de dispositivos residenciales de ultra-bajo consumo hídrico, griferías con sensores inteligentes, y tecnologías domésticas avanzadas para captación y filtración pluvial.
                            </p>
                        </div>
                    </div>
                </div>
            </div>

            <!-- Botones de Navegación Rápida -->
            <div class="mt-16 flex justify-between items-center border-t border-slate-150 pt-8">
                <a href="#consecuencias" class="text-sm font-semibold text-slate-500 hover:text-agua-600 flex items-center gap-1">
                    &larr; Sección Anterior
                </a>
                <a href="#galeria" class="bg-agua-600 hover:bg-agua-700 text-white font-semibold px-5 py-2.5 rounded-lg text-sm transition-colors flex items-center gap-1">
                    Ver Galería &rarr;
                </a>
            </div>
        </div>
    </section>

    <!-- GALERÍA DE IMÁGENES -->
    <section id="galeria" class="py-24 bg-pattern scroll-mt-20">
        <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8">
            <div class="lg:text-center mb-16">
                <h2 class="text-base text-agua-600 font-semibold tracking-wide uppercase">Evidencia Fotográfica</h2>
                <p class="mt-2 text-3xl leading-8 font-extrabold tracking-tight text-slate-900 sm:text-4xl">
                    Galería de la Crisis Ambiental
                </p>
                <p class="mt-4 max-w-2xl text-lg text-slate-500 lg:mx-auto">
                    Imágenes libres de derechos que retratan la belleza natural del recurso y el impacto devastador de las actividades humanas.
                </p>
                <div class="w-24 h-1 bg-agua-500 lg:mx-auto mt-4 rounded-full"></div>
            </div>

            <div class="grid grid-cols-1 sm:grid-cols-2 lg:grid-cols-3 gap-8">
                <!-- Imagen 1 -->
                <div class="group bg-white rounded-2xl overflow-hidden shadow-md hover:shadow-2xl transition-all duration-300 transform hover:-translate-y-1">
                    <div class="h-64 overflow-hidden relative">
                        <img src="https://images.unsplash.com/photo-1548802673-380ab8ebc7b7?auto=format&fit=crop&w=800&q=80" alt="Río contaminado y seco" class="w-full h-full object-cover group-hover:scale-105 transition-transform duration-500" onerror="this.src='https://via.placeholder.com/800x600/b2ebf2/006064?text=Río+Seco'">
                        <div class="absolute inset-0 bg-gradient-to-t from-slate-950/80 to-transparent opacity-0 group-hover:opacity-100 transition-opacity duration-300 flex items-end p-6">
                            <span class="text-white text-xs font-semibold uppercase tracking-wider">Foto 1: Impacto de la Sequía</span>
                        </div>
                    </div>
                    <div class="p-6">
                        <h4 class="font-bold text-slate-900 mb-2">Suelos Agrietados</h4>
                        <p class="text-slate-600 text-xs sm:text-sm">Efecto directo de la desecación de embalses superficiales y presas debido a la escasez prolongada de lluvias.</p>
                    </div>
                </div>

                <!-- Imagen 2 -->
                <div class="group bg-white rounded-2xl overflow-hidden shadow-md hover:shadow-2xl transition-all duration-300 transform hover:-translate-y-1">
                    <div class="h-64 overflow-hidden relative">
                        <img src="https://images.unsplash.com/photo-1611273426858-450d8e3c9fce?auto=format&fit=crop&w=800&q=80" alt="Residuos plásticos en agua" class="w-full h-full object-cover group-hover:scale-105 transition-transform duration-500" onerror="this.src='https://via.placeholder.com/800x600/b2ebf2/006064?text=Contaminación+Plástica'">
                        <div class="absolute inset-0 bg-gradient-to-t from-slate-950/80 to-transparent opacity-0 group-hover:opacity-100 transition-opacity duration-300 flex items-end p-6">
                            <span class="text-white text-xs font-semibold uppercase tracking-wider">Foto 2: Desechos Urbanos</span>
                        </div>
                    </div>
                    <div class="p-6">
                        <h4 class="font-bold text-slate-900 mb-2">Acumulación de Plásticos</h4>
                        <p class="text-slate-600 text-xs sm:text-sm">Ríos convertidos en vertederos de basura plástica no degradable, obstruyendo los ecosistemas riparios.</p>
                    </div>
                </div>

                <!-- Imagen 3 -->
                <div class="group bg-white rounded-2xl overflow-hidden shadow-md hover:shadow-2xl transition-all duration-300 transform hover:-translate-y-1">
                    <div class="h-64 overflow-hidden relative">
                        <img src="https://images.unsplash.com/photo-1533038590840-1cde6e6e40dd?auto=format&fit=crop&w=800&q=80" alt="Filtro de agua o agua saliendo de grifo" class="w-full h-full object-cover group-hover:scale-105 transition-transform duration-500" onerror="this.src='https://via.placeholder.com/800x600/b2ebf2/006064?text=Acceso+Limitado'">
                        <div class="absolute inset-0 bg-gradient-to-t from-slate-950/80 to-transparent opacity-0 group-hover:opacity-100 transition-opacity duration-300 flex items-end p-6">
                            <span class="text-white text-xs font-semibold uppercase tracking-wider">Foto 3: Suministro Precario</span>
                        </div>
                    </div>
                    <div class="p-6">
                        <h4 class="font-bold text-slate-900 mb-2">Acceso Desigual</h4>
                        <p class="text-slate-600 text-xs sm:text-sm">Millones de personas reciben agua por tandeo limitado, limitando su derecho humano a la salud y al saneamiento.</p>
                    </div>
                </div>

                <!-- Imagen 4 -->
                <div class="group bg-white rounded-2xl overflow-hidden shadow-md hover:shadow-2xl transition-all duration-300 transform hover:-translate-y-1">
                    <div class="h-64 overflow-hidden relative">
                        <img src="https://images.unsplash.com/photo-1541872703-74c5e44368f9?auto=format&fit=crop&w=800&q=80" alt="Agua pura fluyendo" class="w-full h-full object-cover group-hover:scale-105 transition-transform duration-500" onerror="this.src='https://via.placeholder.com/800x600/b2ebf2/006064?text=Agua+Limpia'">
                        <div class="absolute inset-0 bg-gradient-to-t from-slate-950/80 to-transparent opacity-0 group-hover:opacity-100 transition-opacity duration-300 flex items-end p-6">
                            <span class="text-white text-xs font-semibold uppercase tracking-wider">Foto 4: Belleza Frágil</span>
                        </div>
                    </div>
                    <div class="p-6">
                        <h4 class="font-bold text-slate-900 mb-2">Caudales Naturales</h4>
                        <p class="text-slate-600 text-xs sm:text-sm">El agua en su estado puro es vital para la supervivencia de bosques de niebla y humedales de montaña.</p>
                    </div>
                </div>

                <!-- Imagen 5 -->
                <div class="group bg-white rounded-2xl overflow-hidden shadow-md hover:shadow-2xl transition-all duration-300 transform hover:-translate-y-1">
                    <div class="h-64 overflow-hidden relative">
                        <img src="https://images.unsplash.com/photo-1504384308090-c894fdcc538d?auto=format&fit=crop&w=800&q=80" alt="Planta de tratamiento de agua" class="w-full h-full object-cover group-hover:scale-105 transition-transform duration-500" onerror="this.src='https://via.placeholder.com/800x600/b2ebf2/006064?text=Saneamiento'">
                        <div class="absolute inset-0 bg-gradient-to-t from-slate-950/80 to-transparent opacity-0 group-hover:opacity-100 transition-opacity duration-300 flex items-end p-6">
                            <span class="text-white text-xs font-semibold uppercase tracking-wider">Foto 5: Infraestructura</span>
                        </div>
                    </div>
                    <div class="p-6">
                        <h4 class="font-bold text-slate-900 mb-2">Plantas de Saneamiento</h4>
                        <p class="text-slate-600 text-xs sm:text-sm">Las grandes plantas de purificación y sedimentación de agua representan la esperanza tecnológica del mañana.</p>
                    </div>
                </div>

                <!-- Imagen 6 -->
                <div class="group bg-white rounded-2xl overflow-hidden shadow-md hover:shadow-2xl transition-all duration-300 transform hover:-translate-y-1">
                    <div class="h-64 overflow-hidden relative">
                        <img src="https://images.unsplash.com/photo-1468476396571-4d6f2a427ee7?auto=format&fit=crop&w=800&q=80" alt="Niños lavándose las manos" class="w-full h-full object-cover group-hover:scale-105 transition-transform duration-500" onerror="this.src='https://via.placeholder.com/800x600/b2ebf2/006064?text=Infancia+y+Agua'">
                        <div class="absolute inset-0 bg-gradient-to-t from-slate-950/80 to-transparent opacity-0 group-hover:opacity-100 transition-opacity duration-300 flex items-end p-6">
                            <span class="text-white text-xs font-semibold uppercase tracking-wider">Foto 6: Derecho Humano</span>
                        </div>
                    </div>
                    <div class="p-6">
                        <h4 class="font-bold text-slate-900 mb-2">Bienestar de la Infancia</h4>
                        <p class="text-slate-600 text-xs sm:text-sm">Garantizar agua limpia para las nuevas generaciones es fundamental para erradicar enfermedades.</p>
                    </div>
                </div>
            </div>

            <!-- Botones de Navegación Rápida -->
            <div class="mt-16 flex justify-between items-center border-t border-slate-200 pt-8">
                <a href="#soluciones" class="text-sm font-semibold text-slate-500 hover:text-agua-600 flex items-center gap-1">
                    &larr; Sección Anterior
                </a>
                <a href="#infografia" class="bg-agua-600 hover:bg-agua-700 text-white font-semibold px-5 py-2.5 rounded-lg text-sm transition-colors flex items-center gap-1">
                    Ver Infografía &rarr;
                </a>
            </div>
        </div>
    </section>

    <!-- INFOGRAFÍA INTERACTIVA -->
    <section id="infografia" class="py-24 bg-agua-950 text-white scroll-mt-20">
        <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8">
            <div class="lg:text-center mb-16">
                <h2 class="text-base text-agua-400 font-semibold tracking-wide uppercase">Datos que Impactan</h2>
                <p class="mt-2 text-3xl leading-8 font-extrabold tracking-tight text-white sm:text-4xl">
                    Infografía: El Ciclo de la Crisis en Cifras
                </p>
                <div class="w-24 h-1 bg-agua-400 lg:mx-auto mt-4 rounded-full"></div>
            </div>

            <!-- Estructura de la Infografía -->
            <div class="bg-slate-900 border border-agua-900 rounded-3xl p-6 sm:p-10 shadow-2xl">
                <!-- Fila de Cabecera -->
                <div class="grid grid-cols-1 lg:grid-cols-3 gap-8 items-center border-b border-agua-900 pb-10">
                    <div class="lg:col-span-2">
                        <span class="bg-red-500/15 text-red-400 border border-red-500/30 text-xs px-3 py-1 rounded-full font-bold uppercase tracking-wide">
                            Peligro Global y Nacional
                        </span>
                        <h3 class="text-2xl sm:text-3xl font-extrabold text-white mt-4">Un Recurso Crítico en Vías de Extinción</h3>
                        <p class="text-slate-400 text-sm mt-2">La alarmante realidad sobre la disponibilidad, consumo e higiene hídrica en nuestro entorno.</p>
                    </div>
                    <div class="bg-agua-950 p-4 rounded-2xl border border-agua-800 text-center">
                        <span class="text-xs text-slate-400 block uppercase font-semibold">Consumo promedio diario por habitante en México</span>
                        <span class="text-4xl font-black text-agua-400 block mt-1">366 Litros</span>
                        <span class="text-[10px] text-red-400 font-semibold block mt-1">Sugerido por la OMS: 100 Litros</span>
                    </div>
                </div>

                <!-- Bloques de datos y métricas -->
                <div class="grid grid-cols-1 md:grid-cols-3 gap-8 mt-10">
                    <!-- Cuadro de datos 1 -->
                    <div class="bg-slate-950 p-6 rounded-2xl border border-agua-900 flex flex-col justify-between">
                        <div>
                            <span class="p-3 bg-red-500/10 text-red-400 rounded-lg inline-block mb-4">
                                <svg class="w-6 h-6 fill-current" viewBox="0 0 24 24"><path d="M12.96,5.29L19.5,18.3C19.83,18.96 19.35,19.75 18.62,19.75H5.38C4.65,19.75 4.17,18.96 4.5,18.3L11.04,5.29C11.41,4.56 12.59,4.56 12.96,5.29M11,10V14H13V10H11M11,16V18H13V16H11Z" /></svg>
                            </span>
                            <h4 class="font-bold text-lg mb-2 text-white">Sobreexplotación</h4>
                            <p class="text-xs text-slate-400 leading-relaxed">
                                México posee el mayor número de acuíferos sobreexplotados en América Latina. La extracción indiscriminada excede hasta en un 300% los flujos de recarga natural.
                            </p>
                        </div>
                        <div class="mt-6 text-3xl font-extrabold text-red-400">105 de 653</div>
                    </div>

                    <!-- Cuadro de datos 2 -->
                    <div class="bg-slate-950 p-6 rounded-2xl border border-agua-900 flex flex-col justify-between">
                        <div>
                            <span class="p-3 bg-yellow-500/10 text-yellow-400 rounded-lg inline-block mb-4">
                                <svg class="w-6 h-6 fill-current" viewBox="0 0 24 24"><path d="M12 2C6.5 2 2 6.5 2 12s4.5 10 10 10 10-4.5 10-10S17.5 2 12 2zm1 14h-2v-2h2v2zm0-4h-2V7h2v5z" /></svg>
                            </span>
                            <h4 class="font-bold text-lg mb-2 text-white">Pérdida en Redes</h4>
                            <p class="text-xs text-slate-400 leading-relaxed">
                                Debido a la nula modernización de las tuberías y las válvulas municipales defectuosas, una enorme porción del suministro de agua potable se esfuma antes de llegar a los hogares.
                            </p>
                        </div>
                        <div class="mt-6 text-3xl font-extrabold text-yellow-400">40% Perdido</div>
                    </div>

                    <!-- Cuadro de datos 3 -->
                    <div class="bg-slate-950 p-6 rounded-2xl border border-agua-900 flex flex-col justify-between">
                        <div>
                            <span class="p-3 bg-emerald-500/10 text-emerald-400 rounded-lg inline-block mb-4">
                                <svg class="w-6 h-6 fill-current" viewBox="0 0 24 24"><path d="M12,2A10,10 0 0,0 2,12A10,10 0 0,0 12,22A10,10 0 0,0 22,12A10,10 0 0,0 12,2M10,17L5,12L6.41,10.59L10,14.17L17.59,6.58L19,8L10,17Z" /></svg>
                            </span>
                            <h4 class="font-bold text-lg mb-2 text-white">Falta de Tratamiento</h4>
                            <p class="text-xs text-slate-400 leading-relaxed">
                                El 60% de todas las aguas residuales industriales y municipales del país regresan de forma directa a la naturaleza sin haber sido sometidas a ningún proceso de purificación.
                            </p>
                        </div>
                        <div class="mt-6 text-3xl font-extrabold text-emerald-400">60% Sin Tratar</div>
                    </div>
                </div>

                <!-- Resumen Visual Inferior -->
                <div class="mt-10 p-6 bg-agua-950 rounded-2xl border border-agua-900 flex flex-col md:flex-row items-center justify-between gap-6">
                    <div class="flex items-center gap-4">
                        <span class="text-4xl">💧</span>
                        <div>
                            <h4 class="font-bold text-white text-base">¿Qué podemos hacer nosotros?</h4>
                            <p class="text-xs text-slate-300">Cada pequeña gota cuenta. Reducir un minuto en tu ducha diaria ahorra hasta 20 litros de agua limpia.</p>
                        </div>
                    </div>
                    <a href="#soluciones" class="bg-agua-500 hover:bg-agua-600 text-white font-semibold text-xs px-5 py-3 rounded-lg uppercase tracking-wider transition-colors inline-block whitespace-nowrap">
                        Ver Soluciones Detalladas
                    </a>
                </div>
            </div>

            <!-- Botones de Navegación Rápida -->
            <div class="mt-16 flex justify-between items-center border-t border-slate-800 pt-8">
                <a href="#galeria" class="text-sm font-semibold text-slate-400 hover:text-agua-400 flex items-center gap-1">
                    &larr; Sección Anterior
                </a>
                <a href="#cartel" class="bg-agua-500 hover:bg-agua-600 text-white font-semibold px-5 py-2.5 rounded-lg text-sm transition-colors flex items-center gap-1">
                    Ver Cartel Digital &rarr;
                </a>
            </div>
        </div>
    </section>

    <!-- CARTEL DIGITAL DE CONCIENTIZACIÓN -->
    <section id="cartel" class="py-24 bg-white scroll-mt-20">
        <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8">
            <div class="lg:text-center mb-16">
                <h2 class="text-base text-agua-600 font-semibold tracking-wide uppercase">Campaña Visual</h2>
                <p class="mt-2 text-3xl leading-8 font-extrabold tracking-tight text-slate-900 sm:text-4xl">
                    Cartel Digital: Mensaje a la Comunidad
                </p>
                <div class="w-24 h-1 bg-agua-500 lg:mx-auto mt-4 rounded-full"></div>
            </div>

            <!-- Contenedor del Cartel -->
            <div class="max-w-3xl mx-auto bg-gradient-to-br from-agua-900 to-agua-950 rounded-3xl overflow-hidden shadow-2xl relative border-4 border-white/10">
                <!-- Fondo Decorativo -->
                <div class="absolute inset-0 opacity-10 bg-[radial-gradient(#fff_1px,transparent_1px)] [background-size:16px_16px]"></div>
                <!-- Círculos de luz flotantes -->
                <div class="absolute -right-24 -bottom-24 w-64 h-64 bg-agua-500/20 rounded-full blur-3xl"></div>
                <div class="absolute -left-24 -top-24 w-64 h-64 bg-agua-400/20 rounded-full blur-3xl"></div>

                <div class="relative z-10 p-8 sm:p-12 text-center text-white">
                    <span class="text-agua-400 text-xs sm:text-sm font-extrabold tracking-widest uppercase block mb-4">
                        ¡CUIDA HOY EL AGUA DE MAÑANA!
                    </span>
                    
                    <!-- Simbología -->
                    <div class="my-8 flex justify-center">
                        <div class="relative">
                            <!-- Icono de Gota Grande -->
                            <svg class="h-28 w-28 text-agua-400 fill-current animate-bounce" viewBox="0 0 24 24">
                                <path d="M12,2.69C12,2.69 19,10.15 19,15A7,7 0 0,1 12,22A7,7 0 0,1 5,15C5,10.15 12,2.69 12,2.69Z" />
                            </svg>
                            <!-- Destello de gota -->
                            <div class="absolute top-2 right-2 w-3 h-3 bg-white rounded-full"></div>
                        </div>
                    </div>

                    <h3 class="text-3xl sm:text-5xl font-black tracking-tight leading-none mb-6">
                        SI EL AGUA <span class="text-transparent bg-clip-text bg-gradient-to-r from-red-400 to-orange-400">SE ACABA</span>,<br>
                        LA VIDA <span class="text-agua-400">TAMBIÉN</span>.
                    </h3>

                    <p class="text-slate-300 text-sm sm:text-base max-w-lg mx-auto mb-8 font-light leading-relaxed">
                        El agua no es un bien inagotable. Cada gota contaminada o tirada al drenaje es un recurso que jamás volverá. El cambio comienza en tu hogar y con tus acciones cotidianas.
                    </p>

                    <div class="border-t border-white/10 pt-8 flex flex-col sm:flex-row justify-center items-center gap-6 text-xs text-slate-400">
                        <span class="flex items-center gap-1">
                            <span class="text-agua-400">✔</span> Cierra la llave al cepillarte
                        </span>
                        <span class="flex items-center gap-1">
                            <span class="text-agua-400">✔</span> Reporta fugas en tu calle
                        </span>
                        <span class="flex items-center gap-1">
                            <span class="text-agua-400">✔</span> Reutiliza el agua de la lavadora
                        </span>
                    </div>

                    <p class="mt-8 text-[10px] text-agua-500 font-bold uppercase tracking-wider">
                        Comisión de Cuidado Ambiental Escolar · 2026
                    </p>
                </div>
            </div>

            <!-- Botones de Navegación Rápida -->
            <div class="mt-16 flex justify-between items-center border-t border-slate-200 pt-8">
                <a href="#infografia" class="text-sm font-semibold text-slate-500 hover:text-agua-600 flex items-center gap-1">
                    &larr; Sección Anterior
                </a>
                <a href="#juego" class="bg-agua-600 hover:bg-agua-700 text-white font-semibold px-5 py-2.5 rounded-lg text-sm transition-colors flex items-center gap-1">
                    ¡Ir al Juego! &rarr;
                </a>
            </div>
        </div>
    </section>

    <!-- SECCIÓN JUEGO INTERACTIVO -->
    <section id="juego" class="py-24 bg-pattern scroll-mt-20">
        <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8">
            <div class="lg:text-center mb-12">
                <h2 class="text-base text-agua-600 font-semibold tracking-wide uppercase">Aprende Jugando</h2>
                <p class="mt-2 text-3xl leading-8 font-extrabold tracking-tight text-slate-900 sm:text-4xl">
                    Desafío: Guardián del Agua
                </p>
                <p class="mt-4 max-w-2xl text-lg text-slate-500 lg:mx-auto">
                    Controla la embarcación de limpieza ecológica. Recolecta las gotas de agua limpia y filtros para purificar el caudal, pero esquiva las botellas plásticas y barriles tóxicos. ¡Logra 200 puntos para ganar!
                </p>
                <div class="w-24 h-1 bg-agua-500 lg:mx-auto mt-4 rounded-full"></div>
            </div>

            <!-- Interfaz del Juego -->
            <div class="max-w-4xl mx-auto bg-slate-900 rounded-3xl p-6 shadow-2xl relative overflow-hidden border-4 border-agua-500/30">
                <!-- Tablero de Datos -->
                <div class="flex items-center justify-between bg-slate-950/80 rounded-2xl p-4 mb-6 border border-slate-800 text-white flex-wrap gap-4">
                    <div class="flex items-center gap-3">
                        <span class="text-2xl">🏆</span>
                        <div>
                            <span class="text-xs text-slate-400 block font-semibold uppercase">Puntuación</span>
                            <span id="game-score" class="text-2xl font-black text-agua-400">0</span> <span class="text-slate-500">/ 200</span>
                        </div>
                    </div>
                    <div class="flex items-center gap-3">
                        <span class="text-2xl">❤️</span>
                        <div>
                            <span class="text-xs text-slate-400 block font-semibold uppercase">Vidas</span>
                            <div id="game-lives" class="flex gap-1 text-red-500 text-xl font-bold">❤️❤️❤️</div>
                        </div>
                    </div>
                    <div class="flex items-center gap-3">
                        <span class="text-2xl">⚡</span>
                        <div>
                            <span class="text-xs text-slate-400 block font-semibold uppercase">Nivel</span>
                            <span id="game-level" class="text-xl font-black text-yellow-400">1</span>
                        </div>
                    </div>
                </div>

                <!-- Contenedor del Lienzo de Canvas -->
                <div class="relative w-full aspect-[4/3] bg-sky-950/40 rounded-2xl overflow-hidden border border-slate-800">
                    <canvas id="game-canvas" class="w-full h-full block bg-gradient-to-b from-sky-900 to-indigo-950"></canvas>

                    <!-- Pantalla Inicial de Inicio / Pausa / Fin -->
                    <div id="game-overlay" class="absolute inset-0 bg-slate-950/85 flex flex-col items-center justify-center text-center p-8 transition-all duration-300">
                        <div id="overlay-icon" class="text-6xl mb-4 animate-bounce">⛵</div>
                        <h3 id="overlay-title" class="text-2xl sm:text-4xl font-extrabold text-white mb-2">¡Desafío Guardián!</h3>
                        <p id="overlay-desc" class="text-slate-400 text-xs sm:text-sm max-w-md mb-6 leading-relaxed">
                            Mueve el barco recolector usando las <span class="text-agua-400 font-bold">flechas de dirección (← / →)</span> o los botones de la pantalla táctil para salvar el río de la contaminación.
                        </p>
                        <button id="btn-play" class="bg-agua-500 hover:bg-agua-600 text-white font-extrabold text-sm sm:text-base px-8 py-3.5 rounded-xl shadow-lg transition-all duration-300 transform hover:scale-105 uppercase tracking-wide">
                            Iniciar Misión de Limpieza
                        </button>
                    </div>
                </div>

                <!-- Controles para pantallas táctiles -->
                <div class="grid grid-cols-2 gap-4 mt-6">
                    <button id="btn-left" class="bg-slate-800/80 hover:bg-slate-700 border border-slate-700/50 active:bg-agua-700 active:text-white py-4 rounded-2xl text-white font-black text-center select-none flex items-center justify-center gap-2 transition-all duration-150">
                        <svg class="w-6 h-6" fill="none" stroke="currentColor" viewBox="0 0 24 24"><path stroke-linecap="round" stroke-linejoin="round" stroke-width="3" d="M15 19l-7-7 7-7" /></svg>
                        IZQUIERDA
                    </button>
                    <button id="btn-right" class="bg-slate-800/80 hover:bg-slate-700 border border-slate-700/50 active:bg-agua-700 active:text-white py-4 rounded-2xl text-white font-black text-center select-none flex items-center justify-center gap-2 transition-all duration-150">
                        DERECHA
                        <svg class="w-6 h-6" fill="none" stroke="currentColor" viewBox="0 0 24 24"><path stroke-linecap="round" stroke-linejoin="round" stroke-width="3" d="M9 5l7 7-7 7" /></svg>
                    </button>
                </div>

                <!-- Leyenda de Ítems del Juego -->
                <div class="mt-6 pt-4 border-t border-slate-800 grid grid-cols-2 sm:grid-cols-4 gap-4 text-xs text-slate-300">
                    <div class="flex items-center gap-2">
                        <span class="w-3 h-3 bg-blue-500 rounded-full inline-block"></span>
                        <span>Gota Limpia (+10 Ptos)</span>
                    </div>
                    <div class="flex items-center gap-2">
                        <span class="w-3 h-3 bg-emerald-400 rounded-full inline-block"></span>
                        <span>Filtro (+20 Ptos / +1 Vida)</span>
                    </div>
                    <div class="flex items-center gap-2">
                        <span class="w-3 h-3 bg-gray-500 rounded-full inline-block"></span>
                        <span>Botella Plástica (-1 Vida)</span>
                    </div>
                    <div class="flex items-center gap-2">
                        <span class="w-3 h-3 bg-red-500 rounded-full inline-block"></span>
                        <span>Barril Tóxico (-1 Vida)</span>
                    </div>
                </div>
            </div>

            <!-- Botones de Navegación Rápida -->
            <div class="mt-16 flex justify-between items-center border-t border-slate-200 pt-8">
                <a href="#cartel" class="text-sm font-semibold text-slate-500 hover:text-agua-600 flex items-center gap-1">
                    &larr; Sección Anterior
                </a>
                <a href="#reflexion" class="bg-agua-600 hover:bg-agua-700 text-white font-semibold px-5 py-2.5 rounded-lg text-sm transition-colors flex items-center gap-1">
                    Ver Reflexión Final &rarr;
                </a>
            </div>
        </div>
    </section>

    <!-- REFLEXIÓN FINAL -->
    <section id="reflexion" class="py-24 bg-pattern scroll-mt-20">
        <div class="max-w-5xl mx-auto px-4 sm:px-6 lg:px-8">
            <div class="bg-gradient-to-br from-agua-50 to-white border border-agua-200 rounded-3xl p-8 sm:p-12 shadow-xl relative overflow-hidden">
                <div class="absolute right-0 top-0 w-32 h-32 bg-agua-100/40 rounded-full blur-2xl"></div>
                <div class="relative z-10">
                    <span class="text-agua-600 text-xs font-bold tracking-widest uppercase block mb-4">PROYECTO ESCOLAR</span>
                    <h2 class="text-3xl font-extrabold text-slate-900 mb-6">Reflexión Final para los Estudiantes</h2>
                    
                    <div class="space-y-6 text-slate-700 text-sm md:text-base leading-relaxed">
                        <p>
                            Estimado compañero estudiante: la problemática de la escasez y la alarmante contaminación del agua en México y el mundo no es un asunto lejano que competa únicamente a los gobiernos o a las grandes industrias. Cada litro de agua que desperdiciamos o contaminamos acelera un proceso que pone en riesgo inminente nuestra propia supervivencia.
                        </p>
                        <p>
                            Al analizar la crisis del agua desde una perspectiva escolar y académica, comprendemos que el conocimiento solo adquiere un verdadero valor cuando se traduce en acciones diarias conscientes. Nuestra escuela, nuestro hogar y nuestra comunidad vecinal son los primeros campos de acción donde debemos liderar el cambio cultural hídrico.
                        </p>
                        <blockquote class="border-l-4 border-agua-500 pl-4 py-1 my-4 text-slate-900 italic font-medium">
                            "No heredamos la tierra de nuestros antepasados, la tomamos prestada de nuestros hijos. El agua limpia es el primer eslabón del futuro."
                        </blockquote>
                        <p>
                            Te invitamos a ser un agente de cambio. No seas un espectador pasivo ante la crisis ambiental de nuestro siglo. Adopta hábitos de ahorro, educa a tu familia, exige políticas ambientales en tu municipio y cuida la naturaleza. Tu voz y tus acciones presentes definirán el porvenir ecológico de México.
                        </p>
                    </div>

                    <div class="mt-8 pt-8 border-t border-agua-200 flex flex-col sm:flex-row items-center justify-between gap-4">
                        <div class="flex items-center gap-3">
                            <div class="w-10 h-10 rounded-full bg-agua-500 flex items-center justify-center text-white font-bold">
                                S
                            </div>
                            <div>
                                <span class="font-bold text-slate-900 text-sm block">Comunidad Escolar</span>
                                <span class="text-xs text-slate-500 block">Comprometidos con el desarrollo sostenible</span>
                            </div>
                        </div>
                        <a href="#inicio" class="bg-agua-600 hover:bg-agua-700 text-white font-semibold px-6 py-3 rounded-lg text-sm transition-all duration-300">
                            Volver al Inicio
                        </a>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <!-- FOOTER -->
    <footer class="bg-agua-950 text-slate-400 py-12 border-t border-agua-900">
        <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8 text-center sm:text-left">
            <div class="flex flex-col sm:flex-row justify-between items-center gap-6">
                <div>
                    <span class="text-white font-extrabold text-lg block">Alerta Azul</span>
                    <p class="text-xs mt-1">Proyecto escolar desarrollado para la materia de Ciencias y Ecología.</p>
                </div>
                <div class="flex gap-4 text-xs">
                    <a href="#que-es" class="hover:text-white transition-colors">¿Qué es la crisis?</a>
                    <span>·</span>
                    <a href="#causas" class="hover:text-white transition-colors">Causas</a>
                    <span>·</span>
                    <a href="#consecuencias" class="hover:text-white transition-colors">Consecuencias</a>
                    <span>·</span>
                    <a href="#soluciones" class="hover:text-white transition-colors">Soluciones</a>
                </div>
            </div>
            <div class="mt-8 pt-8 border-t border-agua-900 text-center text-[10px]">
                <p>&copy; 2026 Alerta Azul. Imágenes libres de derechos por Unsplash. Todos los derechos reservados. Diseñado de forma profesional.</p>
            </div>
        </div>
    </footer>

    <!-- SCRIPT DE COMPORTAMIENTO INTERACTIVO Y LÓGICA DEL JUEGO -->
    <script>
        // Lógica de apertura y cierre del menú móvil
        const mobileMenuBtn = document.getElementById('mobile-menu-btn');
        const mobileMenu = document.getElementById('mobile-menu');
        const menuIcon = document.getElementById('menu-icon');

        mobileMenuBtn.addEventListener('click', () => {
            mobileMenu.classList.toggle('hidden');
            if (mobileMenu.classList.contains('hidden')) {
                menuIcon.setAttribute('d', 'M4 6h16M4 12h16M4 18h16');
            } else {
                menuIcon.setAttribute('d', 'M6 18L18 6M6 6l12 12');
            }
        });

        const mobileLinks = mobileMenu.querySelectorAll('a');
        mobileLinks.forEach(link => {
            link.addEventListener('click', () => {
                mobileMenu.classList.add('hidden');
                menuIcon.setAttribute('d', 'M4 6h16M4 12h16M4 18h16');
            });
        });

        // Desplazamiento suave inteligente (Smooth Scroll)
        const navigationLinks = document.querySelectorAll('a[href^="#"]');
        navigationLinks.forEach(link => {
            link.addEventListener('click', function(e) {
                e.preventDefault();
                const targetId = this.getAttribute('href');
                const targetSection = document.querySelector(targetId);
                
                if (targetSection) {
                    const headerHeight = document.querySelector('header').offsetHeight;
                    const targetPosition = targetSection.getBoundingClientRect().top + window.pageYOffset - headerHeight + 5;
                    window.scrollTo({
                        top: targetPosition,
                        behavior: 'smooth'
                    });
                }
            });
        });

        // Resaltar sección activa en el menú al hacer scroll
        const sections = document.querySelectorAll('section');
        const navLinks = document.querySelectorAll('header nav a');

        window.addEventListener('scroll', () => {
            let current = '';
            const headerHeight = document.querySelector('header').offsetHeight;
            
            sections.forEach(section => {
                const sectionTop = section.offsetTop - headerHeight - 20;
                if (window.pageYOffset >= sectionTop) {
                    current = section.getAttribute('id');
                }
            });

            navLinks.forEach(link => {
                link.classList.remove('text-white', 'bg-agua-900/50');
                link.classList.add('text-slate-100');
                if (link.getAttribute('href') === `#${current}`) {
                    link.classList.remove('text-slate-100');
                    link.classList.add('text-white', 'bg-agua-900/50');
                }
            });
        });

        // SCRIPT DEL JUEGO INTERACTIVO "GUARDIÁN DEL AGUA"
        const canvas = document.getElementById('game-canvas');
        const ctx = canvas.getContext('2d');
        const gameScoreEl = document.getElementById('game-score');
        const gameLivesEl = document.getElementById('game-lives');
        const gameLevelEl = document.getElementById('game-level');
        const gameOverlay = document.getElementById('game-overlay');
        const btnPlay = document.getElementById('btn-play');
        const overlayIcon = document.getElementById('overlay-icon');
        const overlayTitle = document.getElementById('overlay-title');
        const overlayDesc = document.getElementById('overlay-desc');

        // Botones móviles
        const btnLeft = document.getElementById('btn-left');
        const btnRight = document.getElementById('btn-right');

        // Configurar Web Audio API para efectos sonoros interactivos
        let audioCtx;
        function initAudio() {
            if (!audioCtx) {
                audioCtx = new (window.AudioContext || window.webkitAudioContext)();
            }
        }

        function playSynthSound(type) {
            initAudio();
            if (!audioCtx) return;
            if (audioCtx.state === 'suspended') {
                audioCtx.resume();
            }

            const osc = audioCtx.createOscillator();
            const gain = audioCtx.createGain();
            osc.connect(gain);
            gain.connect(audioCtx.destination);

            if (type === 'catch') {
                // Sonido agudo ascendente para aciertos
                osc.frequency.setValueAtTime(440, audioCtx.currentTime); // A4
                osc.frequency.exponentialRampToValueAtTime(880, audioCtx.currentTime + 0.15); // A5
                gain.gain.setValueAtTime(0.1, audioCtx.currentTime);
                gain.gain.exponentialRampToValueAtTime(0.01, audioCtx.currentTime + 0.15);
                osc.start();
                osc.stop(audioCtx.currentTime + 0.15);
            } else if (type === 'damage') {
                // Sonido grave descendente y áspero para golpes
                osc.type = 'sawtooth';
                osc.frequency.setValueAtTime(220, audioCtx.currentTime); 
                osc.frequency.linearRampToValueAtTime(100, audioCtx.currentTime + 0.3); 
                gain.gain.setValueAtTime(0.15, audioCtx.currentTime);
                gain.gain.exponentialRampToValueAtTime(0.01, audioCtx.currentTime + 0.3);
                osc.start();
                osc.stop(audioCtx.currentTime + 0.3);
            } else if (type === 'win') {
                // Arpegio triunfante
                osc.frequency.setValueAtTime(523.25, audioCtx.currentTime); // C5
                osc.frequency.setValueAtTime(659.25, audioCtx.currentTime + 0.1); // E5
                osc.frequency.setValueAtTime(783.99, audioCtx.currentTime + 0.2); // G5
                osc.frequency.setValueAtTime(1046.50, audioCtx.currentTime + 0.3); // C6
                gain.gain.setValueAtTime(0.15, audioCtx.currentTime);
                gain.gain.exponentialRampToValueAtTime(0.01, audioCtx.currentTime + 0.5);
                osc.start();
                osc.stop(audioCtx.currentTime + 0.5);
            }
        }

        // Ajustar resolución de render del Canvas
        function setCanvasSize() {
            canvas.width = canvas.parentElement.clientWidth;
            canvas.height = canvas.parentElement.clientHeight;
        }
        setCanvasSize();
        window.addEventListener('resize', setCanvasSize);

        // Variables de estado del juego
        let score = 0;
        let lives = 3;
        let level = 1;
        let gameActive = false;
        let baseSpeed = 2.5;

        // Propiedades de la barca (Jugador)
        const boat = {
            x: 0,
            y: 0,
            width: 70,
            height: 35,
            speed: 8,
            movingLeft: false,
            movingRight: false
        };

        // Arreglos de objetos del juego
        let fallers = [];
        let particles = [];

        // Inicializar posición inicial de la barca
        function resetPlayer() {
            boat.x = canvas.width / 2 - boat.width / 2;
            boat.y = canvas.height - boat.height - 15;
        }

        // Tipos de objetos que caen
        const FallerTypes = {
            DROP: { char: '💧', color: '#38bdf8', points: 10, penalty: 0, speedMult: 1.0 },
            FILTER: { char: '🟢', color: '#34d399', points: 20, penalty: 0, speedMult: 1.2, isFilter: true },
            BOTTLE: { char: '🍾', color: '#94a3b8', points: 0, penalty: 1, speedMult: 1.1 },
            BARREL: { char: '☣️', color: '#ef4444', points: 0, penalty: 1, speedMult: 1.3 }
        };

        // Generar un nuevo objeto cayendo
        function spawnFaller() {
            const rand = Math.random();
            let type;
            if (rand < 0.55) {
                type = FallerTypes.DROP;
            } else if (rand < 0.65) {
                type = FallerTypes.FILTER;
            } else if (rand < 0.85) {
                type = FallerTypes.BOTTLE;
            } else {
                type = FallerTypes.BARREL;
            }

            fallers.push({
                x: Math.random() * (canvas.width - 40) + 20,
                y: -30,
                size: 26,
                type: type,
                speed: (baseSpeed + (level * 0.7)) * type.speedMult
            });
        }

        // Crear una salpicadura de partículas
        function spawnParticles(x, y, color) {
            for (let i = 0; i < 8; i++) {
                particles.push({
                    x: x,
                    y: y,
                    vx: (Math.random() - 0.5) * 6,
                    vy: (Math.random() - 0.8) * 6,
                    size: Math.random() * 4 + 2,
                    color: color,
                    alpha: 1,
                    decay: Math.random() * 0.05 + 0.02
                });
            }
        }

        // Controles de teclado
        window.addEventListener('keydown', (e) => {
            if (e.key === 'ArrowLeft' || e.key === 'a') boat.movingLeft = true;
            if (e.key === 'ArrowRight' || e.key === 'd') boat.movingRight = true;
        });

        window.addEventListener('keyup', (e) => {
            if (e.key === 'ArrowLeft' || e.key === 'a') boat.movingLeft = false;
            if (e.key === 'ArrowRight' || e.key === 'd') boat.movingRight = false;
        });

        // Controles móviles (Soportar drag e interacciones touch)
        btnLeft.addEventListener('touchstart', (e) => { e.preventDefault(); boat.movingLeft = true; }, { passive: false });
        btnLeft.addEventListener('touchend', () => boat.movingLeft = false);
        btnRight.addEventListener('touchstart', (e) => { e.preventDefault(); boat.movingRight = true; }, { passive: false });
        btnRight.addEventListener('touchend', () => boat.movingRight = false);

        btnLeft.addEventListener('mousedown', () => boat.movingLeft = true);
        btnLeft.addEventListener('mouseup', () => boat.movingLeft = false);
        btnRight.addEventListener('mousedown', () => boat.movingRight = true);
        btnRight.addEventListener('mouseup', () => boat.movingRight = false);

        function updateGame() {
            if (!gameActive) return;

            // Movimiento del barco
            if (boat.movingLeft && boat.x > 0) {
                boat.x -= boat.speed;
            }
            if (boat.movingRight && boat.x < canvas.width - boat.width) {
                boat.x += boat.speed;
            }

            // Generador de frecuencia de aparición
            if (Math.random() < 0.02 + (level * 0.005)) {
                spawnFaller();
            }

            // Actualizar objetos cayendo
            for (let i = fallers.length - 1; i >= 0; i--) {
                const f = fallers[i];
                f.y += f.speed;

                // Colisión con la barca
                if (f.y + f.size >= boat.y && 
                    f.x + f.size >= boat.x && 
                    f.x <= boat.x + boat.width && 
                    f.y <= boat.y + boat.height) {
                    
                    // Acción según el objeto atrapado
                    if (f.type.points > 0) {
                        score += f.type.points;
                        spawnParticles(f.x, f.y, f.type.color);
                        playSynthSound('catch');

                        if (f.type.isFilter && lives < 3) {
                            lives++;
                        }
                    } else if (f.type.penalty > 0) {
                        lives -= f.type.penalty;
                        spawnParticles(f.x, f.y, '#ef4444');
                        playSynthSound('damage');
                    }

                    fallers.splice(i, 1);
                    updateUI();
                    checkGameConditions();
                    continue;
                }

                // Salirse de la pantalla
                if (f.y > canvas.height) {
                    fallers.splice(i, 1);
                }
            }

            // Actualizar partículas
            for (let i = particles.length - 1; i >= 0; i--) {
                const p = particles[i];
                p.x += p.vx;
                p.y += p.vy;
                p.alpha -= p.decay;
                if (p.alpha <= 0) {
                    particles.splice(i, 1);
                }
            }

            // Ajustar niveles hídricos por puntuación
            if (score >= level * 60 && level < 3) {
                level++;
                updateUI();
            }
        }

        function drawGame() {
            ctx.clearRect(0, 0, canvas.width, canvas.height);

            // Dibujar ondas de fondo del río fluir suavemente
            ctx.fillStyle = 'rgba(56, 189, 248, 0.05)';
            for (let i = 0; i < 5; i++) {
                ctx.fillRect(0, 100 + (i * 60) + (Math.sin(Date.now() / 600 + i) * 10), canvas.width, 15);
            }

            // Dibujar objetos cayendo
            fallers.forEach(f => {
                ctx.font = `${f.size}px Arial`;
                ctx.textAlign = 'center';
                ctx.textBaseline = 'middle';
                ctx.fillText(f.type.char, f.x, f.y);
            });

            // Dibujar partículas
            particles.forEach(p => {
                ctx.fillStyle = p.color;
                ctx.globalAlpha = p.alpha;
                ctx.beginPath();
                ctx.arc(p.x, p.y, p.size, 0, Math.PI * 2);
                ctx.fill();
            });
            ctx.globalAlpha = 1.0; // Resetear alfa

            // Dibujar Barca Eco
            ctx.fillStyle = '#f59e0b'; // Color madera
            ctx.beginPath();
            ctx.moveTo(boat.x, boat.y + 10);
            ctx.lineTo(boat.x + 10, boat.y + boat.height);
            ctx.lineTo(boat.x + boat.width - 10, boat.y + boat.height);
            ctx.lineTo(boat.x + boat.width, boat.y + 10);
            ctx.closePath();
            ctx.fill();

            // Detalle blanco de la barca y escudo ecológico
            ctx.fillStyle = '#ffffff';
            ctx.fillRect(boat.x + 15, boat.y + 15, boat.width - 30, 8);
            ctx.fillStyle = '#10b981'; // Verde reciclaje
            ctx.font = '12px sans-serif';
            ctx.fillText('♻️', boat.x + boat.width/2, boat.y + 20);
        }

        function updateUI() {
            gameScoreEl.textContent = score;
            gameLevelEl.textContent = level;
            
            // Renderizar corazones
            let hearts = '';
            for (let i = 0; i < lives; i++) {
                hearts += '❤️';
            }
            if (lives === 0) hearts = '💀';
            gameLivesEl.textContent = hearts;
        }

        function checkGameConditions() {
            if (lives <= 0) {
                endGame(false);
            } else if (score >= 200) {
                endGame(true);
            }
        }

        function endGame(victory) {
            gameActive = false;
            gameOverlay.classList.remove('hidden');

            if (victory) {
                playSynthSound('win');
                overlayIcon.textContent = '👑';
                overlayTitle.textContent = '¡Victoria Ecologista!';
                overlayDesc.innerHTML = `Lograste purificar el caudal acumulando <span class="text-emerald-400 font-extrabold">${score} puntos</span>. ¡Tus acciones salvaron al ecosistema hídrico de la zona!`;
                btnPlay.textContent = 'Volver a Jugar';
            } else {
                playSynthSound('damage');
                overlayIcon.textContent = '☣️';
                overlayTitle.textContent = 'Caudal Contaminado';
                overlayDesc.innerHTML = `La contaminación superó la capacidad de tu barca. Lograste conseguir <span class="text-red-400 font-extrabold">${score} puntos</span>. ¡El planeta necesita que intentes de nuevo!`;
                btnPlay.textContent = 'Reintentar Misión';
            }
        }

        function startGame() {
            initAudio();
            score = 0;
            lives = 3;
            level = 1;
            fallers = [];
            particles = [];
            resetPlayer();
            updateUI();
            
            gameActive = true;
            gameOverlay.classList.add('hidden');
        }

        btnPlay.addEventListener('click', startGame);

        // Bucle Principal de Render y Físicas
        function gameLoop() {
            updateGame();
            drawGame();
            requestAnimationFrame(gameLoop);
        }
        
        // Iniciar en bucle inactivo esperando acción del usuario
        resetPlayer();
        gameLoop();
    </script>
</body>
</html>
