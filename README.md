# Análise e Projeções - Empresa de Cartão de Crédito

DESAFIO: EMPRESA DE CARTÃO DE CRÉDITO

Você trabalha em uma grande empresa de Cartão de Crédito e o diretor da empresa percebeu que o número de clientes que cancelam seus cartões tem aumentado significativamente, causando prejuízos enormes para a empresa.

O que fazer para evitar isso? Como saber quais as pessoas que têm maior tendência a cancelar o cartão?

O QUE TEMOS:

Temos 1 base de dados com informações dos clientes, tanto clientes atuais quanto clientes que cancelaram o cartão.

Base de Dados: Kaggle traduzido por Hashtag Treinamentos.

- Passo 1: Importar a Base de Dados
  - Excluir colunas inúteis
- Passo 2: Tratamento da Base de Dados
  - Excluir/Corrigir linhas e colunas vazias
  - Ajeitar as colunas importadas
- Passo 3: Analisar a base de dados
  - Queremos descobrir os principais motivos de cancelamento de cartão
- Passo 4: Analisar os problemas seguindo a Regra de Pareto como referência. 
  - Quais são os 20% de características que podem estar afetando 80% dos resultados?
  - Criação de gráficos com Plotly Express

Percepção pós-análise:

1. Quase todos os clientes que cancelaram são da categoria Blue

2. Quanto mais um cliente entra em contato com o Banco, maior a chance do mesmo solicitar o cancelamento do produto. - > Plano de ação: Analisar o motivo do contato / tratar os clientes que mais entraram em contato com a entidade financeira.

3. Há uma percepção de que quanto menos o cliente utiliza o cartão, maiores as chances de solicitação de um eventual cancelamento do produto.
    - Com mais de 80 transações realizadas com o produto, a porcentagem de cancelamento é quase nula;
    - Clientes com menos de 60 transações são muito críticos;
    - A mesma coisa acontece com a quantidade de transações.
