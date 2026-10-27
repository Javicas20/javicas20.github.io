# javicas20.github.io

CV personal de Javier Casero Hernández — desarrollador móvil (Android y Kotlin Multiplatform).

Publicado en https://javicas20.github.io/

## Cómo funciona

Una sola página estática, sin dependencias ni build. `index.html` lleva dentro el CSS,
el JavaScript y la foto (como data URI). Lo único externo es la fuente, que se carga
desde Google Fonts.

- Bilingüe español / inglés. Detecta el idioma del navegador en la primera visita
  y recuerda la elección después.
- El botón **Descargar PDF** despliega todas las secciones e imprime en blanco y negro,
  solo en el idioma activo.
- Respeta `prefers-reduced-motion`: sin animaciones para quien las tenga desactivadas.

## Editarlo

Se edita `index.html` directamente. Al hacer push a `main`, GitHub Pages lo publica solo.

## Dominio propio

Para apuntar un dominio (por ejemplo `javiercasero.es`):

1. Crear un archivo `CNAME` en la raíz con el dominio dentro, en una línea.
2. En el DNS del dominio, un registro `CNAME` de `www` a `javicas20.github.io`,
   y registros `A` del apex a las IP de GitHub Pages.
3. Activar *Enforce HTTPS* en Settings → Pages.
