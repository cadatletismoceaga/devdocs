<!DOCTYPE html>
<html lang="gl">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>CEAGA - Centro de Ensino Atletismo Galego</title>
    <!-- Tailwind CSS para diseño moderno, dinámico y móvil -->
    <script src="https://cdn.tailwindcss.com"></script>
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.4.0/css/all.min.css">
    <style>
        html { scroll-behavior: smooth; }
    </style>
</head>
<body class="bg-gray-50 text-gray-800 font-sans">

    <!-- 1. CABECEIRA / NAV -->
    <header class="bg-white shadow-md sticky top-0 z-50">
        <div class="container mx-auto px-6 py-4 flex justify-between items-center">
            <!-- Identidad Corporativa -->
            <div class="flex items-center space-x-3">
                <div class="bg-slate-900 text-white font-bold px-3 py-1 rounded text-xl tracking-wider">CEAGA</div>
                <div class="hidden md:block border-l-2 border-gray-300 pl-3">
                    <p class="text-xs font-bold text-gray-500 tracking-wide uppercase">Centro de Ensino</p>
                    <p class="text-sm font-black text-red-600 uppercase tracking-tight">Atletismo Galego</p>
                </div>
            </div>
            
            <!-- Menú de Navegación -->
            <nav class="hidden lg:flex space-x-8 font-medium text-gray-600 items-center">
                <a href="#inicio" class="hover:text-red-600 transition">Inicio</a>
                <a href="#centro" class="hover:text-red-600 transition">O Centro</a>
                <a href="#ciclos" class="hover:text-red-600 transition">Ciclos Formativos</a>
                <a href="#metodoloxia" class="hover:text-red-600 transition">Metodoloxía</a>
                <a href="#secretaria" class="hover:text-red-600 transition">Secretaría</a>
                <!-- Botón de Acceso Destacado a Moodle -->
                <a href="https://ceaga.atletismo.gal/moodle" class="bg-red-600 text-white px-5 py-2.5 rounded-lg shadow-md font-bold hover:bg-red-700 transition flex items-center space-x-2">
                    <i class="fa-solid fa-graduation-cap"></i>
                    <span>AULA VIRTUAL</span>
                </a>
            </nav>
        </div>
    </header>

    <!-- 2. SECCIÓN DE INICIO / HERO BANNER -->
    <section id="inicio" class="relative bg-slate-900 text-white py-24 md:py-32 overflow-hidden">
        <div class="absolute inset-0 opacity-20 bg-cover bg-center" style="background-image: url('https://images.unsplash.com/photo-1502224562085-639556652f33?auto=format&fit=crop&w=1200&q=80');"></div>
        <div class="container mx-auto px-6 relative z-10 text-center max-w-4xl">
            <span class="bg-red-600 text-white text-xs font-bold uppercase tracking-widest px-3 py-1 rounded-full">Curso 2026/2027</span>
            <h1 class="text-4xl md:text-6xl font-black tracking-tight mt-4 uppercase">Centro de Ensino<br><span class="text-red-500">Atletismo Galego</span></h1>
            <p class="text-lg md:text-xl text-gray-300 mt-6 leading-relaxed">
                Centro privado autorizado pola Xunta de Galicia para a impartición das ensinanzas deportivas de réxime especial na modalidade de Atletismo.
            </p>
            <div class="mt-10 flex flex-col sm:flex-row justify-center items-center space-y-4 sm:space-y-0 sm:space-x-4">
                <a href="https://ceaga.atletismo.gal/moodle" class="w-full sm:w-auto bg-red-600 hover:bg-red-700 text-white font-bold px-8 py-4 rounded-xl shadow-lg transition text-center uppercase tracking-wide">
                    Entrar á Aula Virtual
                </a>
                <a href="#ciclos" class="w-full sm:w-auto bg-transparent border-2 border-white hover:bg-white hover:text-slate-900 text-white font-bold px-8 py-4 rounded-xl transition text-center uppercase tracking-wide">
                    Ver Oferta Formativa
                </a>
            </div>
        </div>
    </section>

    <!-- 3. SECCIÓN: O CENTRO / AUTORIZACIÓNS XUNTA -->
    <section id="centro" class="py-20 bg-white">
        <div class="container mx-auto px-6 max-w-6xl">
            <div class="text-center max-w-3xl mx-auto mb-16">
                <h2 class="text-3xl font-black text-slate-900 uppercase tracking-tight">Identificación e Transparencia</h2>
                <div class="h-1 w-20 bg-red-600 mx-auto mt-4"></div>
                <p class="text-gray-600 mt-4">O CEAGA conta con todas as garantías e autorizacións administrativas reguladas pola Consellería de Educación da Xunta de Galicia conforme ao Real decreto 1363/2007.</p>
            </div>

            <div class="grid grid-cols-1 lg:grid-cols-3 gap-8 items-stretch">
                <!-- Datos del centro -->
                <div class="bg-gray-50 p-8 rounded-2xl border border-gray-100 flex flex-col justify-between">
                    <div>
                        <h3 class="text-xl font-bold text-slate-900 mb-6 border-b pb-2">Datos Oficiais</h3>
                        <ul class="space-y-4 text-sm text-gray-600">
                            <li><strong class="text-slate-900 block">Denominación:</strong> Centro de Ensino Atletismo Galego (CEAGA)</li>
                            <li><strong class="text-slate-900 block">Código / CIF:</strong> G15103500</li>
                            <li><strong class="text-slate-900 block">Domicilio:</strong> Rúa de Bastiagueiro Pequeno, 15173 Oleiros (A Coruña)</li>
                            <li><strong class="text-slate-900 block">Titularidade:</strong> Federación Galega de Atletismo</li>
                        </ul>
                    </div>
                </div>

                <!-- Tabla de homologaciones DOGA -->
                <div class="lg:col-span-2 bg-gray-50 p-8 rounded-2xl border border-gray-100">
                    <h3 class="text-xl font-bold text-slate-900 mb-6 border-b pb-2">Autorizacións publicadas no DOGA</h3>
                    <div class="overflow-x-auto">
                        <table class="w-full text-left text-sm text-gray-600">
                            <thead>
                                <tr class="border-b border-gray-200 text-slate-900 font-bold">
                                    <th class="pb-3">Ensinanza Deportiva</th>
                                    <th class="pb-3 text-right">Publicación Oficial</th>
                                </tr>
                            </thead>
                            <tbody class="divide-y divide-gray-200">
                                <tr>
                                    <td class="py-3.5 font-semibold text-slate-900">Ciclo Inicial de Grao Medio</td>
                                    <td class="py-3.5 text-right text-red-600 font-medium">DOGA do 6 de agosto de 2021</td>
                                </tr>
                                <tr>
                                    <td class="py-3.5 font-semibold text-slate-900">Ciclo Final de Grao Medio</td>
                                    <td class="py-3.5 text-right text-red-600 font-medium">DOGA do 1 de abril do 2024</td>
                                </tr>
                                <tr>
                                    <td class="py-3.5 font-semibold text-slate-900">Ciclo Superior en Atletismo</td>
                                    <td class="py-3.5 text-right text-red-600 font-medium">DOGA do 11 de xullo de 2025</td>
                                </tr>
                            </tbody>
                        </table>
                    </div>
                    <p class="text-xs text-gray-400 mt-6"><i class="fa-solid fa-circle-info mr-1"></i> Ámbito territorial: Comunidade Autónoma de Galicia.</p>
                </div>
            </div>
        </div>
    </section>

    <!-- 4. SECCIÓN: CICLOS FORMATIVOS -->
    <section id="ciclos" class="py-20 bg-gray-100">
        <div class="container mx-auto px-6 max-w-6xl">
            <div class="text-center max-w-3xl mx-auto mb-16">
                <h2 class="text-3xl font-black text-slate-900 uppercase tracking-tight">Oferta Educativa por Ciclos</h2>
                <div class="h-1 w-20 bg-red-600 mx-auto mt-4"></div>
            </div>

            <div class="grid grid-cols-1 lg:grid-cols-3 gap-8">
                <!-- Tarjeta Ciclo Inicial -->
                <div class="bg-white rounded-2xl shadow-sm border border-gray-200 overflow-hidden flex flex-col justify-between">
                    <div class="p-6">
                        <div class="text-red-600 text-xs font-bold uppercase tracking-wider mb-2">Nivel 1</div>
                        <h3 class="text-xl font-bold text-slate-900 mb-4">Ciclo Inicial</h3>
                        <p class="text-gray-600 text-sm mb-6">Centrado nas bases do comportamento deportivo e a iniciación técnica no atletismo.</p>
                        <h4 class="text-xs font-bold text-gray-400 uppercase tracking-widest mb-3">Módulos a distancia</h4>
                        <ul class="space-y-2 text-xs text-gray-600 font-medium">
                            <li><i class="fa-solid fa-circle-check text-green-500 mr-2"></i>MED-C101: Bases do comportamento</li>
                            <li><i class="fa-solid fa-circle-check text-green-500 mr-2"></i>MED-C102: Primeiros auxilios</li>
                            <li><i class="fa-solid fa-circle-check text-green-500 mr-2"></i>MED-C103: Actividade física adaptada</li>
                            <li><i class="fa-solid fa-circle-check text-green-500 mr-2"></i>MED-C104: Organización deportiva</li>
                            <li><i class="fa-solid fa-circle-check text-green-500 mr-2"></i>ATAT103: Iniciación ao atletismo</li>
                        </ul>
                    </div>
                    <div class="p-6 bg-gray-50 border-t border-gray-100 text-xs text-gray-500">
                        <i class="fa-solid fa-location-dot text-red-500 mr-1"></i> Prácticas obrigatorias presenciais: 15h.
                    </div>
                </div>

                <!-- Tarjeta Ciclo Final -->
                <div class="bg-white rounded-2xl shadow-sm border border-gray-200 overflow-hidden flex flex-col justify-between">
                    <div class="p-6">
                        <div class="text-red-600 text-xs font-bold uppercase tracking-wider mb-2">Nivel 2</div>
                        <h3 class="text-xl font-bold text-slate-900 mb-4">Ciclo Final</h3>
                        <p class="text-gray-600 text-sm mb-6">Enfocado á tecnificación deportiva e ao adestramento de atletas en etapas intermedias.</p>
                        <h4 class="text-xs font-bold text-gray-400 uppercase tracking-widest mb-3">Módulos a distancia</h4>
                        <ul class="space-y-2 text-xs text-gray-600 font-medium">
                            <li><i class="fa-solid fa-circle-check text-green-500 mr-2"></i>MED-C201 ao C205 (Comúns)</li>
                            <li><i class="fa-solid fa-circle-check text-green-500 mr-2"></i>ATAT204: Regulamento oficial</li>
                            <li><i class="fa-solid fa-circle-check text-green-500 mr-2"></i>ATAT205: Adestramento condicional</li>
                            <li><i class="fa-solid fa-circle-check text-green-500 mr-2"></i>ATAT206: Organización do atletismo</li>
                            <li><i class="fa-solid fa-circle-check text-green-500 mr-2"></i>ATAT207: Atletismo adaptado</li>
                        </ul>
                    </div>
                    <div class="p-6 bg-gray-50 border-t border-gray-100 text-xs text-gray-500">
                        <i class="fa-solid fa-location-dot text-red-500 mr-1"></i> Prácticas obrigatorias de especialidade: 10h.
                    </div>
                </div>

                <!-- Tarjeta Ciclo Superior -->
                <div class="bg-white rounded-2xl shadow-sm border border-gray-200 overflow-hidden flex flex-col justify-between">
                    <div class="p-6">
                        <div class="text-red-600 text-xs font-bold uppercase tracking-wider mb-2">Nivel 3</div>
                        <h3 class="text-xl font-bold text-slate-900 mb-4">Ciclo Superior</h3>
                        <p class="text-gray-600 text-sm mb-6">Preparación orientada ao alto rendemento deportivo, dirección técnica e xestión de escolas.</p>
                        <h4 class="text-xs font-bold text-gray-400 uppercase tracking-widest mb-3">Módulos a distancia</h4>
                        <ul class="space-y-2 text-xs text-gray-600 font-medium">
                            <li><i class="fa-solid fa-circle-check text-green-500 mr-2"></i>MED-C301 ao C304 (Comúns)</li>
                            <li><i class="fa-solid fa-circle-check text-green-500 mr-2"></i>ATAT305: Planificación condicional</li>
                            <li><i class="fa-solid fa-circle-check text-green-500 mr-2"></i>ATAT306: Dirección técnica</li>
                            <li><i class="fa-solid fa-circle-check text-green-500 mr-2"></i>ATAT307: Módulo de Proxecto</li>
                        </ul>
                    </div>
                    <div class="p-6 bg-gray-50 border-t border-gray-100 text-xs text-gray-500">
                        <i class="fa-solid fa-location-dot text-red-500 mr-1"></i> Carga práctica presencial obrigatoria establecida.
                    </div>
                </div>
            </div>
        </div>
    </section>

    <!-- 5. SECCIÓN: METODOLOXÍA / ENSINANZA A DISTANCIA -->
    <section id="metodoloxia" class="py-20 bg-white">
        <div class="container mx-auto px-6 max-w-5xl">
            <div class="text-center max-w-3xl mx-auto mb-16">
                <h2 class="text-3xl font-black text-slate-900 uppercase tracking-tight">Modelo Semipresencial Interactivo</h2>
                <div class="h-1 w-20 bg-red-600 mx-auto mt-4"></div>
                <p class="text-gray-600 mt-4">Cumprindo estritamente a Orde do 22 de xullo de 2021 que regula o ensino a distancia nas ensinanzas deportivas de réxime especial en Galicia.</p>
            </div>

            <div class="grid grid-cols-1 md:grid-cols-2 gap-8">
                <div class="flex items-start space-x-4">
                    <div class="bg-red-100 text-red-600 p-3 rounded-xl"><i class="fa-solid fa-book-open text-xl"></i></div>
                    <div>
                        <h3 class="text-lg font-bold text-slate-900 mb-1">Guías e Programacións Oficiais</h3>
                        <p class="text-sm text-gray-600">Cada módulo conta cunha guía didáctica detallada con prazos de entrega, contidos e os criterios estritos de cualificación.</p>
                    </div>
                </div>
                <div class="flex items-start space-x-4">
                    <div class="bg-red-100 text-red-600 p-3 rounded-xl"><i class="fa-solid fa-circle-nodes text-xl"></i></div>
                    <div>
                        <h3 class="text-lg font-bold text-slate-900 mb-1">Materiais Multimedia e Autoavaliación</h3>
                        <p class="text-sm text-gray-600">Apuntes do profesorado acompañados de diapositivas, recursos audiovisuais clave e tests con solución interactiva inmediata.</p>
                    </div>
                </div>
                <div class="flex items-start space-x-4">
                    <div class="bg-red-100 text-red-600 p-3 rounded-xl"><i class="fa-solid fa-comments text-xl"></i></div>
                    <div>
                        <h3 class="text-lg font-bold text-slate-900 mb-1">Titorías e Orientación Continua</h3>
                        <p class="text-sm text-gray-600">Canles de comunicación aberta semanais vía telemática síncrona e foros dedicados para a resolución individualizada de dúbidas.</p>
                    </div>
                </div>
                <div class="flex items-start space-x-4">
                    <div class="bg-red-100 text-red-600 p-3 rounded-xl"><i class="fa-solid fa-clipboard-check text-xl"></i></div>
                    <div>
                        <h3 class="text-lg font-bold text-slate-900 mb-1">Avaliación Continua Telemática</h3>
                        <p class="text-sm text-gray-600">Esíxese o seguimento activo, participación nos foros e a realización das tarefas programadas nos prazos determinados en liña.</p>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <!-- 6. SECCIÓN: SECRETARÍA E DOCUMENTACIÓN -->
    <section id="secretaria" class="py-20 bg-gray-50 border-t border-b border-gray-200">
        <div class="container mx-auto px-6 max-w-4xl text-center">
            <h2 class="text-3xl font-black text-slate-900 uppercase tracking-tight mb-4">Área de Secretaría</h2>
            <p class="text-gray-600 mb-10 max-w-2xl mx-auto">Consulta os prazos de matrícula para o Curso 2026/2027 e descarga de forma pública a documentación obrigatoria de ordenación académica.</p>
            
            <div class="bg-white p-6 rounded-2xl shadow-sm border border-gray-200 text-left max-w-xl mx-auto">
                <h3 class="font-bold text-slate-900 mb-4 flex items-center"><i class="fa-solid fa-folder-open text-red-600 mr-2"></i> Documentación Oficial Descargable</h3>
                <div class="space-y-3">
                    <div class="flex justify-between items-center p-3 hover:bg-gray-50 rounded-xl transition border border-transparent hover:border-gray-100">
                        <span class="text-sm text-gray-700 font-medium"><i class="fa-regular fa-file-pdf text-red-500 mr-2"></i> Proxecto de Ensinanza a Distancia 2026</span>
                        <span class="text-xs bg-gray-100 px-2 py-1 rounded text-gray-500 font-bold">PDF</span>
                    </div>
                    <div class="flex justify-between items-center p-3 hover:bg-gray-50 rounded-xl transition border border-transparent hover:border-gray-100">
                        <span class="text-sm text-gray-700 font-medium"><i class="fa-regular fa-file-pdf text-red-500 mr-2"></i> Formulario de Inscrición e Matrícula</span>
                        <span class="text-xs bg-gray-100 px-2 py-1 rounded text-gray-500 font-bold">PDF</span>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <!-- 7. PÉ DE PÁXINA / FOOTER -->
    <footer class="bg-slate-900 text-gray-400 py-12 text-sm border-t border-slate-800">
        <div class="container mx-auto px-6 text-center space-y-4">
            <p class="text-white font-bold uppercase tracking-wider">CEAGA - Centro de Ensino Atletismo Galego</p>
            <p>Rúa de Bastiagueiro Pequeno, 15173 Oleiros (A Coruña) — Correo oficial: <a href="mailto:ensino@atletismo.gal" class="text-red-400 hover:underline">ensino@atletismo.gal</a></p>
            <div class="pt-6 border-t border-slate-800 flex flex-col md:flex-row justify-between items-center text-xs text-gray-500 space-y-4 md:space-y-0">
                <p>&copy; 2026 CEAGA. Todos os dereitos reservados. Centro autorizado pola Xunta de Galicia.</p>
                <div class="space-x-4">
                    <a href="#" class="hover:text-white transition">Aviso Legal</a>
                    <a href="#" class="hover:text-white transition">Política de Privacidade</a>
                    <a href="#" class="hover:text-white transition">Cookies</a>
                </div>
            </div>
        </div>
    </footer>

</body>
</html>
