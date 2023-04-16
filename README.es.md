# <font color=''>IA</font><font color='#7ac77a'>rpi</font>

[![en](https://img.shields.io/badge/lang-en-red.svg)](https://github.com/simcomat/IArpi/blob/main/README.md) [![pt-br](https://img.shields.io/badge/lang-pt--br-green.svg)](https://github.com/simcomat/IArpi/blob/main/README.pt-br.md) [![es](https://img.shields.io/badge/lang-es-yellow.svg)](https://github.com/simcomat/IArpi/blob/main/README.es.md)

Con el objetivo de introducir los conceptos de Machine Learning en los cursos de física, presentamos el **IArpi**: un experimento de aplicación de la Inteligencia Artificial en el estudio del Rodamiento de objetos en el Plano Inclinado. En este repositorio están disponibles los scripts de Python en Jupyter Notebook que contienen la aplicación de Machine Learning de Regresión y Clasificación sobre los datos experimentales del rodamiento en el plano inclinado.


Para comprender la inserción de estos métodos en los cursos de pregrado en física, recolectamos datos de los planes de estudios de las disciplinas de física computacional (o relacionadas) de diferentes universidades federales Brasileñas. Hicimos un análisis estadístico preliminar utilizando el procesamiento del lenguaje natural y el aprendizaje automático de clústeres, encontrando que estos temas no se exploran en los cursos de física hasta la fecha. Los datos recopilados también se encuentrán disponibles aquí. 

![](https://github.com/simcomat/IArpi/blob/main/iarpi.png)


## Organización
- En `datasets` están contenidos los ficheros `.csv` de los datos experimentales de rodamiento (esfera, cilindro y aro) sobre el plano inclinado (`rolling.csv`) y el levantamiento de los menús (`curriculum.csv`) de Física Computacional, Cálculo Numérico y asignaturas afines cursos de pregrado de física en universidades federales Brasileñas;
- En `notebooks` están los archivos `.ipynb` que contienen la secuencia de código para aplicar técnicas de Machine Learning en el conjunto de datos.

## Uso Online
[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/simcomat/IArpi/blob/main/notebooks/iarpi.ipynb)


## Instalación

Debe tener `Python 3` instalado en su computador, con el administrador de paquetes `pip`. Las bibliotecas utilizadas pueden ser instaladas así:

- Jupyter Notebook:
`pip install notebook`
- Para el trabajo con tablas:
`pip install pandas`
- Para usar ciertas funciones matemáticas:
`pip install numpy`
- Para realizar los gráficos:
`pip install matplolib`,
`pip install seaborn`
- Para utilizar los algoritmos de Machine Learning:
`pip install -U scikit-learn`.

O todas las bibliotecas se pueden instalar a la vez ejecutando pip sobre el archivo `requirements.txt`:
`pip install -r requirements.txt`


## Citación
H. Ferreira, E. F. Almeida Junior, W. Espinsa-Garcia, E. Novais, J. N. B. Rodrigues, G. M. Dalpian. Introduzindo aprendizado de máquina em cursos de física: o caso do rolamento do plano inclinado, Revista Brasileira de Ensino de Física, vol. 44, 2022. DOI: https://doi.org/10.1590/1806-9126-RBEF-2022-0214   
