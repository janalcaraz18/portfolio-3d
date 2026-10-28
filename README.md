# Portfolio 3D — estructura del proyecto

Portfolio web estático organizado por responsabilidades y tipos de contenido.

## Estructura

```text
portfolio-3d/
├── index.html
├── README.md
├── assets/
│   ├── css/style.css
│   ├── js/main.js
│   ├── images/
│   │   ├── profile/
│   │   └── projects/
│   ├── videos/
│   └── fonts/
├── projects/
│   ├── lighting-study/
│   ├── environment/
│   ├── asset-materials/
│   └── animation-short-film/
└── journal/articles/
```

## Dónde va cada cosa

- **HTML:** estructura de la página principal en `index.html`.
- **CSS:** colores, composición y responsive en `assets/css/style.css`.
- **JavaScript:** interacciones en `assets/js/main.js`.
- **Imágenes:** perfil en `assets/images/profile/`; renders y miniaturas en `assets/images/projects/`.
- **Vídeo:** guarda el showreel en `assets/videos/showreel.mp4` y activa el elemento de vídeo comentado en `index.html`.
- **Proyectos:** cada carpeta de `projects/` contiene una plantilla para documentar rol, herramientas, proceso y resultado.
- **Journal:** guarda borradores y artículos de proceso en `journal/articles/`.

Las carpetas incluyen plantillas; aún tienes que añadir tus renders, vídeo y datos reales. Cambia también el email de ejemplo y los enlaces sociales antes de compartir el portfolio.

## Publicar con GitHub Pages

En GitHub, abre **Settings → Pages**, selecciona la rama `main` y la carpeta `/(root)`. Las rutas de recursos son relativas para que el sitio funcione también en `/portfolio-3d/`.
