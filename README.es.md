# <font color=''>IA</font><font color='#7ac77a'>rpi</font>

[![en](https://img.shields.io/badge/lang-en-red.svg)](https://github.com/simcomat/IArpi/blob/main/README.md) [![pt-br](https://img.shields.io/badge/lang-pt--br-green.svg)](https://github.com/simcomat/IArpi/blob/main/README.pt-br.md) [![es](https://img.shields.io/badge/lang-es-yellow.svg)](https://github.com/simcomat/IArpi/blob/main/README.es.md)

Con el objetivo de introducir los conceptos de Machine Learning en los cursos de física, presentamos el **IArpi**: un experimento de aplicación de la Inteligencia Artificial en el estudio del Rodamiento de objetos (esfera, cilindro y aro) en el Plano Inclinado. En este repositorio están disponibles los scripts de Python en Jupyter Notebook que contienen la aplicación de Machine Learning de Regresión y Clasificación sobre datos experimentales del rodamiento en el plano inclinado.


Para comprender la inserción de estos métodos en los cursos de grado de física, recolectamos datos de los planes de estudios (en portugués) de las disciplinas de física computacional (o relacionadas) de diferentes universidades federales de Brasil. Hicimos un análisis estadístico preliminar utilizando el procesamiento del lenguaje natural y el aprendizaje automático de clústeres y descubrimos que estos temas no se exploran en los cursos de física hasta la fecha. Los datos recopilados también están disponibles aquí. 

![](https://github.com/simcomat/IArpi/blob/main/iarpi.png)


## Organización
- En `datasets` están contenidos los ficheros `.csv` de los datos experimentales de rodamiento sobre el plano inclinado (`rolling.csv`) y el levantamiento de los menús (`curriculum.csv`) de Física Computacional, Cálculo Numérico y asignaturas afines cursos de pregrado de física en universidades federales brasileñas;
- En `notebooks` están los archivos `.ipynb` que contienen la secuencia de código para aplicar técnicas de Machine Learning en el conjunto de datos.


## Instalação

É necessário ter o `Python 3` instalado na máquina, com o gerenciador de pacotes `pip`. As bibliotecas utilizadas podem ser instaladas por:


- Framework de codificação Jupyter Notebook:
`pip install notebook`
- Para trabalhar com tabelas:
`pip install pandas`
- Para usar certas funções matemáticas:
`pip install numpy`
- Para plotar gráficos:
`pip install matplolib`
`pip install seaborn`
- Para usar algoritmos de Aprendizado de Máquina:
`pip install -U scikit-learn`


Ou todas as bibliotecas podem ser instaladas de uma só vez rodando o pip sobre o arquivo `requirements.txt`:
`pip install -r requirements.txt`
