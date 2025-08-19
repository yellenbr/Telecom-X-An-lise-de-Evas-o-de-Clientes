# Telecom-X-An-lise-de-Evas-o-de-Clientes
Uma análise de dados da Telecom X que realiza o processo de ETL e exploração estatística para identificar padrões de evasão de clientes e propor estratégias de retenção.
Descrição

Este projeto tem como objetivo realizar o processo de ETL (Extração, Transformação e Carga) e a Análise Exploratória de Dados (EDA) sobre a base de clientes da Telecom X, empresa fictícia de telecomunicações que enfrenta alta taxa de evasão (Churn).

A análise busca identificar padrões e fatores associados ao cancelamento de clientes, fornecendo insights que podem ser usados em modelos preditivos e em estratégias de retenção.

🛠️ Tecnologias Utilizadas

Python 3.10+

Pandas – manipulação e limpeza dos dados

Seaborn – visualizações estatísticas

Matplotlib – gráficos e análises visuais

Jupyter Notebook / Google Colab

📌 Etapas do Projeto

Extração

Importação dos dados no formato JSON.

Normalização das tabelas aninhadas (clientes, telefone, internet, conta).

Transformação

Limpeza de valores nulos e inconsistentes.

Conversão de variáveis numéricas e categóricas.

Criação da variável binária Churn (1 = saiu, 0 = permaneceu).

Carga e Análise (EDA)

Estatísticas gerais da base de clientes.

Visualizações: churn por tipo de contrato, método de pagamento, mensalidade e tenure.

Heatmap de correlação entre variáveis numéricas.

Relatório Final

Taxa de churn identificada (~27%).

Clientes com contrato "Month-to-month" são os mais propensos a sair.

Pagamento por "Electronic Check" aparece fortemente associado ao churn.

Clientes novos (tenure < 12 meses) apresentam maior risco de evasão.

Senior Citizens demonstram taxa de cancelamento mais alta.

📈 Principais Insights

Incentivar contratos de longo prazo (1–2 anos).

Criar programas de fidelização para novos clientes.

Reduzir churn migrando clientes de electronic check para meios automáticos de pagamento.

Oferecer benefícios personalizados a clientes de maior risco.

▶️ Como Executar o Projeto

Clone o repositório ou baixe os arquivos.

Instale as dependências:

pip install pandas seaborn matplotlib


Abra o notebook no Jupyter ou Google Colab.

Execute as células nas seções:

Extração

Transformação

Carga e análise

Relatório Final

👩‍💻 Autoria

Desenvolvido como parte do desafio "Telecom X: Análise de Evasão de Clientes", ministrado pela instrutora Ingrid Silva.
