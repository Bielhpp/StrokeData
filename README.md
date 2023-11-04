# StrokeData
 Projeto de estudo para analisar 
# StrokeData - Projeto de Estudo utilizando Google Colab

Objetivos de Ensino
Exercitar os seguintes conceitos das ferramentas:
✓ Exercitar o módulo Spark MLLib do Apache Spark.

Enunciado
Doenças ligadas ao coração afetam milhões de pessoas ao redor do mundo e, segundo a Organização Mundial da Saúde (OMS), são a segunda principal causa de morte da população mundial. Como cientista de dados, você foi contratado para criar um modelo preditivo que, a partir de dados de pacientes como idade, gênero, nível de glicose, se o paciente fuma ou não, vai prever se aquele paciente terá um derrame cerebral ou não.
O arquivo stroke_data.csv possui atributos de pacientes e um atributo “stroke” (derrame), que indica se aquele paciente sofreu um evento de derrame ou não.

O exercício serve para responder as seguintes perguntas:

1- Quantos registros existem no arquivo?
2- Quantas colunas existem no arquivo? Quantas são numéricas? Ao ler o arquivo com spark.read.csv, habilite inferSchema=True. Use a função printSchema() da API de Dataframes.
3- No conjunto de dados, quantos pacientes sofreram e não sofreram derrame (stroke), respectivamente?
4- A partir do dataframe, crie uma tabela temporária usando df.createOrReplaceTempView('table') e a seguir use spark.sql para escrever uma consulta SQL que obtenha quantos pacientes tiveram derrame por tipo de trabalho (work_type). Quantos pacientes sofreram derrame e trabalhavam respectivamente, no setor privado, de forma independente, no governo e quantas são crianças?
5- Escreva uma consulta com spark.sql para determinar a proporção, por gênero, de participantes do estudo. A maioria dos participantes é:
6- Escreva uma consulta com spark.sql para determinar quem tem mais probabilidade de sofrer derrame: hipertensos ou não-hipertensos. Você pode escrever uma consulta para cada grupo. A partir das probabilidades que você obteve, você conclui que:
7- Escreva uma consulta com spark.sql que determine o número de pessoas que sofreram derrame por idade. Com qual idade o maior número de pessoas do conjunto de dados sofreu derrame?
8- Usando a API de dataframes, determine quantas pessoas sofreram derrames após os 50 anos.
9- Usando spark.sql, determine qual o nível médio de glicose para pessoas que, respectivamente, sofreram e não sofreram derrame.
10- Qual é o BMI (IMC = índice de massa corpórea) médio de quem sofreu e não sofreu derrame?
11- Crie um modelo de árvore de decisão que prevê a chance de derrame (stroke) a partir das variáveis contínuas/categóricas: idade, BMI, hipertensão, doença do coração, nível médio de glicose. Use o conteúdo da segunda aula interativa para criar e avaliar o modelo.
Qual a acurácia de um modelo construído?
12- Adicione ao modelo as variáveis categóricas: gênero e status de fumante. Use o conteúdo da aula interativa para lidar com as variáveis categóricas.  A acurácia (qualidade) do modelo aumentou para:
13- Adicione ao modelo as variáveis categóricas: gênero e status de fumante. Use o conteúdo da aula interativa para lidar com as variáveis categóricas. Qual dessas variáveis é mais importante no modelo de árvore de decisão que você construiu?
14- Adicione ao modelo as variáveis categóricas: gênero e status de fumante. Use o conteúdo da aula interativa para lidar com as variáveis categóricas. Qual a profundidade da árvore de decisão? 
15- Quantos nodos a árvore de decisão possui?