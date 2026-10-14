# Ergonomía Digital

[![Abrir en Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/MiguelSerranoReyes/ergonomia-digital/blob/main/rula_semiautomatico.ipynb)
[![Código: MIT](https://img.shields.io/badge/c%C3%B3digo-MIT-blue.svg)](LICENSE)
[![Contenido: CC BY 4.0](https://img.shields.io/badge/contenido-CC%20BY%204.0-lightgrey.svg)](LICENSE-CONTENT)

Material del taller **Ergonomía Digital**: evaluación ergonómica **RULA** semiautomática con visión
computacional, lista para ejecutarse en Google Colab.

## ¿Qué hace la libreta?

La libreta `rula_semiautomatico.ipynb` explica el método RULA paso a paso y lo calcula a partir de
fotografías:

1. Detecta el cuerpo en una vista lateral y una posterior con **MediaPipe Pose**.
2. Mide los ángulos de brazo, antebrazo, muñeca, cuello y torso, e indica qué tan confiable es
   cada medición.
3. Presenta un cuestionario interactivo con los 15 pasos de la hoja RULA. La computadora sugiere
   lo que pudo medir y el usuario decide lo que una foto no muestra (fuerza, tiempo, giros).
4. Aplica las tablas A, B y C y entrega el puntaje RULA final con su interpretación.

Incluye tres casos: una oficinista, una persona trabajando con laptop y una odontóloga.

Está pensada para estudiantes sin experiencia en programación: explica los conceptos básicos de
Python conforme aparecen.

## Cómo usarla

1. Haz clic en el botón **Abrir en Colab**. Solo necesitas una cuenta de Google.
2. Para conservar tus cambios, usa *Archivo → Guardar una copia en Drive*. La versión que abre el
   botón es de solo lectura.
3. Ejecuta las celdas en orden con **Shift + Enter**, o todas a la vez con
   *Entorno de ejecución → Ejecutar todas*.

No requiere instalar nada en tu computadora. Las imágenes de los casos se descargan
automáticamente del repositorio
[MiguelSerranoReyes/datasets](https://github.com/MiguelSerranoReyes/datasets/tree/main/ergonomia).

## Limitaciones

Los ángulos se miden en fotografías 2D, por lo que dependen del punto de vista de la cámara y de
qué partes del cuerpo quedan ocultas. Algunos umbrales que la hoja RULA no define se dejaron
explícitos y editables en la libreta (diccionario `CRITERIOS`). Los resultados son una
herramienta didáctica y de apoyo, no sustituyen la evaluación de un especialista.

## Referencia del método

McAtamney, L. y Corlett, E. N. (1993). RULA: a survey method for the investigation of
work-related upper limb disorders. *Applied Ergonomics*, 24(2), 91–99.
https://doi.org/10.1016/0003-6870(93)90080-S

## Licencia

- **Código:** [MIT](LICENSE). Puedes usarlo, modificarlo y redistribuirlo conservando el aviso de
  autoría.
- **Textos y explicaciones de la libreta:** [CC BY 4.0](LICENSE-CONTENT). Puedes reutilizarlos y
  adaptarlos con cualquier fin, citando la fuente.

## Cómo citar

> Serrano Reyes, M. (2026). *Ergonomía Digital: evaluación RULA semiautomática con visión
> computacional* [Material didáctico]. Facultad de Ingeniería, UNAM.
> https://github.com/MiguelSerranoReyes/ergonomia-digital

## Autor

**Miguel Serrano Reyes**, Departamento de Ingeniería en Sistemas Biomédicos, Facultad de
Ingeniería, UNAM. [miguelserranoreyes.com](https://miguelserranoreyes.com) ·
ORCID [0000-0003-1190-5801](https://orcid.org/0000-0003-1190-5801)
