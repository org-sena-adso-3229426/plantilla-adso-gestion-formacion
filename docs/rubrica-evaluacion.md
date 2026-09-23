# Módulo 7 · Evaluación de Entregables
 
## Propósito
 
La valoración se apoya en criterios observables registrados en los Pull Requests (PR) y se comunica de forma formativa. Los instrumentos aquí descritos son propuestas y deben alinearse con el diseño curricular y el reglamento institucional vigente.
 
---
 
# 9.1 Lista de Chequeo de Desempeño (Git y Trabajo Colaborativo)
 
| # | Criterio observable | Cumple | No cumple |
|---|---------------------|---------|------------|
| 1 | Trabaja en rama `feature/*` con nombre convencional; no hace push directo a `main` o `develop`. | ☐ | ☐ |
| 2 | Los commits son pequeños y contienen mensajes descriptivos. | ☐ | ☐ |
| 3 | El PR diligencia la plantilla (historia, criterios, pruebas y evidencias). | ☐ | ☐ |
| 4 | Atiende los comentarios de revisión y los marca como resueltos. | ☐ | ☐ |
| 5 | Revisa al menos un PR de un compañero con observaciones respetuosas y útiles. | ☐ | ☐ |
| 6 | Resuelve conflictos de fusión sin perder cambios de otros integrantes. | ☐ | ☐ |
 
---
 
# 9.2 Rúbrica de Calidad del Entregable (Por Pull Request)
 
| Criterio (Peso) | 4 · Excelente | 3 · Satisfactorio | 2 · En proceso | 1 · Insuficiente |
|-----------------|--------------|-------------------|---------------|------------------|
| **Funcionalidad (40%)** | Cumple todos los criterios de aceptación y maneja casos límite. | Cumple todos los criterios. | Cumple parcialmente; presenta errores menores. | No ejecuta o incumple la mayoría de los criterios. |
| **Calidad del código (25%)** | Modular, legible, sin duplicación y con pruebas. | Legible y organizado. | Funciona, pero presenta desorden o estructura mejorable. | Difícil de leer y mantener; contiene código innecesario. |
| **Documentación del PR (20%)** | Completa y con evidencias claras. | Completa. | Faltan algunas secciones. | Vacía o sin evidencias. |
| **Uso de Git (15%)** | Historial limpio; PR enfocado en una única historia. | Correcto. | Commits poco claros. | Cambios no relacionados o historial confuso. |
 
### 🎓 De la rúbrica al juicio evaluativo
 
Antes de realizar la evaluación se debe definir un umbral de aprobación.
 
**Ejemplo:**
 
- Promedio ponderado ≥ 3.0
- Ningún criterio de Funcionalidad en nivel 1
 
Con estas condiciones se puede registrar el resultado como **"Aprobado"** para el RAP correspondiente.
 
> El umbral debe comunicarse previamente a los aprendices en la guía de aprendizaje.
>
> El resultado final registrado en Sofía Plus es responsabilidad del instructor.
 
---
 
# 9.3 Lista de Chequeo del Producto (Incremento del Sprint)
 
- ☐ La aplicación se ejecuta desde la rama `main` siguiendo las instrucciones del `README`.
- ☐ Cada historia del sprint cumple sus criterios de aceptación.
- ☐ No existen credenciales ni archivos `.env` en el repositorio.
- ☐ Las pruebas automatizadas (si existen) se ejecutan satisfactoriamente.
- ☐ La Definition of Done fue validada por el líder del equipo.
- ☐ La demostración (Sprint Demo) fue presentada al instructor.
 
---
 
# 9.4 Autoevaluación, Coevaluación y Heteroevaluación
 
| Modalidad | Quién evalúa | Instrumento | Frecuencia |
|------------|-------------|-------------|------------|
| Autoevaluación | Aprendiz | Formato corto: ¿qué aprendí?, ¿qué me costó?, ¿qué mejoraría? | Cada sprint |
| Coevaluación | Compañeros y líder | Lista de chequeo 9.1 sobre el aporte de cada integrante | Cada sprint |
| Heteroevaluación | Líder → equipo · Instructor → líderes y producto | Rúbrica 9.2 + Lista 9.3 | Cada PR / Fin de sprint |
 
---
 
# 9.5 Estados de un Pull Request
 
| Estado | Significado | Acción |
|----------|------------|---------|
| **Approve** | Cumple los criterios clave establecidos. | Realizar Merge. |
| **Request changes** | Falta funcionalidad, documentación o limpieza del código. | Corregir en la misma rama y solicitar nueva revisión. |
| **Close** | Entrega no viable o fuera del alcance definido. | Rehacer el trabajo en una nueva rama. |
 
---
 
# Recomendaciones para los Equipos
 
1. Mantener ramas pequeñas y enfocadas en una sola historia de usuario.
2. Realizar revisiones de código frecuentes.
3. Documentar las evidencias en cada Pull Request.
4. Aplicar buenas prácticas de Git y control de versiones.
5. Garantizar el cumplimiento de la Definition of Done antes de solicitar revisión.
 
---
 
## Referencias
 
- Guía de aprendizaje del programa de formación.
- Reglamento de evaluación institucional.
- Convenciones de Git y GitHub definidas por el proyecto.