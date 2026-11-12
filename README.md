# Nicrobio-Webs — Portafolio

Portafolio estático de Nicolás Gómez, publicado con GitHub Pages.

## Contenido

- `index.html`: portada del portafolio.
- `petalos-de-carne-tickets.html`: landing interactiva de preventa de boletas (demostrativa).
- `cassettes_nicrobio.html`: tienda conceptual de cassettes con modelos 3D (Three.js).
- `glam-guapa.html`: página de GGuapa, tienda de maquillaje con sección 3D interactiva (Three.js).
- Los sitios de Grupo Judicial Torres & Asociados y ASOLUXIA se enlazan a sus dominios publicados.

## Publicar con GitHub Pages

1. Sube `index.html` a la raíz del repositorio `Nicrobio-Webs`.
2. Conserva en esa misma raíz todos los proyectos HTML: `petalos-de-carne-tickets.html`, `cassettes_nicrobio.html` y `glam-guapa.html`.
3. En GitHub, abre **Settings → Pages**.
4. En **Build and deployment**, elige **Deploy from a branch**.
5. Selecciona la rama `main` y la carpeta `/(root)`, y pulsa **Save**.
6. Cuando termine el despliegue, la página principal quedará publicada en:
   `https://nicrobio.github.io/Nicrobio-Webs/`

## Enlaces de los proyectos HTML

- `https://nicrobio.github.io/Nicrobio-Webs/petalos-de-carne-tickets.html`
- `https://nicrobio.github.io/Nicrobio-Webs/cassettes_nicrobio.html`
- `https://nicrobio.github.io/Nicrobio-Webs/glam-guapa.html`

## Notas técnicas

- `glam-guapa.html` y `cassettes_nicrobio.html` cargan Three.js desde un CDN (jsDelivr), por lo que necesitan conexión a internet para mostrar las secciones 3D.
- `glam-guapa.html` pesa cerca de 1 MB porque sus imágenes van incrustadas en el propio archivo.

## Antes de publicar

Revisa que los números de teléfono, enlaces de WhatsApp, datos de contacto, imágenes y nombres incluidos en los HTML sean datos que tienes autorización para publicar. El código de un repositorio público puede ser consultado por cualquier persona.

En particular, `glam-guapa.html` incluye el enlace de WhatsApp y los perfiles de redes sociales de GGuapa, y enlaza a productos de `gguapa.com`: confirma que cuentas con el permiso de la marca para mostrarlos.

Los flujos de compra de Pétalos de Carne y Cassettes Nicrobio son demostrativos y no realizan cobros reales.
