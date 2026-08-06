# Publicación — 1teci-diseno-produccion

**URL en vivo:** https://joselugareducaand.github.io/1teci-diseno-produccion/
**Repositorio:** https://github.com/joselugarEducaAnd/1teci-diseno-produccion
**Directorio operativo:** este mismo directorio.
**Publicado:** 2026-08-06 · campaña `DOCA-015`.

## Cómo republicar

1. Abrir `materiales_alumnado/exelearning/1teci-diseno-produccion.elpx` en
   eXeLearning 4 y exportar como sitio web sobre
   `materiales_alumnado/exelearning/diseno-produccion-y-ciclo-de-vida_web/`.
2. Sincronizar el export con este directorio, excluyendo siempre `.git`, `.github`,
   `.nojekyll`, `README.md` y `POINTER.md`.
3. No publicar `content.xml`: es contenido interno del export y no lo necesita el sitio.
4. Comprobar los enlaces del mapa de la portada y que el widget de tolerancias carga.
5. Ejecutar `git add -A`, commit y push desde este directorio; el workflow despliega
   GitHub Pages automáticamente.

El `.elpx` es la fuente de verdad: las correcciones posteriores se parchean sobre él,
no se regenera el bundle desde cero.
