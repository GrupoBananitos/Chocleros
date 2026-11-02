# Space Tourism — proyecto reorganizado

## Estructura

```text
space-tourism/
├── index.html                 # Destinos
├── home.html                  # Portada
├── crew.html                  # Tripulación
├── technology.html            # Tecnología
└── assets/
    ├── css/
    │   ├── main.css           # Importa los módulos CSS
    │   ├── base.css           # Variables, estilos globales y encabezado
    │   ├── pages.css          # Estilos específicos de cada página
    │   └── responsive.css     # Adaptación para tablet y móvil
    ├── js/
    │   └── main.js            # Menú y componentes interactivos
    └── images/                # Todas las imágenes locales
```

## Cómo colocar tus propias imágenes

1. Abre `assets/images/`.
2. Copia tus imágenes desde tu ordenador dentro de esa carpeta.
3. Renómbralas exactamente con los nombres de la tabla siguiente, o modifica las rutas en HTML/CSS/JavaScript.
4. Mantén las extensiones indicadas. Si usas otra extensión, actualiza también la ruta correspondiente.

| Archivo | Uso |
|---|---|
| `logo.png` | Logo del encabezado, en todas las páginas |
| `background-space.jpg` | Fondo general de respaldo |
| `background-home.jpg` | Fondo de Home |
| `background-crew.jpg` | Fondo de Crew |
| `background-technology.jpg` | Fondo de Technology |
| `planet-moon.jpg` | Luna |
| `planet-mars.jpg` | Marte |
| `planet-europa.jpg` | Europa |
| `planet-titan.jpg` | Titán |
| `crew-douglas-hurley.png` | Douglas Hurley |
| `crew-mark-shuttleworth.png` | Mark Shuttleworth |
| `crew-victor-glover.png` | Victor Glover |
| `crew-anousheh-ansari.png` | Anousheh Ansari |
| `technology-launch-vehicle.png` | Vehículo de lanzamiento |
| `technology-spaceport.png` | Puerto espacial |
| `technology-space-capsule.png` | Cápsula espacial |

**Importante:** el ZIP no incluye fotografías de reemplazo porque no venían como archivos en el proyecto original. El sitio ya está configurado para usar rutas locales; debes añadir tus imágenes con los nombres indicados.

## Personalizar el logo

El logo se muestra desde `assets/images/logo.png`. Puedes usar PNG transparente o SVG. Si utilizas SVG, cambia en los cuatro HTML la ruta `assets/images/logo.png` por `assets/images/logo.svg`.

## Personalizar fondos

Los fondos están definidos en `assets/css/main.css`, en la sección `PAGE BACKGROUNDS`. Cambia el nombre del archivo en `url('../images/...')` si deseas utilizar otro.

## Ejecutar

No requiere dependencias ni backend. Abre `home.html` para comenzar por la portada o `index.html` para entrar directamente a Destinos. También puedes abrirlo con Live Server en Visual Studio Code.

## Tipografías

Las tipografías se cargan desde Google Fonts. Las imágenes son locales; para que las tipografías también funcionen sin internet, habría que descargar sus archivos y configurarlas con `@font-face`.
