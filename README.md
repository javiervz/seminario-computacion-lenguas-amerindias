## Seminario de métodos computacionales para lenguas amerindias

Este repositorio incluye todos (o casi todos) los materiales del curso **Seminario de métodos computacionales para lenguas amerindias** ([R.Zariquiey](https://github.com/rzariquiey) y [J. Vera](https://github.com/javiervz)). El programa (más o menos tentativo) incluye los siguientes contenidos:

**Calendario (tentativo)**

| # clase | tema | contenidos | tareas |
| :-: | :-: | :-: | :-: |
| 1 | introducción a la lingüística computacional | análisis computacional de lenguas amerindias desde Perú + nociones básicas de **Python** (variables, listas, ciclos for) | tarea 1: lectura de papers + ciclos for | 
| 2 | nociones básicas de **Python** | ciclos for, if/else | revisión tarea 1 | 
| 3 | nociones básicas de **Python** (continuación) | variables, listas, ciclo for, if/else | tarea 2 (mapas) |
| 4 | uso básico de pandas | ciclo for + lectura de bases de datos tipológicos (Glottolog, Sails, Wals) | revisión tarea 2 |
| 5 | estadísticas básicas de lenguas de Perú | diccionarios + lectura de bases de datos tipológicos + estadística básica| tarea 3 (preguntas en bases de datos) |
| 6 | diccionarios y Unimorph | diccionarios + representación de información morfológica | revisión tarea 3 + tarea 4 (morfología) |
| 7 | distancias entre lenguas | distancia de Hamming + datos tipológicos + representación | revisión tarea 4 + tarea 5 (distancias) |
| 8 | archivos de texto | lectura corpus de texto + cálculos básicos | revisión tarea 5 + tarea 6|
| 9 | archivos de texto (continuación) | nociones de complejidad y lenguas Amerindias | tarea 7 (problemas sobre datos) |
| 10-16 | Seminario de problemas | Recapitulación + problemas sobre datos lingüísticos |  |


## ¿Dónde programar en **Python**?

### Posibilidad 1: **Anaconda** (recomiendo instalar esto sí o sí en cada laptop)

Para esto sigamos los siguientes pasos (este [link](https://medium.com/saturdays-ai/empezando-a-usar-jupyter-notebook-para-python-parte-1-instalaci%C3%B3n-94e97b4c5f37) puede servir):

1. Ir a [link para instalar Anaconda](https://docs.anaconda.com/anaconda/install/) y elegir el sistema operativo.
2. Si es **Windows** o **Mac** es similar: deben bajar el instalador. Si es **linux** hay que bajar e instalar por terminal.
3. Supongamos que tenemos **Windows**. Elijan los bits de su pc, en **configuración** aparece esa información. Luego bajamos el instalador (un .exe) y lo instalamos.
4. Pongan **Next** y **I agree** a todo. Esperen un momento. Pueden hacerse un café o un té mientras esperan. Al final aprieten **Next**. Les recomiendo reiniciar el PC.
5. Ahora tenemos un programa que se llama **Anaconda**. En el menú, hacen click y en las opciones debería estar **jupyter notebook** o **jupyter lab**. Elijan el que más les guste. 
6. En una nueva ventana de su navegador, deberían aparecer las carpetas de su pc. Cree una nueva en su lugar favorito. Aprieten **new -> folder**. Dentro de la carpeta, creen un **new --> Python 3**. Y listo!!!

### Posibilidad 2: **Colab** (recomiendo al menos conocer el uso básico)

En [Colab](https://colab.research.google.com/) pueden abrir **Jupyter Notebooks**. Esto tiene ciertas ventajas y desventajas:

**Ventajas**

1. No hay que instalar nada. 
2. La sintaxis es igual a los Jupyter notebooks
3. Los mapas no tienen problemas de instalación (de librerías y cosas así). 

**Desventajas**

1. Existen pequeñas dificultades en la lectura de datos.
2. Cálculos muy grandes pueden malograrse.

### Posibilidad 3: Amazon Sagemaker (recomendado, aunque hay que pagar un poco. Hay versiones gratuitas que pueden explorar)

En [Link Sagemaker](https://aws.amazon.com/es/pm/sagemaker/), pueden crearse un perfil de **Amazon** para programar en Jupyter en algún computador perdido en el espacio. Tiene el pequeño inconveniente de pagar con tarjeta de crédito. Un uso razonable cuesta alrededor de 10-20 dólares mensuales. 

