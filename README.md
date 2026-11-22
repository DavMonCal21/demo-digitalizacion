# Correos 1716–2026

Web estática del Proyecto de Digitalización (1.ª evaluación, 2.º DAM) sobre la evolución tecnológica de Correos.
Usa Bootstrap 5.3.9 por CDN y no necesita servidor ni JavaScript propio.

## Estructura

```text
demo-digitalizacion/
├── index.html         Inicio: resumen, pregunta guía y cifras 2024
├── historia.html      1. Identidad e historia
├── empresa.html       Líneas de negocio, 2. Organización, 3. Presencia geográfica y mercado
├── tecnologia.html    4. Evolución tecnológica (7 hitos), antes/después y vídeo
├── curiosidades.html  5. Curiosidades e ideas de mejora digital
├── img/               Fotografías (Wikimedia Commons, licencias CC)
├── css/
│   └── style.css
└── README.md
```

## Cómo abrirla

Abre `index.html` en el navegador (o pulsa F5 en VS Code). Hace falta conexión a Internet para cargar Bootstrap.

## Dónde personalizar

- El menú y el pie se repiten en cada HTML: si los cambias, hazlo en todas las páginas y mantén
  `aria-current="page"` en el enlace de la página actual.
- Los colores están en las variables de `:root` en `css/style.css`.
- Vídeo: en `tecnologia.html` hay un comentario que explica cómo insertar el vídeo de YouTube.
- Gráficos: las barras de `empresa.html` usan la variable `--value` (porcentaje respecto al valor máximo).

Trabajo académico: no es la web oficial de Correos.
