# 📊 Análise Exploratória de Dados Profissionais
Este projeto tem como objetivo realizar uma análise exploratória de um conjunto de dados contendo informações de 1050 profissionais de diferentes áreas. A partir dessas informações, buscamos identificar padrões relacionados à faixa etária, localização, gênero, evasão e outros aspectos relevantes.

📁 Sobre o Dataset
O arquivo utilizado é o dataset_analise_exploratoria.csv, que contém as seguintes colunas:

ID: Identificador único do funcionário

Nome: Nome completo

Idade: Idade do funcionário

Sexo: Masculino ou Feminino

Cidade: Cidade de residência

Profissão: Cargo ocupado

Salário: Valor do salário mensal

Data_Admissão: Dados de engajamento

Ativo: Indica se o funcionário ainda está vinculado à empresa (Sim/Não)

🔍 Etapas da Análise
📥 1. Carregamento e Inspeção Inicial
Importação de dados com a bibliotecapandas

Verificação de formato, tipos de dados e possíveis valores ausentes

📊 2. Análises Realizadas
🧑‍💼 Salário médio por profissão
Agrupamento por profissão e cálculo do salário médio

Visualização dos dados com gráficos de barras

🚻 Diferença salarial entre gêneros
Comparação do salário médio entre homens e mulheres

🛠️ Profissões da área exata
Filtragem das profissões técnicas (como Engenheiro, Desenvolvedor, Arquiteto, etc.)

Análise específica da média salarial dessas áreas

📉 Funcionários ativos e evasão
Contagem de profissionais ativos e inativos por profissão

Identificação das profissões com maior evasão

🗺️ Distribuição geográfica dos profissionais
Quantidade de profissionais por cidade

Foco na cidade de Salvador, onde há maior concentração

💰 Média salarial por cidade
Comparação do salário médio entre diferentes cidades

Exportação de dados em arquivos.csv

🗂️ Arquivos Gerados
Salarios_por_cidade.csv: Tabela com a média salarial por cidade

Funcionarios_salvador.csv: Lista de profissionais que atuam em Salvador

🧾 Conclusões
Profissões técnicas tendem a ter evolução mais elevada.

Existe uma diferença salarial entre os gêneros.

A cidade de Salvador concentra a maior parte dos profissionais específicos.

As informações levantadas podem orientar decisões estratégicas, como a criação de unidades físicas e alocação de recursos.

🛠️ Tecnologias Utilizadas
Python 3

Pandas

Matplotlib

Google Colab

🚀 Próximos Passos
Incluir visualizações mais avançadas com SeabornouPlotly

Tratar e padronizar os dados (dados, valores inconsistentes, etc.)

Realizar análise temporal com base nos dados de admissão

Aplicar técnicas de clusterização para segmentação de perfis profissionais

