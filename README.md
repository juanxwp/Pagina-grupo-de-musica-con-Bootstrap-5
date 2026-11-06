# Mägo de Oz · Web Fan

Página web de fans del grupo de música **Mägo de Oz**, maquetada con **Bootstrap 5** y construida con **Vite**.

## Proyecto

* Proyecto creado con `npm create vite@latest` (plantilla *vanilla*) y Bootstrap instalado con `npm install bootstrap`.
* En `src/main.js` se importan, por este orden, el CSS de Bootstrap, `bootstrap.bundle.min.js` y `style.css`.
* Se ha borrado el código de ejemplo de la plantilla (`counter.js`, contador, logotipo de Vite).
* `npm run build` genera la carpeta `dist` sin errores.

### Tecnologías

* [Vite](https://vite.dev/) como herramienta de desarrollo y empaquetado.
* [Bootstrap 5.3](https://getbootstrap.com/) para el diseño responsive y los componentes.
* [Bootstrap Icons](https://icons.getbootstrap.com/) para los iconos.
* HTML5, CSS3 y JavaScript (módulos ES).

### Componentes de Bootstrap utilizados

Barra de navegación fija (*navbar*) con menú colapsable, carrusel, tarjetas (*cards*), vídeo incrustado con *ratio*, tabla responsive con *badges*, paginación, colapsables, acordeón de preguntas frecuentes y modal de contacto con formulario validado. Incluye además un botón para alternar entre modo oscuro y modo claro.

## Estructura


Pagina-grupo-de-musica-con-Bootstrap-5/
├── public/
│   └── img/              # Imágenes estáticas (carrusel, miembros, logotipos)
├── src/
│   ├── main.js           # Punto de entrada: importa Bootstrap (CSS y JS) y style.css
│   └── style.css         # Estilos propios (tarjetas, modo oscuro, botones de compra)
├── .gitignore            # Excluye node_modules, dist, etc.
├── index.html            # Página única con todas las secciones
├── package.json          # Dependencias y scripts de npm
└── package-lock.json


### Secciones de `index.html`

| Sección | Contenido |

| Inicio | Carrusel con fotos destacadas del grupo |
| El grupo | Presentación, vídeo oficial y miembros en tarjetas |
| Discografía | Álbumes con listado de canciones desplegable |
| Gira | Tabla de próximas fechas con botón de compra de entradas y paginación |
| Preguntas frecuentes | Acordeón con dudas sobre la gira |
| Contacto | Modal con formulario de contacto y contratación |

## Instalación y uso

Requiere [Node.js](https://nodejs.org/) instalado.


# Instalar dependencias
npm install bootstrap

# Servidor de desarrollo
npm run dev

# Generar la versión de producción (carpeta dist)
npm run build

# Previsualizar la versión generada
npm run preview
