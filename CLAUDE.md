# Instrucciones para Claude Code

## Flujo de trabajo con git

- **Siempre parte de la última versión de `origin/main`** antes de hacer cambios: haz `git fetch origin main` y crea la rama de trabajo (o fusiona) desde ahí. Nunca trabajes sobre una base desactualizada.
- `main` es la rama de referencia del proyecto; otras ramas pueden estar obsoletas.

## Proyecto

- Es un juego web en un único fichero `index.html` (Silicon Reign, estilo Reigns sobre una startup de IA).
- Todo el contenido es bilingüe: los textos de UI y cartas son arrays `[español, inglés]`. Cualquier texto nuevo debe añadirse en ambos idiomas.
- Las cartas con `id` solo aparecen como consecuencia encadenada (`next`), nunca en el mazo inicial.
