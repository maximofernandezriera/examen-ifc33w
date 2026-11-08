# examen-ifc33w

Material privado del examen de Programación (0485, DAW) del grupo IFC33W.

<a href="https://colab.research.google.com/github/maximofernandezriera/examen-ifc33w/blob/main/solucion-examen-d-v4.ipynb" target="_parent"><img src="https://colab.research.google.com/assets/colab-badge.svg" alt="Open In Colab"/></a>

## Contenido

- `solucion-examen-d-v4.ipynb`: solución del modelo D-V4 (biblioteca de Lucía), explicada paso a paso para proyectarla en clase antes de devolver los exámenes. Para cada ejercicio, de A1 a C3, incluye:
  - el enunciado y su puntuación;
  - un dibujo de pizarra con la idea clave;
  - el código ejecutado y la explicación;
  - un enlace a PythonTutor;
  - la rúbrica por criterios y los errores frecuentes.

  Al final hay una tabla resumen de respuestas y dudas frecuentes. El cuaderno se entrega ya ejecutado, con las salidas guardadas.
- `generar_notebook.py`: script que genera el cuaderno. Comprueba que las salidas de A y B coinciden con la clave y que las soluciones de C pasan sus doctests.

## Regenerar

```bash
pip install nbformat nbclient ipykernel matplotlib
python3 generar_notebook.py
```

El repositorio es privado porque contiene las soluciones del examen. Colab pedirá autorizar el acceso a GitHub para abrirlo.
