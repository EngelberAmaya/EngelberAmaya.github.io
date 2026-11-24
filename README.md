# Sitio web personal de Engelber Amaya

Sitio web profesional y portafolio personal de Engelber Alberto Amaya Noguera, Ingeniero en Informática y Desarrollador Web Full Stack. La página presenta su perfil, habilidades, formación, trayectoria laboral, proyectos, aplicaciones demostrativas, cursos realizados y datos de contacto.

Sitio publicado: <https://engelberamaya.netlify.app/>

## Descripción general

El proyecto es una página única —single page— construida como sitio estático con Astro. La navegación lateral lleva a las distintas secciones mediante enlaces internos y el desplazamiento suave entre contenidos. El diseño es adaptable a escritorio, tabletas y dispositivos móviles.

La página muestra principalmente información en español y se organiza en las siguientes secciones:

1. **Inicio/Hero**: presenta el nombre de Engelber Amaya y una profesión escrita con efecto de máquina de escribir.
2. **Sobre mí**: describe su perfil profesional, ubicación, teléfono, correo, perfiles de GitHub y LinkedIn, formación y experiencia.
3. **Skills**: muestra en barras de progreso las habilidades técnicas y el nivel estimado de dominio de HTML, CSS, JavaScript, Bootstrap, Git, SQL, SQL Server, Angular, Angular Material, Node.js, Ionic, MongoDB, React y TypeScript.
4. **Currículum**: incluye educación, formación técnica e universitaria y la experiencia profesional en T&M Consulting Services, World Cloud Services, Hispanos Soluciones y Excuela.
5. **Portafolio**: resume seis proyectos principales con descripción e enlaces a su código fuente en GitHub.
6. **Aplicaciones**: reúne aplicaciones demostrativas agrupadas por tecnología. Permite filtrarlas con Isotope entre todas, JavaScript y Angular, ampliar las capturas con GLightbox y abrir una página independiente con los detalles de cada aplicación.
7. **Cursos realizados**: recopila cursos y certificados de Angular, Angular Material, SQL Server, Node.js y React obtenidos en Udemy y Platzi.
8. **Contacto**: muestra dirección, correo, teléfono, perfil de GitHub y un mapa integrado de Google Maps.

## Funcionalidad de la interfaz

- Barra lateral fija con foto de perfil y enlaces a LinkedIn, GitHub, Facebook, Instagram y Linktree.
- Menú lateral responsive que se abre y se oculta desde el botón de navegación móvil.
- Resaltado automático del enlace activo según la sección visible durante el desplazamiento.
- Navegación con desplazamiento suave y manejo de enlaces con URL hash.
- Botón flotante para volver al inicio de la página.
- Animación de texto en la sección principal mediante Typed.js.
- Animaciones de entrada al hacer scroll mediante AOS.
- Barras de habilidades que se completan al ingresar al área de skills.
- Filtros interactivos de proyectos con Isotope.
- Visor de imágenes con GLightbox.
- Carruseles con Swiper en las páginas de detalle.
- Indicadores numéricos mediante Pure Counter.
- Indicadores de carga por sección que desaparecen al cargar o al alcanzar cada bloque durante el scroll.
- Diseño adaptable con cambios específicos para las barras laterales, tipografías e imágenes en dispositivos pequeños.

## Portafolio profesional

La sección de portafolio presenta:

- **Sistema Hospital**: usuarios, médicos y hospitales con CRUD, autenticación mediante token, búsqueda, exportación de datos, integración API, imágenes dinámicas y menú según el rol almacenado en LocalStorage.
- **Fotos Gram App**: aplicación Ionic para publicaciones con imágenes, fotografías tomadas desde el dispositivo, ubicación geográfica con MapBox, publicaciones, registro y modificación de usuarios, token y Guards.
- **Marketplace Angular**: categorías, subcategorías, productos, compras, productos vendidos o recomendados, productos relacionados y reseñas con puntuación.
- **Escuela Angular Material**: administración y relación de alumnos, profesores y casas de estudio, con filtros, ordenación y paginación.
- **Socket Colas Banco**: simulación del orden de atención de clientes y asignación de clientes a escritorios o cajas.
- **Rest Server Node**: API REST con consultas paginadas, creación, modificación y eliminación lógica de usuarios, validaciones, autenticación con Gmail/Google Sign-In y tokens.

Todos los proyectos enlazan directamente a los repositorios correspondientes en GitHub.

## Aplicaciones demostrativas

La sección `Aplicaciones` contiene un filtro por tecnología y permite visualizar los siguientes proyectos activos:

| Aplicación | Tecnología | Funcionalidad principal |
| --- | --- | --- |
| BlackJack | JavaScript | Juego de un jugador contra la computadora. |
| Tareas | JavaScript | Creación, listado y eliminación de tareas con filtros y persistencia en `localStorage`. |
| Películas App | Angular | Catálogo y búsqueda de películas, información detallada, reparto de actores y favoritos. |
| Gifs App | Angular | Exploración de GIFs mediante Giphy, tendencias con scroll infinito, búsquedas reactivas e historial persistente. |
| Country App | Angular | Consulta de países mediante la API REST Countries con búsqueda por nombre, capital y región, detalle de país y caché. |
| Maps App | Angular | Mapas interactivos, administración de marcadores y visualización de propiedades con Mapbox GL JS. |

Cada aplicación cuenta con una página HTML de detalle bajo `public/components/`. Estas páginas muestran capturas en un carrusel, tecnología utilizada, código fuente, URL pública y descripción del proyecto.

El proyecto conserva además páginas de detalle preparadas para aplicaciones React —GIF, héroes y tareas—, aunque React se encuentra actualmente deshabilitado en el filtro y en el listado principal de la página.

## Tecnologías utilizadas

### Framework y entorno

- **Astro 5.7**: generación del sitio estático, composición por componentes y construcción para producción.
- **TypeScript/JavaScript**: configuración estricta de TypeScript con Astro y JavaScript para las interacciones del navegador.
- **Node.js y npm**: ejecución de scripts, dependencias y herramientas de desarrollo.

### Estructura de interfaz

- **Astro Components**: componentes `.astro` reutilizables para la cabecera, el hero y cada sección.
- **HTML5**: marcado semántico de la página y de las páginas independientes de detalle.
- **CSS3**: personalización del estilo visual y diseño responsive.
- **Bootstrap 5**: estructura responsive, utilidades, botones y componentes base.
- **Bootstrap Icons** y **Boxicons**: iconos para navegación, redes, datos de contacto y proyectos.
- **Google Fonts**: tipografías Open Sans, Raleway y Poppins.

### Librerías JavaScript del navegador

- **AOS**: animaciones al entrar en el viewport.
- **Typed.js**: efecto de escritura animado en el hero.
- **Waypoints**: activación de acciones al llegar a determinados elementos.
- **Pure Counter**: contabilización animada.
- **Isotope**: filtrado y disposición dinámica de la cuadrícula de aplicaciones.
- **GLightbox**: ampliación de imágenes.
- **Swiper**: carruseles de capturas.
- **Bootstrap Bundle**: componentes interactivos de Bootstrap.

### Contenido multimedia y servicios externos

- **Cloudinary**: alojamiento de varias capturas y imágenes de aplicaciones.
- **Google Maps**: mapa embebido en la sección de contacto.
- **GitHub**: repositorios de proyectos y perfil profesional.
- **LinkedIn, Facebook, Instagram y Linktree**: enlaces sociales.
- **Udemy y Platzi**: enlaces a certificados de cursos.

## Arquitectura y estructura del proyecto

```text
.
├── public/
│   ├── assets/
│   │   ├── css/style.css       # Estilos principales y responsive
│   │   ├── js/main.js          # Navegación, filtros, animaciones y carruseles
│   │   ├── img/                # Foto, favicons e imágenes de las aplicaciones
│   │   └── vendor/             # Librerías CSS y JavaScript incluidas localmente
│   ├── components/
│   │   ├── angular/            # Páginas HTML de detalle de Angular
│   │   ├── javascript/         # Páginas HTML de detalle de JavaScript
│   │   └── react/              # Páginas HTML históricas de React
│   ├── favicon.svg
│   └── robots.txt
├── src/
│   ├── components/             # Secciones visibles del sitio
│   ├── layouts/Layout.astro    # Documento base y carga de estilos/scripts
│   └── pages/index.astro       # Página principal y composición de secciones
├── .vscode/
│   ├── extensions.json
│   └── launch.json
├── astro.config.mjs            # Dominio del sitio y ruta base
├── package.json
├── package-lock.json
├── tsconfig.json
└── dist/                       # Resultado generado por el build
```

### Componentes principales

- `Layout.astro`: define el HTML base, metadatos, favicons, fuentes, estilos y scripts compartidos.
- `Header.astro`: foto, nombre, redes sociales y navegación lateral.
- `Hero.astro`: nombre y profesión con efecto de escritura.
- `About.astro`: presentación profesional y datos personales.
- `Skills.astro`: barras de habilidades técnicas.
- `Resume.astro`: educación y experiencia laboral.
- `Portfolio.astro`: proyectos destacados y repositorios.
- `Applications.astro`: galería filtrable de aplicaciones con capturas y detalles.
- `Courses.astro`: formación externa y certificados.
- `Contact.astro`: datos de contacto y mapa.
- `public/assets/js/main.js`: comportamiento interactivo del sitio.

Los archivos colocados en `public/` se sirven directamente y no pasan por el proceso de componentes de Astro. La salida compilada se escribe en `dist/`, mientras que dependencias, caché y archivos locales están excluidos mediante `.gitignore`.

## Configuración

La configuración principal de Astro se encuentra en `astro.config.mjs`:

- Dominio configurado: `https://engelberamaya.netlify.app/`.
- Ruta base: `/`.
- Salida estática predeterminada de Astro.

`tsconfig.json` extiende la configuración estricta de Astro y excluye el directorio `dist` de la comprobación.

## Requisitos

- Node.js compatible con Astro 5.
- npm.

## Instalación y ejecución

Desde la raíz del proyecto:

```powershell
npm install
npm run dev
```

El servidor de desarrollo se inicia normalmente en `http://localhost:4321/`.

### Comandos disponibles

| Comando | Acción |
| --- | --- |
| `npm install` | Instala las dependencias. |
| `npm run dev` | Inicia el servidor de desarrollo de Astro. |
| `npm run build` | Genera el sitio de producción en `dist/`. |
| `npm run preview` | Sirve localmente la versión generada para revisarla. |
| `npm run astro ...` | Ejecuta comandos adicionales de Astro. |

También existe una configuración de VS Code en `.vscode/launch.json` para iniciar el servidor de desarrollo desde la terminal integrada.

## Despliegue

Al ejecutar `npm run build`, Astro genera archivos estáticos en `dist/`. Esa carpeta puede publicarse en cualquier hosting compatible con sitios estáticos.

Algunas páginas de detalle hacen referencias internas a `../../index.html`. Para conservar este comportamiento después del despliegue, el servidor debe continuar sirviendo el archivo generado de la página principal como `/index.html`.
