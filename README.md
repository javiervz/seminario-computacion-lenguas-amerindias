## Seminario de métodos computacionales para lenguas amerindias

Este repositorio incluye todos (o casi todos) los materiales del curso **Seminario de métodos computacionales para lenguas amerindias** ([R.Zariquiey](https://github.com/rzariquiey) y [J. Vera](https://github.com/javiervz)). El programa (más o menos tentativo) incluye los siguientes contenidos:

**Calendario (tentativo)**

| # clase | tema | contenidos lingüísticos | contenidos computacionales | papers | tareas | guías |
| :-: | :-: | :-: | :-: | :-: | :-: | :-: |
| 1 | introducción a la lingüística computacional | análisis computacional de lenguas amerindias desde Perú | elementos básicos de **Python**, variables |  |  |
| 2 | nociones básicas de **Python** | anotación computacional de lenguas ameridindias | variables, listas, ciclos for | papers sobre aproximaciones computacionales a lenguas amerindias |  |              
| 3 | nociones básicas de **Python** (continuación) | anotación computacional de lenguas ameridindias | listas, ciclo for, if/else | papers sobre aproximaciones computacionales a lenguas amerindias |   | guía sobre strings, n-gramas |
| 4 | representación de información morfológica | Unimorph | diccionarios | paper sobre Unimorph | tarea 1 |
| 5 | información morfológica y nociones de complejidad | Complejidad y morfología | distribuciones de n-gramas, entropía | paper sobre entropía |  |
| 6 | representación de información sobre lenguas amerindias | bases de datos tipológicas y lenguas amerindias | diccionarios, uso básico de pandas | paper sobre bases de datos y lenguas amerindias |  |
| 7 | estadísticas sobre lenguas peruanas | panorama sobre lenguas peruanas | diccionarios, estadística básica, gráficos | paper sobre estado de lenguas peruanas | entrega tarea 1, tarea 2 |
| 8 | comparaciones entre lenguas | distancias tipológicas | diccionarios, cálculos de distancias, representación | paper sobre distancias entre lenguas |  |
| 9 | archivos de texto | corpus lingüísticos de lenguas amerindias | bases de datos de texto, lectura de archivos de texto, cálculos básicos | paper sobre archivos de texto en lenguas amerindias|  | guía sobre nociones de complejidad y lenguas amerindias |
| 10-16 | Seminario de problemas | recapitulación sobre **Python** | problemas sobre datos lingüísticos | | entrega tarea 2 | 


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

