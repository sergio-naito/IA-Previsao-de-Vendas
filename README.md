# IA para Previsão de Vendas

Por que este projeto é importante para mim?

Resposta: Este projeto é importante, pois foi o primeiro projeto ou primeiro portfólio como Cientista de Dados, que inclui neste repositório do GitHub.
O meu aprendizado sobre Ciência de Dados, começou no dia 01.06.2023, quando conheci o Professor Eduardo - Ciência dos Dados do Programa CDPRO (Cientsta de Dados Profissional), quando o algoritmo do YouTube, me encontrou quando fazia pesquisa sobre Inteligência Artificial, e me apresentou um video sobre 10 dias de Aquecimento para o Evento da Era dos Dados.

Participei dos vídeos ao vivo, dos dias 05.06.2023 a 16.06.2023. Nestes vídeos foram feitas várias apresentações de algoritmos. 

Depois da semana de aquecimento foi a vez do Treinamento, propriamente dito.

Este projeto foi desenvolvido para Treinamento na Semana da Era dos Dados, realizado pelo Professor Eduardo - Ciência dos Dados, do Programa CDPRO (Cientista de Dados Profissional), nos dias 19, 21 e 23.06.2023, com o objetivo de criar uma Inteligência Artificial para Predição de Vendas.

Feita a utilização da linguagem Python, com os seguintes pacotes:
- gdown
- ProfileReport (pandas-profiling)
- <notranslate>display</notranslate>(IPYthon.display)
- html (IPYthon.display)
- pandas
- <notranslate>numpy</notranslate>
- make_pipeline (sklearn.pipeline)
- train_test_split (sklearn_model_selection)
- StandardScaler (sklearn_preprocessing)
- <notranslate>OneHotEncoder</notranslate> (sklearn_model_selection)
- ColumnTransformer (sklearn.compose)
- SMOTE (imbleam.over_sampling)
- LGBM<notranslate>Classifier</notranslate> (lightgbm)
- <notranslate>classificationreport</notranslate> (sklearn.metrics)
- <notranslate>accuracyscore</notranslate> (sklearn.metrics)
- plotly.express
- plotly.graph_objects
- <notranslate>pickle</notranslate>: https://docs.python.org/3/library/pickle.html[target="_blank"]
- <notranslate>streamlit</notranslate>
- ngrok
- e principalmente o Deploy, que mostra o resultado da previsão no Browser, no Smartphone, no Tablet.


Observações: 
- algumas palavras dos pacotes estao com "underscore (_)" para manter a palavra em inglês, sem que faça a tradução para o português;
- também tem a dica de colocar um link da palavra em inglês e no final colocar [target="_blank"], para manter a palavra em inglês.
- inclusão de \<notranslate\> <notranlate> streamlit </notranslate> \<\/notranslate\> e a palavra em inglês no meio de \<notranslate\>, que não deve ser traduzido, para o Português. Sem as tags a tradução automática ficaria "iluminado".

## Descrição detalhada de cada pacote

Aqui irei detalhar cada pacote do Python.

A parte mais importante que é o Deploy, não ficou muito claro e irei detalhar melhor.

#gdown - para fazer o download do arquivo

#ProfileReport
A parte do pacote "ngrok" támbém não ficou muito claro e irei detalhar melhor também.

Para melhorar o entendimento eu irei colocar os print-screens das telas.


## Bibliotecas Python para realizar o acesso aos dados

  gdown: Biblioteca Python para realizar o download de arquivos do Google Drive.

## Bibliotecas Python para manipulação de dados

pandas: Biblioteca Python para análise de dados.

numpy: Biblioteca Python para cálculo numérico.

## Bibliotecas Python para IA - Machine Learning e Automações

sklearn: Biblioteca Python para aprendizado de máquina.

imblearn: Biblioteca Python para aprendizado de máquina com conjuntos de dados desbalanceados.

lightgbm: Biblioteca Python para aprendizado de máquina com árvores de decisão.

pyngrok: Biblioteca Python para criar túneis de acesso à internet.


Detalhes de cada biblioteca

gdown

A biblioteca gdown é uma biblioteca Python que permite realizar o download de arquivos do Google Drive. Para instalar a biblioteca, execute o seguinte comando no terminal:

Para realizar o download de um arquivo do Google Drive, use o seguinte comando:

gdown https://drive.google.com/uc?id=1_kq8cZ4JZVsYw0BamYfiohSngLIJkoVb
Este comando irá baixar o arquivo dataset.csv para a pasta atual.

pandas

A biblioteca pandas é uma biblioteca Python para análise de dados. Ela permite carregar dados de diversos formatos, realizar limpeza e transformação de dados, e gerar relatórios e gráficos.

Para instalar a biblioteca, execute o seguinte comando no terminal:

Para carregar um arquivo CSV com o pandas, use o seguinte código:

df = pd.read_csv('dataset.csv', delimiter=',')
Este código irá carregar o arquivo dataset.csv para um DataFrame do pandas.

numpy

A biblioteca numpy é uma biblioteca Python para cálculo numérico. Ela fornece funções e classes para realizar operações matemáticas e estatísticas com arrays.

Para instalar a biblioteca, execute o seguinte comando no terminal:

sklearn

A biblioteca sklearn é uma biblioteca Python para aprendizado de máquina. Ela fornece algoritmos para aprendizado supervisionado, aprendizado não supervisionado, aprendizado por reforço, e aprendizado de máquina com grandes conjuntos de dados.

Para instalar a biblioteca, execute o seguinte comando no terminal:

imblearn

A biblioteca imblearn é uma biblioteca Python para aprendizado de máquina com conjuntos de dados desbalanceados. Ela fornece algoritmos e técnicas para lidar com o problema de desbalanceamento de classes.

Para instalar a biblioteca, execute o seguinte comando no terminal:

lightgbm

A biblioteca lightgbm é uma biblioteca Python para aprendizado de máquina com árvores de decisão. Ela é uma biblioteca eficiente e precisa, que pode ser utilizada para diversos problemas de aprendizado de máquina.

Para instalar a biblioteca, execute o seguinte comando no terminal:

pyngrok

A biblioteca pyngrok é uma biblioteca Python para criar túneis de acesso à internet. Ela permite expor um servidor local à internet, o que pode ser útil para fins de desenvolvimento ou teste.

Para instalar a biblioteca, execute o seguinte comando no terminal:

Para criar um túnel de acesso à internet, use o seguinte código:

from pyngrok import ngrok

public_url = ngrok.connect(port='8501')
Este código irá criar um túnel de acesso à internet na porta 8501. A variável public_url irá conter o endereço público do servidor local.
  
