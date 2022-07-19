# <font color=''>IA</font><font color='#7ac77a'>rpi</font>

[![en](https://img.shields.io/badge/lang-en-red.svg)](https://github.com/simcomat/IArpi/blob/main/README.md) [![pt-br](https://img.shields.io/badge/lang-pt--br-green.svg)](https://github.com/simcomat/IArpi/blob/main/README.pt-br.md) [![es](https://img.shields.io/badge/lang-es-yellow.svg)](https://github.com/simcomat/IArpi/blob/main/README.es.md)

Visando introduzir conceitos de Aprendizado de Máquina para cursos de física, apresentamos o **IArpi**: um experimento de aplicação de Inteligência Artificial no estudo do Rolamento no Plano Inclinado. Neste repositório estão disponíveis os scripts em Python Jupyter Notebook contendo a aplicação de Aprendizado de Máquina de Regressão e Classificação em dados experimentais de rolamento no plano inclinado.


Para entender a inserção desses métodos em cursos de graduação de física, coletamos dados de ementas (em português) de disciplinas de física computacional (ou correlatas) de diferentes universidades federais do Brasil. Fizemos uma análise estatística preliminar usando Processamento de Linguagem Natural e Aprendizado de Máquina de Agrupamento, encontrando que esses assuntos não são explorados em cursos de física até o momento. Os dados coletados também estão disponibilizados aqui. 

![](https://github.com/simcomat/IArpi/blob/main/iarpi.png)


## Organização
- Em `datasets` estão contidos os arquivos `.csv` dos dados experimentais de rolamento no plano inclinado (`rolling.csv`) e do levantamento das ementas (`curriculum.csv`) de disciplinas de Física Computacional, Cálculo Numérico e correlatas de cursos de graduação em física de universidades federais brasileiras;
- Em `notebooks` estão os arquivos `.ipynb` contendo a sequência de códigos para aplicação das técnicas de Aprendizado de Máquina sobre o dataset.


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