# Definition of Done (DoD)
 
## Propósito
 
La **Definition of Done (DoD)** establece los criterios mínimos que deben cumplirse antes de considerar una historia de usuario, tarea o incremento del sprint como terminado.
 
Todos los integrantes del equipo deberán verificar el cumplimiento de estos criterios antes de solicitar la revisión de un Pull Request (PR).
 
---
 
# Criterios de Aceptación de la Definition of Done
 
Para que una entrega sea considerada **Terminada (Done)**, debe cumplir con todos los siguientes puntos:
 
## ✅ 1. Código integrado en `develop`
 
- Los cambios fueron desarrollados en una rama de trabajo (`feature/*`, `bugfix/*`, etc.).
- La integración se realiza mediante Pull Request.
- El código queda correctamente incorporado en la rama `develop`.
- No existen conflictos pendientes de fusión.
 
---
 
## ✅ 2. Pull Request aprobado
 
- El Pull Request fue creado utilizando la plantilla definida por el proyecto.
- El PR incluye descripción clara de los cambios realizados.
- Se atendieron todos los comentarios de revisión.
- El Pull Request recibió la aprobación del revisor o líder responsable.
 
---
 
## ✅ 3. Criterios de aceptación verificados
 
- Todos los criterios de aceptación de la historia de usuario fueron validados.
- La funcionalidad cumple los requisitos definidos.
- No existen errores conocidos que impidan el uso correcto de la funcionalidad.
- Los escenarios principales fueron comprobados.
 
---
 
## ✅ 4. Pruebas ejecutadas
 
- Se realizaron las pruebas definidas para la historia.
- Los resultados fueron satisfactorios.
- No existen errores bloqueantes pendientes.
- En caso de contar con pruebas automatizadas, estas se ejecutan correctamente.
 
### Evidencias sugeridas
 
- Capturas de pantalla.
- Registros de ejecución.
- Resultados de pruebas automatizadas.
- Videos cortos de funcionamiento.
 
---
 
## ✅ 5. Evidencia adjunta
 
El Pull Request debe incluir evidencias que demuestren el funcionamiento de la solución:
 
- Capturas de pantalla.
- GIFs o videos.
- Resultados de pruebas.
- Evidencias de validación por parte del equipo.
 
---
 
# Lista de Verificación
 
Antes de solicitar aprobación del Pull Request, verificar:
 
- [ ] El código está integrado en `develop`.
- [ ] El Pull Request fue revisado y aprobado.
- [ ] Los criterios de aceptación fueron verificados.
- [ ] Las pruebas fueron ejecutadas exitosamente.
- [ ] Las evidencias fueron adjuntadas al Pull Request.
 
---
 
# Responsables
 
## Desarrollador
 
- Implementar la solución.
- Ejecutar las pruebas.
- Adjuntar evidencias.
- Solicitar revisión.
 
## Revisor
 
- Validar la calidad del código.
- Verificar criterios de aceptación.
- Aprobar o solicitar cambios.
 
## Líder del Equipo
 
- Confirmar el cumplimiento de la Definition of Done.
- Autorizar la integración final en `develop`.
 
---
 
# Criterio Final
 
> Una historia de usuario se considera **Done** únicamente cuando todos los criterios de esta Definition of Done han sido cumplidos y verificados por el equipo.