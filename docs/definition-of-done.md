# Definition of Done (DoD) · Ficha 3229426
 
Una historia de usuario SOLO se considera terminada ("Hecho") cuando cumple
TODOS los puntos siguientes. El líder verifica estos puntos antes de aprobar
el PR hacia `develop`; el instructor los vuelve a verificar antes de aprobar
el PR hacia `main`.
 
## 1. Código
- [ ] El código está en una rama `feature/HU-XX-descripcion` creada desde `develop`.
- [ ] No hay código comentado, `console.log`/`print` de depuración, ni archivos
      temporales (.env, node_modules, __pycache__, etc.).
- [ ] Los nombres de variables, funciones y archivos son descriptivos.
 
## 2. Pull Request
- [ ] El PR usa la plantilla completa (.github/PULL_REQUEST_TEMPLATE.md).
- [ ] El PR está vinculado al Issue de la historia con "closes #N".
- [ ] El PR fue aprobado por el revisor correspondiente (líder o instructor,
      según el campo "Revisión" del tablero Kanban).
- [ ] Todos los comentarios de revisión quedaron marcados como resueltos.
 
## 3. Criterios de aceptación
- [ ] Cada criterio de aceptación de la historia fue probado manualmente
      y quedó marcado [x] en el PR.
- [ ] Si existen pruebas automáticas (GitHub Actions), todas pasan en verde.
 
## 4. Evidencia
- [ ] El PR incluye al menos una captura de pantalla o registro de la
      ejecución que demuestra el cumplimiento del criterio.
 
## 5. Tablero
- [ ] Al fusionar el PR, la tarjeta del Issue queda en la columna "Hecho"
      del tablero Kanban del proyecto.
 
> Si falta cualquier punto de esta lista, el revisor debe usar
> "Request changes" en el Pull Request y explicar qué falta,
> siguiendo el formato de retroalimentación de la guía de aprendizaje
> (sección 8.11 del taller).
