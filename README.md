# LH_CD_ESTER_SANTOS
Desafio - Lighthouse Programa De Formação em Dados

Neste projeto foi realizada a análise de um conjunto de dados de uma plataforma de aluguéis temporários na cidade de Nova York. 
O objetivo é realizar uma análise exploratória (EDA) e desenvolver um modelo de previsão de preços. O modelo de predição escolhido foi o de regressão linear, em especial pela sua ampla gama aplicação na análise de dados, permitindo a análise de como uma variável dependente ("price") é afetada por uma ou mais variáveis independentes. 


Perguntas respondidas ao longo do projeto:
- Onde seria mais indicada a compra de um apartamento caso queira investir no mercado de aluguéis?
- O número mínimo de noites interferem no preço?
- Existe algum padrão no texto do nome do local para lugares de mais alto valor?


O notebook está estruturado da seguinte forma:

Importação das bibliotecas: 
Carregamento e manipulação dos dados: familiarização, limpeza e filtragem dos dados utilizados.
Visualização de dados geográficos com folium: a visualização geográfica pode ajudar a identificar padrões de preço de acordo com a localização além de ser uma potencial ferramenta para outros projetos.
Análise exploratória de dados: exploração visando identificar outliers, padrões e insights para a seleção de variáveis da regressão linear.
Predição de preços: ajuste dos dados para uso no modelo de ML, remoção de outliers, treinamento, teste e validação.


## Pré-requisitos

- Python - 3.11.5 
- Jupyter Notebook - 6.5.4 
- Conda - 23.7.4
- folium - 0.15.1
- pandas - 2.0.3
- seaborn - 0.12.2
- matplotlib - 3.7.2
- numpy - 1.24.3
- scikit-learn - 1.3.0
- numpy - 1.24.3


## Execução
-Clonar o Repositório do GitHub - Necessário ter o Git instalado em seu computador (se não tiver, você pode baixá-lo e instalá-lo a partir do site oficial do Git)
1: Abra o terminal (no Linux ou macOS) ou o prompt de comando/PowerShell (no Windows)
2: Navegue até o diretório onde deseja clonar o repositório
3: Use o comando git clone seguido do URL do repositório:
````
git clone https://github.com/dossantosester/LH_CD_ESTER_SANTOS.git
````
-Instalar as dependências necessárias 
No terminal execute:
````
pip install -r requirements.txt
````
-Abrir o Jupyter Notebook -  Se ainda não tiver o Jupyter Notebook instalado, você pode instalá-lo via pip:
````
pip install notebook
````
1:iniciar o notebook via terminal:
````
jupyter notebook
````
2: Navegar até o arquivo do notebook (.ipynb) e abri-lo.


