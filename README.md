# Ciência de dados
Repositório de material sobre Ciência de Dados

1) Criando o ambiente 'ds' (datascience) no conda e instalação de pacotes Python

O novo ambiente é criado a partir do comando:

$ conda env create -f environment.yml

Será criado o ambiente 'ds' com os seguintes pacotes:
 - numpy
 - pandas
 - matplotlib
 - pandas
 - scipy
 - seaborn
 - scikit-learn
 - tensorflow
 - keras
 - statsmodels
 - plotly
 - jupyter
 - jupyterlab
 - ipympl

Para ativar o ambiente 'ds', digite:

$ conda activate ds

Para saber a lista de pacotes instalados no ambiente atual, digite:

$ conda list

2) Instalando a biblioteca do OpenCV
Ative o ambinente e digite:

$ pip install opencv-python

3) Configurar o jupyter-notebook para opção auto-completion no code editor

No ambiente 'ds' digite:

$ pip install jupyter_contrib_nbextensions
$ jupyter contrib nbextension install

Abra o jupyter-notebook e na aba 'nbextensions' habilitar a opção 'Hinterland'
fonte: https://towardsdatascience.com/the-only-auto-completion-extension-youll-ever-need-for-your-jupyter-notebooks-87bbaecb7126 (acessado em 14/09/2022)

