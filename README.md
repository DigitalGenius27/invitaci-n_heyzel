# Early & Darling — frontend a partir del HTML proporcionado

Este paquete usa el HTML/CSS/JavaScript completo que compartiste, conservando las secciones, textos, estilos e interacciones del código.

## Cómo probarlo
1. Descomprime el ZIP.
2. Abre `index.html` en un navegador moderno.

## Recursos externos
El HTML original hace referencia a dos recursos que no venían incluidos en el texto pegado: `garden.jpg` (fondo floral) y `tu-poeta-piano.mp3` (música). Para que la copia local intente cargarlos, las referencias se cambiaron a sus URLs del sitio original (`mareasite.com/ED/assets/...`). No pude verificar que esas URLs de recursos sean accesibles desde fuera; si no cargan, habrá que obtener esos dos archivos desde el sitio original y guardarlos localmente en `assets/`, cambiando las referencias a `assets/garden.jpg` y `assets/tu-poeta-piano.mp3`.

La invitación está personalizada por query string, por ejemplo `?para=mirian-reynosa`. Para abrirla con el nombre de Mirian desde un servidor local, usa `index.html?para=mirian-reynosa`.
