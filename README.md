# Rulo Pardo

Sitio web personal en desarrollo para Rulo Pardo, actor, director y creador. Este primer borrador presenta su perfil y una selección de trabajos en teatro, cine, televisión, música, danza y radio. El proyecto es actualmente una base estática, sencilla y en evolución.

## Tecnologías

- HTML5
- CSS3, con hojas de estilo organizadas por componentes y variables de diseño
- Recursos locales: imágenes y tipografías

No se utiliza actualmente un framework, JavaScript, gestor de paquetes ni proceso de compilación.

## Estructura

```text
.
├── index.html             # Página principal y portafolio
├── form.html              # Vista inicial del formulario de contacto
├── assets/
│   ├── fonts/             # Tipografías locales
│   ├── images/            # Fotografías, fondos y otros recursos visuales
│   └── favicon.ico
└── styles/
    ├── style.css          # Hoja principal e importaciones
    ├── design-tokens.css  # Variables de diseño
    ├── reset.css          # Estilos base
    ├── fonts.css          # Tipografías locales
    ├── site-nav.css       # Navegación
    ├── works.css          # Trabajos seleccionados
    ├── credits-dialog.css # Diálogos de créditos
    ├── contact.css        # Sección de contacto
    ├── form.css           # Formulario
    ├── footer.css         # Pie de página
    ├── buttons.css        # Botones
    ├── gallery.css        # Estilos de carrusel
    └── palette.css        # Paleta de colores
```

## Contenido actual

- Portada y navegación por secciones.
- Manifiesto y selección de trabajos.
- Diálogos con créditos de distintas disciplinas.
- Sección de trayectoria.
- Información de contacto y enlaces a perfiles externos.
- Página independiente con una primera versión del formulario.
- Diseño adaptable y recursos cargados desde el propio proyecto.

## Ver el sitio localmente

No es necesario instalar dependencias. Se puede abrir `index.html` directamente en un navegador o iniciar un servidor local desde la carpeta del proyecto:

```bash
python -m http.server 8000
```

Después, abre [http://localhost:8000](http://localhost:8000). También puedes usar una extensión de servidor local en Visual Studio Code.

## Estado del proyecto

Este repositorio es embrionario y está en desarrollo. Algunas partes son prototipos y pueden requerir ajustes antes de considerarse terminadas:

- El formulario todavía no está conectado a un servicio de envío.

- Algunos efectos y controles usan funciones recientes de CSS y HTML cuya compatibilidad depende del navegador.

La estructura y las funcionalidades pueden cambiar a medida que avance el proyecto.
