# Proyecto-Intermodular

Catálogo web de productos estático (sin base de datos) construido con **HTML + CSS**.

## Estructura principal
- `index.html`: página principal con secciones de Inicio, Categorías, Productos, Ofertas y Contacto.
- `estilo.css`: estilos globales y bloque específico responsive para el catálogo.

## Características implementadas
- Diseño en secciones para simular un catálogo comercial.
- Tarjetas de producto estáticas (sin backend).
- Diseño responsive básico usando `grid`, `auto-fit` y media queries.
- Navegación por anclas (`#inicio`, `#productos`, etc.).

## Publicación en servidor local
Desde la raíz del proyecto (`/workspace/Proyecto-Intermodular`), ejecuta:

```bash
python3 -m http.server 8000
```

Luego abre en tu navegador:

- `http://localhost:8000`

Para detener el servidor, usa `Ctrl + C`.
