# <font color=''>IA</font><font color='#7ac77a'>rpi</font>

[![en](https://img.shields.io/badge/lang-en-red.svg)](https://github.com/simcomat/IArpi/blob/main/README.md) [![pt-br](https://img.shields.io/badge/lang-pt--br-green.svg)](https://github.com/simcomat/IArpi/blob/main/README.pt-br.md) [![es](https://img.shields.io/badge/lang-es-yellow.svg)](https://github.com/simcomat/IArpi/blob/main/README.es.md)


To introduce Machine Learning concepts in physics courses we present the **IArpi**, an experiment of application artificial intelligence to the rolling on an inclined plane physics problem. In this repository are available Python Jupyter Notebook scripts with Regression and Classification Machine Learning applications on experimental data of rolling on an inclined plane. 

To understand the insertion of these concepts in brazilian physics undergraduate programs, we collected curriculum of Computatinal Physics subjects (or correlated such as Numerical Calculus) from public federal universities in Brazil. We did a preliminary statistical analysis using Natural Language Processing and Clustering Machine Learning, showing that these topics are not explored in physics courses until now. The collected data are also available here. 


![](https://github.com/simcomat/IArpi/blob/main/iarpi.png)


## Repository Structure
- In `datasets` folder are the `.csv` files with experimental data (`rolling.csv`) and curriculum subjects (`curriculum.csv`) in portuguese.
- In `notebooks` folder is the `.ipynb` file with Python code of Machine Learning over the rolling data.

## Online Use

You can run the code at [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/simcomat/IArpi/blob/main/notebooks/iarpi.ipynb)

## Requeriments
It is necessary a `Python 3` installation, with `pip` package manager. The used libraries can be installed by:


- Jupyter Notebook framework:
`pip install notebook`
- To work with tables:
`pip install pandas`
- To use some math functions:
`pip install numpy`
- To plot graphs:
`pip install matplolib`
`pip install seaborn`
- To use Machine Learning algorithms:
`pip install -U scikit-learn`


Otherwise, all libraries can be installed in one shot running pip over `requirements.txt` file by:
`pip install -r requirements.txt`

## Related Work
H. Ferreira, E. F. Almeida Junior, W. Espinsa-Garcia, E. Novais, J. N. B. Rodrigues, G. M. Dalpian. Introduzindo aprendizado de máquina em cursos de física: o caso do rolamento do plano inclinado, Revista Brasileira de Ensino de Física, vol. 44, 2022. DOI: https://doi.org/10.1590/1806-9126-RBEF-2022-0214   
