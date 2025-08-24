<!DOCTYPE html>
<html lang="es" class="scroll-smooth">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Sergio De La Hoz – Analista de Datos Junior</title>
  <meta name="description" content="Portafolio de Sergio De La Hoz, Analista de Datos Junior. Proyectos de dashboards, limpieza y transformación de datos con Python, SQL, Power BI." />
  <meta name="theme-color" content="#0ea5e9"/>
  <link rel="preconnect" href="https://fonts.googleapis.com">
  <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
  <link href="https://fonts.googleapis.com/css2?family=Inter:wght@300;400;500;600;700;800&display=swap" rel="stylesheet">
  <script src="https://cdn.tailwindcss.com"></script>
  <script>
    tailwind.config = {
      theme: {
        extend: {
          fontFamily: { sans: ["Inter", "ui-sans-serif", "system-ui"] },
          colors: {
            brand: {
              50: '#ecfeff', 100: '#cffafe', 200: '#a5f3fc', 300: '#67e8f9',
              400: '#22d3ee', 500: '#06b6d4', 600: '#0891b2', 700: '#0e7490', 800: '#155e75', 900: '#164e63'
            }
          },
          boxShadow: {
            soft: '0 10px 25px -10px rgba(2, 132, 199, 0.25)'
          }
        }
      },
      darkMode: 'class'
    }
  </script>
  <style>
    /* Suaviza el scroll en anclas para Safari viejitos */
    html { scroll-behavior: smooth; }
  </style>
</head>
<body class="bg-white text-slate-800 dark:bg-slate-950 dark:text-slate-100">
  <!-- Header / Navbar -->
  <header class="sticky top-0 z-50 backdrop-blur supports-[backdrop-filter]:bg-white/70 dark:supports-[backdrop-filter]:bg-slate-950/60 border-b border-slate-200/60 dark:border-slate-800">
    <div class="mx-auto max-w-7xl px-4 sm:px-6 lg:px-8 h-16 flex items-center justify-between">
      <a href="#inicio" class="flex items-center gap-3">
        <div class="h-9 w-9 rounded-xl bg-gradient-to-br from-brand-500 to-sky-600 text-white grid place-content-center font-bold shadow-soft">SD</div>
        <span class="font-semibold">Sergio De La Hoz</span>
        <span class="hidden sm:inline text-sm text-slate-500 dark:text-slate-400">· Analista de Datos Junior</span>
      </a>
      <nav class="hidden md:flex items-center gap-6 text-sm">
        <a href="#sobre-mi" class="hover:text-brand-600 dark:hover:text-brand-300">Sobre mí</a>
        <a href="#habilidades" class="hover:text-brand-600 dark:hover:text-brand-300">Habilidades</a>
        <a href="#proyectos" class="hover:text-brand-600 dark:hover:text-brand-300">Proyectos</a>
        <a href="#certificaciones" class="hover:text-brand-600 dark:hover:text-brand-300">Certificaciones</a>
        <a href="#contacto" class="hover:text-brand-600 dark:hover:text-brand-300">Contacto</a>
      </nav>
      <div class="flex items-center gap-2">
        <button id="themeToggle" class="p-2 rounded-xl hover:bg-slate-100 dark:hover:bg-slate-800" aria-label="Cambiar tema">
          <svg id="sun" xmlns="http://www.w3.org/2000/svg" class="h-5 w-5 hidden dark:block" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2"><path d="M12 3v2M12 19v2M5.64 5.64l1.41 1.41M16.95 16.95l1.41 1.41M3 12h2M19 12h2M5.64 18.36l1.41-1.41M16.95 7.05l1.41-1.41"/><circle cx="12" cy="12" r="4"/></svg>
          <svg id="moon" xmlns="http://www.w3.org/2000/svg" class="h-5 w-5 dark:hidden" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2"><path d="M21 12.79A9 9 0 1 1 11.21 3 7 7 0 0 0 21 12.79z"/></svg>
        </button>
        <a href="#contacto" class="hidden sm:inline-flex items-center gap-2 rounded-xl bg-brand-600 px-3 py-2 text-white hover:bg-brand-700 shadow-soft">
          <svg xmlns="http://www.w3.org/2000/svg" class="h-4 w-4" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2"><path d="M21 10a8.38 8.38 0 0 1-.9 3.8 8.5 8.5 0 1 1 0-7.6A8.38 8.38 0 0 1 21 10z"/><line x1="22" y1="2" x2="16" y2="8"/></svg>
          Contáctame
        </a>
      </div>
    </div>
  </header>

  <!-- Hero -->
  <section id="inicio" class="relative overflow-hidden">
    <div class="mx-auto max-w-7xl px-4 sm:px-6 lg:px-8 py-20 md:py-28 grid md:grid-cols-2 gap-10 items-center">
      <div>
        <span class="inline-flex items-center gap-2 rounded-full border border-brand-200/60 dark:border-brand-900/50 bg-brand-50 dark:bg-slate-900 px-3 py-1 text-xs text-brand-700 dark:text-brand-200">Disponible para prácticas / junior</span>
        <h1 class="mt-4 text-4xl md:text-5xl font-extrabold leading-tight">Analista de Datos Junior<br><span class="text-transparent bg-clip-text bg-gradient-to-r from-brand-600 to-sky-500">Sergio De La Hoz</span></h1>
        <p class="mt-4 text-slate-600 dark:text-slate-300 max-w-[60ch]">Estudiante de Ingeniería de Sistemas (10° semestre) en la Universidad Popular del Cesar. Transformo datos en información accionable mediante <strong>Python, SQL y Power BI</strong>. Experiencia construyendo dashboards, limpiezas de datos y EDA.</p>
        <div class="mt-6 flex flex-wrap gap-3">
          <a href="#proyectos" class="inline-flex items-center gap-2 rounded-xl bg-brand-600 px-4 py-2.5 text-white hover:bg-brand-700 shadow-soft">Ver proyectos</a>
          <a href="#contacto" class="inline-flex items-center gap-2 rounded-xl border border-slate-300 dark:border-slate-700 px-4 py-2.5 hover:bg-slate-50 dark:hover:bg-slate-800">Contacto</a>
        </div>
        <div class="mt-8 flex items-center gap-4 text-sm text-slate-500 dark:text-slate-400">
          <span class="inline-flex items-center gap-2"><svg class="w-4 h-4" fill="none" stroke="currentColor" viewBox="0 0 24 24" stroke-width="2"><path d="M17.657 16.657L13.414 12l4.243-4.243M6.343 7.343L10.586 12l-4.243 4.243"></path></svg> Python, Pandas, SQL</span>
          <span class="inline-flex items-center gap-2"><svg class="w-4 h-4" fill="none" stroke="currentColor" viewBox="0 0 24 24" stroke-width="2"><path d="M12 20l9-5-9-5-9 5 9 5z"></path><path d="M12 12l9-5-9-5-9 5 9 5z"></path></svg> Power BI, Excel</span>
        </div>
      </div>
      <div class="relative">
        <div class="aspect-[4/3] w-full rounded-2xl bg-gradient-to-tr from-sky-100 to-brand-50 dark:from-slate-800 dark:to-slate-900 border border-slate-200 dark:border-slate-800 p-3">
          <!-- Reemplaza src con tu imagen o avatar -->
          <img src="https://images.unsplash.com/photo-1542744173-05336fcc7ad4?q=80&w=1200&auto=format&fit=crop" alt="Ilustración de análisis de datos" class="h-full w-full object-cover rounded-xl"/>
        </div>
        <div class="absolute -bottom-6 -left-6 hidden lg:block bg-white/80 dark:bg-slate-900/80 backdrop-blur rounded-2xl border border-slate-200 dark:border-slate-800 p-4 shadow-soft">
          <p class="text-xs text-slate-600 dark:text-slate-300">+20 notebooks / dashboards educativos y personales.<br> Enfoque en limpieza, EDA y visualización.</p>
        </div>
      </div>
    </div>
  </section>

  <!-- Sobre mí -->
  <section id="sobre-mi" class="py-16 md:py-24 border-t border-slate-200 dark:border-slate-800">
    <div class="mx-auto max-w-4xl px-4 sm:px-6 lg:px-8">
      <h2 class="text-2xl md:text-3xl font-bold">Sobre mí</h2>
      <p class="mt-4 text-slate-600 dark:text-slate-300">Soy estudiante de décimo semestre de <strong>Ingeniería de Sistemas</strong> en la <strong>Universidad Popular del Cesar</strong> (Valledupar). Tengo experiencia en desarrollo de aplicaciones (móvil, web y escritorio) y actualmente me enfoco en el <strong>análisis de datos</strong>: limpieza, transformación, modelado y visualización para toma de decisiones.</p>
      <p class="mt-3 text-slate-600 dark:text-slate-300">Participo en una empresa internacional (Outlier) evaluando prompts y respuestas generadas por IA, fortaleciendo mis habilidades de <strong>razonamiento, documentación y criterios de calidad</strong>. Busco una oportunidad junior o de prácticas para aportar valor a equipos de datos.</p>
      <dl class="mt-6 grid grid-cols-1 sm:grid-cols-2 gap-4 text-sm">
        <div class="rounded-xl border border-slate-200 dark:border-slate-800 p-4">
          <dt class="font-semibold">Ubicación</dt>
          <dd class="text-slate-600 dark:text-slate-300">Valledupar, Cesar – Colombia</dd>
        </div>
        <div class="rounded-xl border border-slate-200 dark:border-slate-800 p-4">
          <dt class="font-semibold">Disponibilidad</dt>
          <dd class="text-slate-600 dark:text-slate-300">Remoto / Híbrido / Presencial (Colombia)</dd>
        </div>
      </dl>
    </div>
  </section>

  <!-- Habilidades -->
  <section id="habilidades" class="py-16 md:py-24">
    <div class="mx-auto max-w-7xl px-4 sm:px-6 lg:px-8">
      <h2 class="text-2xl md:text-3xl font-bold">Habilidades</h2>
      <div class="mt-6 grid md:grid-cols-2 gap-8">
        <div class="rounded-2xl border border-slate-200 dark:border-slate-800 p-6">
          <h3 class="font-semibold">Datos · Core</h3>
          <ul class="mt-4 flex flex-wrap gap-2 text-sm">
            <li class="px-3 py-1 rounded-full bg-slate-100 dark:bg-slate-800">Python</li>
            <li class="px-3 py-1 rounded-full bg-slate-100 dark:bg-slate-800">Pandas</li>
            <li class="px-3 py-1 rounded-full bg-slate-100 dark:bg-slate-800">NumPy</li>
            <li class="px-3 py-1 rounded-full bg-slate-100 dark:bg-slate-800">Matplotlib/Seaborn</li>
            <li class="px-3 py-1 rounded-full bg-slate-100 dark:bg-slate-800">SQL</li>
            <li class="px-3 py-1 rounded-full bg-slate-100 dark:bg-slate-800">Power BI</li>
            <li class="px-3 py-1 rounded-full bg-slate-100 dark:bg-slate-800">Excel</li>
            <li class="px-3 py-1 rounded-full bg-slate-100 dark:bg-slate-800">Talend</li>
            <li class="px-3 py-1 rounded-full bg-slate-100 dark:bg-slate-800">Tableau (básico)</li>
          </ul>
        </div>
        <div class="rounded-2xl border border-slate-200 dark:border-slate-800 p-6">
          <h3 class="font-semibold">Programación · Soporte</h3>
          <ul class="mt-4 flex flex-wrap gap-2 text-sm">
            <li class="px-3 py-1 rounded-full bg-slate-100 dark:bg-slate-800">C#</li>
            <li class="px-3 py-1 rounded-full bg-slate-100 dark:bg-slate-800">Java</li>
            <li class="px-3 py-1 rounded-full bg-slate-100 dark:bg-slate-800">JavaScript</li>
            <li class="px-3 py-1 rounded-full bg-slate-100 dark:bg-slate-800">Dart/Flutter</li>
            <li class="px-3 py-1 rounded-full bg-slate-100 dark:bg-slate-800">UX/UI</li>
          </ul>
          <p class="mt-4 text-sm text-slate-600 dark:text-slate-300">Conocimientos complementarios aplicados a proyectos educativos y personales.</p>
        </div>
      </div>
    </div>
  </section>

  <!-- Proyectos -->
  <section id="proyectos" class="py-16 md:py-24 bg-slate-50 dark:bg-slate-900/40 border-y border-slate-200 dark:border-slate-800">
    <div class="mx-auto max-w-7xl px-4 sm:px-6 lg:px-8">
      <div class="flex items-end justify-between gap-4 flex-wrap">
        <div>
          <h2 class="text-2xl md:text-3xl font-bold">Proyectos</h2>
          <p class="mt-2 text-slate-600 dark:text-slate-300">Dashboards, EDA y procesos de limpieza/transformación. Cada tarjeta enlaza a GitHub, Power BI Service o Notebook.</p>
        </div>
        <div class="flex gap-2 text-sm" role="group" aria-label="Filtros de proyectos">
          <button data-filter="all" class="filter-btn px-3 py-1.5 rounded-lg border border-slate-300 dark:border-slate-700 hover:bg-slate-100 dark:hover:bg-slate-800">Todos</button>
          <button data-filter="dashboard" class="filter-btn px-3 py-1.5 rounded-lg border border-slate-300 dark:border-slate-700 hover:bg-slate-100 dark:hover:bg-slate-800">Dashboards</button>
          <button data-filter="eda" class="filter-btn px-3 py-1.5 rounded-lg border border-slate-300 dark:border-slate-700 hover:bg-slate-100 dark:hover:bg-slate-800">EDA</button>
          <button data-filter="limpieza" class="filter-btn px-3 py-1.5 rounded-lg border border-slate-300 dark:border-slate-700 hover:bg-slate-100 dark:hover:bg-slate-800">Limpieza</button>
        </div>
      </div>

      <div id="gridProyectos" class="mt-8 grid grid-cols-1 md:grid-cols-2 lg:grid-cols-3 gap-6">
        <!-- Card Proyecto 1 -->
        <article class="card group" data-tags="dashboard">
          <a href="#" target="_blank" rel="noopener" class="block rounded-2xl overflow-hidden border border-slate-200 dark:border-slate-800 bg-white dark:bg-slate-900">
            <div class="aspect-[16/9] bg-slate-100 dark:bg-slate-800 overflow-hidden">
              <img src="https://images.unsplash.com/photo-1543286386-713bdd548da4?q=80&w=1280&auto=format&fit=crop" alt="Dashboard de Ventas" class="w-full h-full object-cover group-hover:scale-[1.03] transition"/>
            </div>
            <div class="p-5">
              <h3 class="font-semibold">Dashboard de Ventas e Inventario</h3>
              <p class="mt-1 text-sm text-slate-600 dark:text-slate-300">Power BI · KPI: ingresos, rotación, top productos, quiebres de stock.</p>
              <div class="mt-3 flex flex-wrap gap-2 text-xs">
                <span class="px-2 py-1 rounded bg-slate-100 dark:bg-slate-800">Power BI</span>
                <span class="px-2 py-1 rounded bg-slate-100 dark:bg-slate-800">DAX</span>
                <span class="px-2 py-1 rounded bg-slate-100 dark:bg-slate-800">Data Modeling</span>
              </div>
            </div>
          </a>
        </article>

        <!-- Card Proyecto 2 -->
        <article class="card group" data-tags="eda limpieza">
          <a href="#" target="_blank" rel="noopener" class="block rounded-2xl overflow-hidden border border-slate-200 dark:border-slate-800 bg-white dark:bg-slate-900">
            <div class="aspect-[16/9] bg-slate-100 dark:bg-slate-800 overflow-hidden">
              <img src="https://images.unsplash.com/photo-1554475901-4538ddfbccc2?q=80&w=1280&auto=format&fit=crop" alt="EDA clientes" class="w-full h-full object-cover group-hover:scale-[1.03] transition"/>
            </div>
            <div class="p-5">
              <h3 class="font-semibold">EDA de Comportamiento de Clientes</h3>
              <p class="mt-1 text-sm text-slate-600 dark:text-slate-300">Python · Segmentación simple, RFM, outliers, correlaciones.</p>
              <div class="mt-3 flex flex-wrap gap-2 text-xs">
                <span class="px-2 py-1 rounded bg-slate-100 dark:bg-slate-800">Python</span>
                <span class="px-2 py-1 rounded bg-slate-100 dark:bg-slate-800">Pandas</span>
                <span class="px-2 py-1 rounded bg-slate-100 dark:bg-slate-800">Matplotlib</span>
              </div>
            </div>
          </a>
        </article>

        <!-- Card Proyecto 3 -->
        <article class="card group" data-tags="limpieza">
          <a href="#" target="_blank" rel="noopener" class="block rounded-2xl overflow-hidden border border-slate-200 dark:border-slate-800 bg-white dark:bg-slate-900">
            <div class="aspect-[16/9] bg-slate-100 dark:bg-slate-800 overflow-hidden">
              <img src="https://images.unsplash.com/photo-1556157382-97eda2d62296?q=80&w=1280&auto=format&fit=crop" alt="Limpieza de datos retail" class="w-full h-full object-cover group-hover:scale-[1.03] transition"/>
            </div>
            <div class="p-5">
              <h3 class="font-semibold">Limpieza & Normalización (Retail)</h3>
              <p class="mt-1 text-sm text-slate-600 dark:text-slate-300">Tratamiento de nulos/duplicados, casting de tipos, reglas de negocio.</p>
              <div class="mt-3 flex flex-wrap gap-2 text-xs">
                <span class="px-2 py-1 rounded bg-slate-100 dark:bg-slate-800">Python</span>
                <span class="px-2 py-1 rounded bg-slate-100 dark:bg-slate-800">Pandas</span>
                <span class="px-2 py-1 rounded bg-slate-100 dark:bg-slate-800">Data Quality</span>
              </div>
            </div>
          </a>
        </article>

        <!-- Card Proyecto 4 -->
        <article class="card group" data-tags="dashboard">
          <a href="#" target="_blank" rel="noopener" class="block rounded-2xl overflow-hidden border border-slate-200 dark:border-slate-800 bg-white dark:bg-slate-900">
            <div class="aspect-[16/9] bg-slate-100 dark:bg-slate-800 overflow-hidden">
              <img src="https://images.unsplash.com/photo-1600267175161-cfaa711b4a81?q=80&w=1280&auto=format&fit=crop" alt="Dashboard RRHH" class="w-full h-full object-cover group-hover:scale-[1.03] transition"/>
            </div>
            <div class="p-5">
              <h3 class="font-semibold">Dashboard de RR.HH. (Ausentismo)</h3>
              <p class="mt-1 text-sm text-slate-600 dark:text-slate-300">Indicadores de rotación, ausencias, horas extra e insights por área.</p>
              <div class="mt-3 flex flex-wrap gap-2 text-xs">
                <span class="px-2 py-1 rounded bg-slate-100 dark:bg-slate-800">Power BI</span>
                <span class="px-2 py-1 rounded bg-slate-100 dark:bg-slate-800">DAX</span>
                <span class="px-2 py-1 rounded bg-slate-100 dark:bg-slate-800">ETL</span>
              </div>
            </div>
          </a>
        </article>

        <!-- Card Proyecto 5 -->
        <article class="card group" data-tags="eda">
          <a href="#" target="_blank" rel="noopener" class="block rounded-2xl overflow-hidden border border-slate-200 dark:border-slate-800 bg-white dark:bg-slate-900">
            <div class="aspect-[16/9] bg-slate-100 dark:bg-slate-800 overflow-hidden">
              <img src="https://images.unsplash.com/photo-1542326237-94b1c5a538d3?q=80&w=1280&auto=format&fit=crop" alt="Análisis de churn" class="w-full h-full object-cover group-hover:scale-[1.03] transition"/>
            </div>
            <div class="p-5">
              <h3 class="font-semibold">Análisis de Churn (Telecom)</h3>
              <p class="mt-1 text-sm text-slate-600 dark:text-slate-300">EDA de abandono de clientes con métricas descriptivas y visuales.</p>
              <div class="mt-3 flex flex-wrap gap-2 text-xs">
                <span class="px-2 py-1 rounded bg-slate-100 dark:bg-slate-800">Python</span>
                <span class="px-2 py-1 rounded bg-slate-100 dark:bg-slate-800">Pandas</span>
                <span class="px-2 py-1 rounded bg-slate-100 dark:bg-slate-800">Seaborn</span>
              </div>
            </div>
          </a>
        </article>

        <!-- Card Proyecto 6 -->
        <article class="card group" data-tags="limpieza">
          <a href="#" target="_blank" rel="noopener" class="block rounded-2xl overflow-hidden border border-slate-200 dark:border-slate-800 bg-white dark:bg-slate-900">
            <div class="aspect-[16/9] bg-slate-100 dark:bg-slate-800 overflow-hidden">
              <img src="https://images.unsplash.com/photo-1580894894513-541292a8dc85?q=80&w=1280&auto=format&fit=crop" alt="Pipeline Talend" class="w-full h-full object-cover group-hover:scale-[1.03] transition"/>
            </div>
            <div class="p-5">
              <h3 class="font-semibold">ETL con Talend (Dimensionamiento)</h3>
              <p class="mt-1 text-sm text-slate-600 dark:text-slate-300">Pipeline de integración de datos y carga a modelo dimensional.</p>
              <div class="mt-3 flex flex-wrap gap-2 text-xs">
                <span class="px-2 py-1 rounded bg-slate-100 dark:bg-slate-800">Talend</span>
                <span class="px-2 py-1 rounded bg-slate-100 dark:bg-slate-800">ETL</span>
                <span class="px-2 py-1 rounded bg-slate-100 dark:bg-slate-800">Data Warehouse</span>
              </div>
            </div>
          </a>
        </article>
      </div>

      <p class="mt-6 text-sm text-slate-500 dark:text-slate-400">Tip: reemplaza los enlaces <em>#</em> por tus URLs de GitHub / Power BI Service / Kaggle / nbviewer. Sube capturas a /assets/ y actualiza las imágenes.</p>
    </div>
  </section>

  <!-- Certificaciones -->
  <section id="certificaciones" class="py-16 md:py-24">
    <div class="mx-auto max-w-7xl px-4 sm:px-6 lg:px-8">
      <h2 class="text-2xl md:text-3xl font-bold">Certificaciones</h2>
      <div class="mt-6 grid grid-cols-1 md:grid-cols-3 gap-6">
        <div class="rounded-2xl border border-slate-200 dark:border-slate-800 p-5">
          <h3 class="font-semibold">Talento Tech</h3>
          <p class="text-sm text-slate-600 dark:text-slate-300">Ruta Analista de Datos</p>
          <a href="#" class="mt-3 inline-block text-brand-700 dark:text-brand-300 hover:underline text-sm">Ver certificado</a>
        </div>
        <div class="rounded-2xl border border-slate-200 dark:border-slate-800 p-5">
          <h3 class="font-semibold">Google – Coursera</h3>
          <p class="text-sm text-slate-600 dark:text-slate-300">Google Data Analytics (en curso)</p>
          <a href="#" class="mt-3 inline-block text-brand-700 dark:text-brand-300 hover:underline text-sm">Ver progreso</a>
        </div>
        <div class="rounded-2xl border border-slate-200 dark:border-slate-800 p-5">
          <h3 class="font-semibold">Otros</h3>
          <ul class="text-sm text-slate-600 dark:text-slate-300 list-disc pl-5 mt-1">
            <li>Insignias y certificados de CISCO (redes)</li>
            <li>Oracle Database Foundations</li>
            <li>Certificado en habilidades blandas</li>
          </ul>
        </div>
      </div>
    </div>
  </section>

  <!-- Contacto -->
  <section id="contacto" class="py-16 md:py-24 bg-slate-50 dark:bg-slate-900/40 border-t border-slate-200 dark:border-slate-800">
    <div class="mx-auto max-w-3xl px-4 sm:px-6 lg:px-8">
      <h2 class="text-2xl md:text-3xl font-bold">Contacto</h2>
      <p class="mt-2 text-slate-600 dark:text-slate-300">¿Hablamos? Estoy abierto a oportunidades junior o prácticas en análisis de datos.</p>
      <div class="mt-6 grid gap-4">
        <a href="mailto:sddelahoz@unicesar.edu.co" class="flex items-center gap-3 p-4 rounded-xl border border-slate-200 dark:border-slate-800 hover:bg-white dark:hover:bg-slate-900">
          <span class="inline-grid place-content-center h-9 w-9 rounded-lg bg-brand-600 text-white">@</span>
          <div>
            <div class="font-semibold">sddelahoz@unicesar.edu.co</div>
            <div class="text-sm text-slate-500 dark:text-slate-400">Correo electrónico</div>
          </div>
        </a>
        <a href="https://github.com/SergioDeLaHoz" target="_blank" rel="noopener" class="flex items-center gap-3 p-4 rounded-xl border border-slate-200 dark:border-slate-800 hover:bg-white dark:hover:bg-slate-900">
          <span class="inline-grid place-content-center h-9 w-9 rounded-lg bg-slate-900 text-white">GH</span>
          <div>
            <div class="font-semibold">github.com/SergioDeLaHoz</div>
            <div class="text-sm text-slate-500 dark:text-slate-400">GitHub</div>
          </div>
        </a>
        <a href="https://wa.me/573186863938" target="_blank" rel="noopener" class="flex items-center gap-3 p-4 rounded-xl border border-slate-200 dark:border-slate-800 hover:bg-white dark:hover:bg-slate-900">
          <span class="inline-grid place-content-center h-9 w-9 rounded-lg bg-emerald-600 text-white">WA</span>
          <div>
            <div class="font-semibold">+57 318 686 3938</div>
            <div class="text-sm text-slate-500 dark:text-slate-400">WhatsApp</div>
          </div>
        </a>
      </div>
      <p class="mt-6 text-xs text-slate-500 dark:text-slate-400">También disponible en LinkedIn (compárteme tu enlace y lo agrego).</p>
    </div>
  </section>

  <!-- Footer -->
  <footer class="py-10">
    <div class="mx-auto max-w-7xl px-4 sm:px-6 lg:px-8 text-sm text-slate-500 dark:text-slate-400 flex flex-col md:flex-row items-center justify-between gap-4">
      <p>© <span id="year"></span> Sergio De La Hoz. Hecho con HTML + TailwindCSS.</p>
      <div class="flex items-center gap-3">
        <a href="#inicio" class="hover:text-brand-600 dark:hover:text-brand-300">Inicio</a>
        <span aria-hidden="true">·</span>
        <a href="#proyectos" class="hover:text-brand-600 dark:hover:text-brand-300">Proyectos</a>
      </div>
    </div>
  </footer>

  <!-- Scripts -->
  <script>
    // Tema (dark/light) con persistencia en localStorage
    const html = document.documentElement;
    const themeToggle = document.getElementById('themeToggle');
    const stored = localStorage.getItem('theme');
    if (stored === 'dark' || (!stored && window.matchMedia('(prefers-color-scheme: dark)').matches)) {
      html.classList.add('dark');
    }
    themeToggle?.addEventListener('click', () => {
      html.classList.toggle('dark');
      const isDark = html.classList.contains('dark');
      localStorage.setItem('theme', isDark ? 'dark' : 'light');
    });

    // Año footer
    document.getElementById('year').textContent = new Date().getFullYear();

    // Filtros de proyectos
    const buttons = document.querySelectorAll('.filter-btn');
    const cards = document.querySelectorAll('#gridProyectos .card');
    buttons.forEach(btn => btn.addEventListener('click', () => {
      const f = btn.getAttribute('data-filter');
      buttons.forEach(b => b.classList.remove('bg-brand-600','text-white'));
      btn.classList.add('bg-brand-600','text-white');
      cards.forEach(card => {
        const tags = card.getAttribute('data-tags') || '';
        const show = f === 'all' || tags.includes(f);
        card.style.display = show ? '' : 'none';
      });
    }));
  </script>
</body>
</html>
