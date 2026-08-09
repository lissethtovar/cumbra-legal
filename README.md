# cumbra-legal

Páginas legales y de soporte de las aplicaciones **Cumbra** (Andamia).

Sitio estático, sin dependencias. Se publica con GitHub Pages.

```
index.html                 Índice: soporte + enlaces a cada política
estilos.css                Tokens del sistema visual Señal
anestesia/privacidad.html  Política de Cumbra Anestesia
trauma/privacidad.html     Política de Cumbra TraumaOrtopedia
.nojekyll                  Evita que GitHub Pages procese el sitio con Jekyll
```

## Publicar

1. Subir este contenido a un repositorio **público**.
2. Settings → Pages → Source: `Deploy from a branch`, rama `main`, carpeta `/ (root)`.
3. Opcional, dominio propio: Settings → Pages → Custom domain → `legal.andamia.io`,
   y en el registrador un registro `CNAME` de `legal` hacia `<usuario>.github.io`.
   El correo de iCloud vive en los registros MX y no se ve afectado.

## URLs que pide App Store Connect

| Campo | URL |
|---|---|
| Privacy Policy URL (Anestesia) | `.../anestesia/privacidad.html` |
| Privacy Policy URL (Trauma) | `.../trauma/privacidad.html` |
| Support URL | `.../` (el índice) |

## Al cambiar qué datos recoge una app

Actualizar la tabla de datos y **la fecha del encabezado** de la política afectada.
El historial de git deja constancia de qué decía en cada momento.
