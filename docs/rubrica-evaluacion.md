# Rúbrica de evaluación · Ficha 3229426
 
## 1. Lista de chequeo de desempeño (Git y trabajo colaborativo)
- [ ] Trabaja en rama feature/* con nombre convencional; no hace push
      directo a main/develop.
- [ ] Los commits son pequeños y con mensaje descriptivo.
- [ ] El PR diligencia la plantilla completa.
- [ ] Atiende los comentarios de revisión y los marca como resueltos.
- [ ] Revisa al menos un PR de un compañero con etiquetas y tono respetuoso.
- [ ] Resuelve conflictos de fusión sin perder cambios de otros.
 
## 2. Rúbrica de calidad del entregable (por Pull Request)
 
| Criterio (peso)              | 4 Excelente | 3 Satisfactorio | 2 En proceso | 1 Insuficiente |
|-------------------------------|-------------|-----------------|--------------|----------------|
| Funcionalidad (40%)          | Cumple todos los criterios y casos límite | Cumple todos los criterios | Cumple parte, con errores menores | No ejecuta o incumple la mayoría |
| Calidad del código (25%)     | Modular, legible, sin duplicación, con pruebas | Legible y organizado | Funciona pero desordenado | Difícil de leer, con código basura |
| Documentación del PR (20%)   | Completa, con evidencias claras | Completa | Faltan secciones | Vacía o sin evidencias |
| Uso de Git (15%)             | Historial limpio, PR acotado | Correcto | Commits poco claros | Cambios no relacionados o historial confuso |
 
Umbral de aprobación sugerido: promedio ponderado >= 3.0 y ningún criterio
de Funcionalidad calificado en 1.
 
## 3. Lista de chequeo del producto (incremento del sprint)
- [ ] La aplicación se ejecuta desde main siguiendo el README.
- [ ] Cada historia del sprint cumple sus criterios de aceptación.
- [ ] No hay credenciales ni archivos .env en el repositorio.
- [ ] Las pruebas (si existen) pasan.
- [ ] La Definition of Done (docs/definition-of-done.md) está satisfecha.
- [ ] La demo del sprint se presentó al instructor.
 
## 4. Autoevaluación, coevaluación y heteroevaluación
 
| Modalidad      | Quién                              | Instrumento                              | Frecuencia   |
|----------------|-------------------------------------|-------------------------------------------|--------------|
| Autoevaluación | Aprendiz                            | ¿Qué aprendí? ¿Qué me costó? ¿Qué mejoraría? | Cada sprint  |
| Coevaluación   | Compañeros y líder                  | Sección 1 de esta rúbrica, sobre el aporte de cada integrante | Cada sprint  |
| Heteroevaluación | Líder → equipo / Instructor → líderes y producto | Secciones 2 y 3 de esta rúbrica          | Cada PR / fin de sprint |
 
## 5. Estados de un Pull Request
 
| Estado           | Significado                                  | Acción                                    |
|------------------|-----------------------------------------------|--------------------------------------------|
| Approve          | Cumple los criterios clave                    | Merge                                       |
| Request changes  | Falta funcionalidad, documentación o limpieza | Corregir en la misma rama y pedir revisión  |
| Close            | Entrega no viable o fuera del alcance         | Rehacer en una rama nueva                   |
