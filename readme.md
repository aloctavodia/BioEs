# Bioinformática Estructural usando Python

Este repositorio contiene material didáctico para el dictado de un curso introductorio de Bioinformática Estructural. Este material es **trabajo en progreso** por lo que todavía quedan varias aristas por pulir. El material consiste en Jupyter notebooks y tiene un enfoque práctico. Confío en que este formato ayudará a los estudiantes a entusiasmarse con los distintos tópicos y aún mas importante que los motivará para seguir estudiando por su cuenta.


## Temas
### Introducción a la programación científica
Investigación reproducible. Lenguaje de programación Python. Scripts y notebooks de Jupyter.
Variables. Operadores. Cadenas listas, tuplas, diccionarios, conjuntos. Bucles y control de flujo.
Modulos y librerías. Excepciones. Escritura/lectura de archivos. Concepto de algoritmo y
ejemplos. Automatización de tareas cotidianas. Pequeños programas-proyectos. El material de este tema se encuentra en [este](https://github.com/aloctavodia/Intro_Python) repositorio.

### Introducción a la Bioinformática Estructural
Bioinformática y biología computacional, definiciones, presente y futuro. Bioinformática
estructural, definición. El PDB, base de datos y formato. Visualización y análisis de estructuras
usando PyMOL/Python: Distancias y mapas de contacto, medición de ángulos, ángulos torsionales y Ramachandran plot, radio de giro, superposición estructural, área expuesta al solvente y algoritmo de Shrake & Rupley.

### Alineamiento de secuencias y clustering
Definición de homología, el problema del alineamiento, alineamientos globales vs locales, matrices de sustitución, matriz BLOSUM. Algoritmo de Needleman-Wunsch algorithm y de Smith-Waterman algorithm. BLAST. Estrategias para alineamientos múltiples. Alineamiento Progresivo (_greedy approach_) y alineamiento iterativo. Conceptos en filogenia molecualr computacional, métodos basados en distancia, métodos basados en caracteres, máxima parsimonia, Máxima verosimilitud, métodos Bayesianos. Clustering: Neighbor joining, K-means clustering


### Modelado por homología (usando Modeller)
TODO

### Modelado de novo (usando PyRosetta)
TODO

## Instalación
Para usar este material es necesario tener instalado Python (lamentablemente PyRosetta todavía no está portado a Python 3 por lo que se usará Python 2.7). Además es necesario instalar los siguientes paquetes:

Las notebooks fueron creadas en una computadora x86_64 corriendo Ubuntu 15.10 y usando las siguientes librerías de Python:

* Jupyter 4.0.1
* NumPy 1.10.4
* SciPy 0.16.1
* Matplotlib 1.5.1
* Seaborn 0.7.0
* PyMOL 
```conda install -c https://conda.anaconda.org/ostrokach pymol)```
* Modeller 
```conda config --add channels salilab
conda install modeller)```

Para los usuarios de Windows/Mac Os X se recomienda instalar Python y todas las librerías requeridas vía [Anaconda](https://www.continuum.io/downloads). Para los usuarios de Linux se recomienda Anaconda o pip, ya que los gestores de paquetes suelen tener versiones algo viejas de estas librerías.


## Contribuciones
Todo el contenido de este repositorio es abierto, esto quiere decir que cualquier persona interesada puede contribuir a el. Todas las contribuciones serán bien recibidas incluyendo:

* Correcciones ortográficas
* Nuevas figuras
* Correcciones en el código Python, incluidas mejoras de estilo
* Mejores ejemplos
* Mejores explicaciones 
* Correcciones de errores conceptuales

La forma de contribuir es vía la interfaz de Github, es decir los cambios deberán ser hechos en forma de _pull requests_ y los problemas/bugs deberán reportarse como _Issues_.
