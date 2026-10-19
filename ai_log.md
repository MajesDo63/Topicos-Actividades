## Entrada Actividad 1 (A1) - Variante v2-revisor

- **Herramienta utilizada:** Asistente IA (Gemini).
- **Caso de uso:** 
  - Generación de la estructura del archivo `evals/a1_v2-revisor.jsonl` con 10 preguntas equilibradas entre casos normales, exactos y sinónimos.
  - Asignación de dimensiones temáticas y vectores de prueba para el ejercicio manual en `notebooks/a1_manual.ipynb`.
  - Redacción base de las conclusiones del reporte.
- **Validación de parte mia y correcciones:** 
  - Se verificaron manualmente los IDs esperados (`sec-01`, `sec-02`, etc.) contra los documentos reales del corpus de `v2-revisor`.
  - Se corrigieron sintaxis de comillas y formato JSONL para evitar errores de parseo en la prueba de comparación.
  - Se validó que el cálculo numérico del coseno en el notebook fuera coherente con la teoría de vectores normalizados.