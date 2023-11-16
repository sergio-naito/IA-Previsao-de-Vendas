# IA para Previsão de Vendas

Por que este projeto é importante para mim?

Resposta: Este projeto é importante, pois foi o primeiro projeto ou primeiro portfólio como Cientista de Dados, que inclui neste repositório do GitHub.
O meu aprendizado sobre Ciência de Dados, começou no dia 01.06.2023, quando conheci o Professor Eduardo - Ciência dos Dados do Programa CDPRO (Cientsta de Dados Profissional), quando o algoritmo do YouTube, me encontrou quando fazia pesquisa sobre Inteligência Artificial, e me apresentou um video sobre 10 dias de Aquecimento para o Evento da Era dos Dados.

Participei dos vídeos ao vivo, dos dias 05.06.2023 a 16.06.2023. Nestes vídeos foram feitas várias apresentações de algoritmos. 

Depois da semana de aquecimento foi a vez do Treinamento, propriamente dito.

Este projeto foi desenvolvido para Treinamento na Semana da Era dos Dados, realizado pelo Professor Eduardo - Ciência dos Dados, do Programa CDPRO (Cientista de Dados Profissional), nos dias 19, 21 e 23.06.2023, com o objetivo de criar uma Inteligência Artificial para Predição de Vendas.

A partir de primeiro projeto efetuado com sucesso, eu resolvi me matricular no [Curso Programa CDPRO do Professor Eduardo Rocha](https://github.com/sergio-naito/Programa-CDPRO/tree/main).

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


### gdown

O pacote gdown é uma biblioteca Python para baixar arquivos do Google Drive. Ele simplifica o processo de download de arquivos do Google Drive fornecendo uma interface amigável ao usuário e lidando com o processo de autenticação.

Para realizar o download de um arquivo do Google Drive, usamos o seguinte comando:

gdown https://drive.google.com/uc?id=1_kq8cZ4JZVsYw0BamYfiohSngLIJkoVb
Este comando irá baixar o arquivo dataset.csv para a pasta atual.


### pandas-profiling

O pacote pandas-profiling é uma biblioteca Python para fazer o perfil de DataFrames do pandas. Ele fornece uma visão abrangente dos dados, incluindo estatísticas, tipos de dados, valores ausentes e correlações.

### pandas

A biblioteca pandas é uma biblioteca Python para análise de dados. Ela permite carregar dados de diversos formatos, realizar limpeza e transformação de dados, e gerar relatórios e gráficos.

Para carregar um arquivo CSV com o pandas, use o seguinte código:

df = pd.read_csv('dataset.csv', delimiter=',')
Este código irá carregar o arquivo dataset.csv para um DataFrame do pandas.


### IPython.display

O módulo IPython.display fornece funções para exibir objetos em notebooks do IPython. Ele inclui funções para exibir texto, imagens, HTML e widgets interativos.

### numpy

O pacote numpy é uma biblioteca Python para computação numérica. Ele fornece funções e classes para trabalhar com arrays, matrizes e álgebra linear.


### sklearn.pipeline

O módulo sklearn.pipeline fornece ferramentas para criar pipelines, que são sequências de transformadores e estimadores. Os pipelines são úteis para simplificar o processo de construção de modelos de aprendizado de máquina.

### sklearn_model_selection

O módulo sklearn_model_selection fornece funções para avaliar e selecionar modelos de aprendizado de máquina. Ele inclui funções para dividir dados em conjuntos de treinamento e teste, validação cruzada e ajuste de hiperparâmetros.

### sklearn.preprocessing

O módulo sklearn.preprocessing fornece ferramentas para pré-processar dados antes de treinar modelos de aprendizado de máquina. Ele inclui funções para escalar recursos, codificar variáveis categóricas e imputar valores ausentes.

### imblearn

A biblioteca imblearn é uma biblioteca Python para aprendizado de máquina com conjuntos de dados desbalanceados. Ela fornece algoritmos e técnicas para lidar com o problema de desbalanceamento de classes.

### imblearn.over_sampling

O pacote imblearn.over_sampling fornece ferramentas para sobreamostragem de classes minoritárias em conjuntos de dados desbalanceados. Ele inclui algoritmos para gerar exemplos sintéticos de classe minoritária.

### lightgbm

O pacote lightgbm é uma biblioteca Python para máquinas de aprendizado por reforço e para aprendizado de máquina com árvores de decisão. É uma biblioteca de aprendizado de máquina rápida, eficiente e precisa que pode ser usada para uma variedade de tarefas, incluindo classificação, regressão e classificação.

### sklearn

A biblioteca sklearn é uma biblioteca Python para aprendizado de máquina. Ela fornece algoritmos para aprendizado supervisionado, aprendizado não supervisionado, aprendizado por reforço, e aprendizado de máquina com grandes conjuntos de dados.

### sklearn.metrics

O módulo sklearn.metrics fornece funções para avaliar o desempenho de modelos de aprendizado de máquina. Ele inclui funções para calcular métricas de classificação, como precisão, recall e pontuação F1.

### plotly.express

O pacote plotly.express fornece uma API de alto nível para criar visualizações interativas com Plotly. Ele simplifica o processo de criação de gráficos e tabelas fornecendo um conjunto de funções pré-definidas.

### plotly.graph_objects

O pacote plotly.graph_objects fornece uma API de nível inferior para criar visualizações interativas com Plotly. Ele oferece mais controle sobre a aparência e o comportamento de gráficos e tabelas.

### pickle

O módulo pickle fornece funções para serializar e desserializar objetos Python. Ele permite salvar objetos Python em um arquivo e carregá-los de volta para a memória em um momento posterior.

### streamlit

O pacote streamlit é uma biblioteca Python para criar aplicativos web interativos. Ele simplifica o processo de criação de aplicativos web com Python fornecendo uma interface amigável ao usuário e lidando com o código HTML, CSS e JavaScript.

### ngrok

O pacote ngrok é uma biblioteca Python para criar túneis para expor servidores web locais à internet. Ele permite testar seus aplicativos web localmente e compartilhá-los com outras pessoas sem ter que implantá-los em um servidor público, o que pode ser útil para fins de desenvolvimento ou teste.

Para criar um túnel de acesso à internet, usamos o seguinte código:

from pyngrok import ngrok

public_url = ngrok.connect(port='8501')
Este código irá criar um túnel de acesso à internet na porta 8501. A variável public_url irá conter o endereço público do servidor local.

A parte do pacote "ngrok" támbém não ficou muito claro e irei detalhar melhor também.

Para melhorar o entendimento eu irei colocar os print-screens das telas.

