<div align="justify">
  
# Compilado de projetos de Business Intelligence e Data Science utilizando Power BI
#### Autor: Guilherme Oliveira da Rocha Cunha

Estes projetos foram apresentados no curso **Microsoft Power BI Para Business Intelligence e Data Science** oferecido pelo portal de capacitação profissional Data Science Academy (DSA) ([link](https://www.datascienceacademy.com.br/course/microsoft-power-bi-para-business-intelligence-e-data-science)). Neste curso foi abordado não apenas a como utilizar o Microsoft Power BI, mas também como aplicar técnicas de Data Science para gerar modelos preditivos e extrair insights para a tomada de decisões, integrando o Power BI com Linguagem R e Python.

Os projetos são demonstrados em laboratórios práticos ou em mini-projetos, onde em cada um deles foram exploradas e trabalhadas diversas funcionalidades do Power BI, assim como foram estudadas e executadas soluções para diferentes problemas que podem vir a surgir em uma análise exploratória de dados. Todos os laboratórios e mini-projetos foram refeitos do zero por mim, construídos de acordo com as instruções do professor Daniel Mendes, instrutor responsável por este curso. Todo o material utilizado e produzido, incluindo os conjuntos de dados disponibilizados pela DSA (.csv ou .xlsx) e os relatórios/dashboards feitos por mim (.pbix), estão presentes neste repositório.

## Sumário

### Parte 1: Business Intelligence
#### [1. Laboratório Prático 1 - Dashboard Analítico de Vendas Globais](#1-laboratório-prático-1---dashboard-analítico-de-vendas-globais-1)
#### [2. Laboratório Prático 2 - Dashboard de Vendas, Custo, Margem de Lucro e KPI](#2-laboratório-prático-2---dashboard-de-vendas-custo-margem-de-lucro-e-kpi-1)
#### [3. Mini-Projeto 1 - Análise de Campanhas de Marketing](#3-mini-projeto-1---análise-de-campanhas-de-marketing-1)
#### [4. Mini-Projeto 2 - Análise de Dados Comerciais: Performance de Vendas](#4-mini-projeto-2---análise-de-dados-comerciais-performance-de-vendas-1)
#### [5. Mini-Projeto 3 - Análise de Dados de Recursos Humanos](#5-mini-projeto-3---análise-de-dados-de-recursos-humanos-1)
#### [6. Mini-Projeto 4 - Análise de Dados de Logística](#6-mini-projeto-4---análise-de-dados-de-logística-1)
#### [7. Mini-Projeto 5 - Análise de Dados Financeiros](#7-mini-projeto-5---análise-de-dados-financeiros-1)
#### [8. Laboratório Prático 3 - Análise de Dados Contábeis: Balanço patrimonial](#8-laboratório-prático-3---análise-de-dados-contábeis-balanço-patrimonial-1)
#### [9. Mini-Projeto 6 - Análise de Dados do Mercado de Ações](#9-mini-projeto-6---análise-de-dados-do-mercado-de-ações-1)

### Parte 2: Data Science
#### [10. Laboratório Prático 4 - Limpeza e Manipulação de Dados de Cadastro de Clientes](#10-laboratório-prático-4---limpeza-e-manipulação-de-dados-de-cadastro-de-clientes-1)
#### [11. Laboratório Prático 5 - Engenharia de Atributos com Linguagem M](#11-laboratório-prático-5---engenharia-de-atributos-com-linguagem-m-1)
#### [12. Laboratório Prático 6 - Integrando Banco de Dados com Power BI para Extração e Análise de Dados](#12-laboratório-prático-6---integrando-banco-de-dados-com-power-bi-para-extração-e-análise-de-dados-1)
#### [13. Laboratório Prático 7 - Machine Learning com Linguagem Python e Power BI dentro do Jupyter Notebook](#13-laboratório-prático-7---machine-learning-com-linguagem-python-e-power-bi-dentro-do-jupyter-notebook-1)
#### [14. Laboratório Prático 8 - Detecção de Anomalias em Transações Financeiras com Linguagem R e Power BI](#14-laboratório-prático-8---detecção-de-anomalias-em-transações-financeiras-com-linguagem-r-e-power-bi-1)
#### [15. Laboratório Prático 9 - Engenharia de Producão com Power BI e IA: Prevendo a Produção Industrial ao Longo do Tempo](#15-laboratório-prático-9---engenharia-de-producão-com-power-bi-e-ia-prevendo-a-produção-industrial-ao-longo-do-tempo-1)

## 1. Laboratório Prático 1 - Dashboard Analítico de Vendas Globais
Neste laboratório foram utilizados dados de vendas de uma empresa fictícia que comercializa produtos em todos os cantos do mundo.

O Dashboard deve responder às seguintes perguntas de negócio e seguir as seguintes especificações:
- Pergunta 1 - Qual o valor total vendido?
- Pergunta 2 - Quantas vendas foram realizadas por categoria de produto?
- Pergunta 3 - Quantas vendas foram realizadas por país considerando a prioridade de entrega?
- Pergunta 4 - Qual foi a média de desconto nas vendas por subcategoria de produto?
- Pergunta 5 - Quais países tiveram maior média de valor de venda? Demonstre em um mapa.

O Dashboard deve dar ao usuário a possibilidade de filtrar os dados por ano, por segmento e por país.

### 1.1. Dashboard Analítico de Vendas Globais
![Lab_1](https://github.com/Gui-lherme-Oliv/Data-Analysis_PowerBI/assets/123426025/cbcad32a-37dc-42c8-95a3-d433406d0ac1)

#### [Voltar ao Sumário](#sumário)
## 2. Laboratório Prático 2 - Dashboard de Vendas, Custo, Margem de Lucro e KPI
Neste laboratório foram explorados os conceitos de modelagem de dados, cardinalidade, recursos de limpeza de dados do Power BI e introdução ao DAX. Foram utilizados dados de vendas fictícios obtidos em 4 diferentes tabelas: Clientes, Pedidos, Produtos e Vendas.

O Dashboard deve responder às seguintes perguntas de negócio e seguir as seguintes especificações:
- Pergunta 1 - Qual foi o total de valor venda considerando cada modo de envio dos pedidos? Use um gráfico de cascata.
- Pergunta 2 - Quais mercados tiveram o maior custo médio de envio dos produtos vendidos? Use um gráfico treemap.
- Pergunta 3 - A empresa tem como objetivo (meta) manter uma média de 350 para o valor de venda todos os meses. Mostre um indicador (KPI – Key Performance Indicator) com o valor médio de venda. A empresa ficou abaixo ou acima da meta no mês de Abril/2014?
- Pergunta 4 - Considere que o lucro é equivalente a: Valor Venda - Custo Envio. Qual categoria de produto apresentou maior lucro médio?
- Pergunta 5 - Qual foi o comportamento da margem de lucro ao longo do tempo? Considere a margem de lucro como o Lucro dividido pelo Valor Venda.

### 2.1. Dashboard de Vendas, Custo, Margem de Lucro e KPI
![Lab_2](https://github.com/Gui-lherme-Oliv/Data-Analysis_PowerBI/assets/123426025/18db1226-36dd-4de9-b5c1-98f6f367fcd4)

#### [Voltar ao Sumário](#sumário)
## 3. Mini-Projeto 1 - Análise de Campanhas de Marketing
Este Mini-Projeto trouxe uma breve introdução à análise de campanhas de Marketing com o Power BI. Foram gerados 4 Dashboards, mais de 10 elementos visuais, customizações, formatações, correções nos dados e utilização de diferentes recursos do Power BI. Os dados foram previamente customizados para este Mini-Projeto e representam informações sobre clientes e campanhas de Marketing realizadas por uma empresa fictícia.

Neste Mini-Projeto os relatórios foram divididos em 4 visões:
- Visão do Cliente
- Visão do Comportamento de Compra do Cliente
- Visão da Performance das Campanhas de Marketing
- Visão dos Padrões de Compra no Ponto de Venda (País)

Para cada visão foram compreendidas as variáveis, criados gráficos, medidas, extraídas métricas e cruzados os dados, visando entregar aos tomadores de decisão uma visão bastante completa sobre o perfil dos clientes, os padrões de compra e a efetividade das campanhas de Marketing.

### 3.1. Dashboard - Visão do Cliente
![MP_1-1](https://github.com/Gui-lherme-Oliv/Data-Analysis_PowerBI/assets/123426025/11e95a31-4018-4487-9e38-6f919614c33a)

### 3.2. Dashboard - Visão do Comportamento de Compra do Cliente
![MP_1-2](https://github.com/Gui-lherme-Oliv/Data-Analysis_PowerBI/assets/123426025/6964d293-9cbb-4e95-8f87-e6ff850d442e)

### 3.3. Dashboard - Visão da Performance das Campanhas de Marketing
![MP_1-3](https://github.com/Gui-lherme-Oliv/Data-Analysis_PowerBI/assets/123426025/0814f65a-59f0-4a38-9166-c4447ce469bf)

### 3.4. Dashboard - Visão dos Padrões de Compra no Ponto de Venda (País)
![MP_1-4](https://github.com/Gui-lherme-Oliv/Data-Analysis_PowerBI/assets/123426025/50cbaff8-1cdb-464c-8b47-1d5dbe5a4686)

#### [Voltar ao Sumário](#sumário)

## 4. Mini-Projeto 2 - Análise de Dados Comerciais: Performance de Vendas
Neste Mini-Projeto foi trabalhado um problema da área comercial, especificamente para analisar a performance de vendas de uma empresa fictícia. Ele trouxe uma breve introdução à análise de dados comerciais com o Power BI. Foram construídas diversas visualizações para compreender a performance de vendas de uma empresa fictícia por diferentes ângulos. Neste Mini-Projeto aprendi a trabalhar com interessantes recursos do Power BI como a Narrativa Inteligente, Principais Influenciadores, Gráfico de Faixas e criação de menu para índice do Dashboard.

### 4.1. Dashboard - Narrativa Inteligente
![MP_2-1](https://github.com/Gui-lherme-Oliv/Business-Intelligence_PowerBI/assets/123426025/70264d99-ce13-46f0-a111-98f9d6a82b6c)

### 4.2. Dashboard - Principais Influenciadores de Vendas
![MP_2-2](https://github.com/Gui-lherme-Oliv/Business-Intelligence_PowerBI/assets/123426025/0a4372f2-152b-4a74-a3c7-90b91230d048)

### 4.3. Dashboard - Faixas de Vendas por Categoria e Pontos de Venda
![MP_2-3](https://github.com/Gui-lherme-Oliv/Business-Intelligence_PowerBI/assets/123426025/7af9ded3-016a-4811-95ca-d0f11a7b4eee)

### 4.4. Dashboard - Performance dos Vendedores por Região
![MP_2-4](https://github.com/Gui-lherme-Oliv/Business-Intelligence_PowerBI/assets/123426025/cf72d09e-87e5-426b-8c68-94a2862d5860)

### 4.5. Menu para Navegador de Página
![MP_2-5](https://github.com/Gui-lherme-Oliv/Business-Intelligence_PowerBI/assets/123426025/db3c11b9-0678-4e8b-8c34-893d293dad0e)

#### [Voltar ao Sumário](#sumário)
## 5. Mini-Projeto 3 - Análise de Dados de Recursos Humanos
Este Mini-Projeto trouxe uma breve introdução à análise de dados de RH (Recursos Humanos) com o Power BI, onde foram utilizados dados fictícios. Durante o projeto foram trabalhados alguns outros recursos e funcionalidades do Power BI, como tabela de medidas e coluna condicional. 

O Dashboard criado deve responder às seguintes perguntas de negócio e seguir as seguintes especificações:
- Qual o total de funcionários atualmente na empresa?
- Qual o tempo médio de experiência dos funcionários (em anos)?
- Qual o total e percentual de funcionários do gênero masculino e feminino?
- Qual a média salarial mensal?
- Qual o total de funcionários por função?
- Qual o percentual de funcionários disponíveis para fazer hora extra?
- Qual o nível de envolvimento dos funcionários no trabalho considerando 4 categorias: Ruim, Baixo, Médio e Alto?
- Este item não deve estar no Dashboard, mas precisa ser calculado: Qual o total e o percentual de funcionários que devem receber promoção? Considerando a coluna “Anos Desde a última Promoção” com a seguinte regra: Se o funcionário tiver 5 anos ou mais desde a última promoção, deve ter a promoção considerada. Caso contrário, a promoção não deve ser considerada agora.

### 5.1. Dashboard - Análise de Dados de Recursos Humanos
![MP_3](https://github.com/Gui-lherme-Oliv/Business-Intelligence_PowerBI/assets/123426025/10a17924-8999-441d-a970-7a26560acfd1)

#### [Voltar ao Sumário](#sumário)
## 6. Mini-Projeto 4 - Análise de Dados de Logística
Este Mini-Projeto apresentou o seguinte estudo de caso com dados fictícios: Uma empresa de logística solicitou que um profissional fornecesse um dashboard para compreender como está o processo de entrega de produtos da empresa. O profissional não parecia ter muito conhecimento sobre Power BI e entregou um trabalho com nítidos problemas e erros. Os diretores da empresa pediram minha ajuda para revisar o dashboard, identificar e corrigir erros e problemas e apresentar uma nova versão. Todos os erros e problemas detectados devem ser justificados.

O Dashboard precisaria mostrar os seguintes KPIs de Logística:
- Total de Entregas no Prazo Por Canal de Entrega
- Percentual de Entregas Antecipadas Por Equipe de Entrega
- Total de Entregas Por Mês
- Total de Entregas de Produtos dos Top 5 Vendedores
- Total de Entregas com Atraso Por Cidade
- Percentual de Entregas Por Status de Entrega

Durante o projeto foram trabalhados alguns outros recursos e funcionalidades do Power BI, como classificação de rating e filtro com medida DAX. 

### 6.1. Dashboard - Análise de Dados de Logística
![MP_4](https://github.com/Gui-lherme-Oliv/Business-Intelligence_PowerBI/assets/123426025/ca6ca8fb-244f-4e0c-a6f5-07431564b8cb)

#### [Voltar ao Sumário](#sumário)
## 7. Mini-Projeto 5 - Análise de Dados Financeiros
Neste Mini-Projeto foram exploradas mais algumas funcionalidades do Power BI, agora no contexto da área de finanças. Foram utilizados dados fictícios, que continham problemas de layout colocados propositalmente e que foram então resolvidos, utilizando algumas funcionalidades inclusive o pivot de tabela.

Estudo de caso: Sua empresa deseja ter uma visão das receitas e despesas e solicitou que você criasse um Dashboard que permita analisar os seguintes indicadores financeiros:
- Total de Receitas
- Total de Despesas
- Margem de Lucro
- Total de Receitas Por Componente
- Total de Despesas Por Componente em relação à média de Despesas
- Total  de  Receitas e  Despesas Por  Componente  e  Por  Ano, com  a  hierarquia Tipo/Componente.

Além disso a empresa precisa identificar os segmentos onde Receitas e Despesas são maiores e menores a fim de traçar seu plano estratégico. Seu trabalho é converter os dados brutos em conhecimento para suportar a tomada de decisões, através da análise de dados.

### 7.1. Dashboard - Análise de Dados Financeiros
![MP_5](https://github.com/Gui-lherme-Oliv/Business-Intelligence_PowerBI/assets/123426025/cf1d1e80-1cc6-4ffb-b083-c1e599aecc63)

#### [Voltar ao Sumário](#sumário)
## 8. Laboratório Prático 3 - Análise de Dados Contábeis: Balanço Patrimonial
Neste  laboratório foi construído um importante relatório contábil no Power BI, o Balanço Patrimonial. Utilizando dados fictícios, foram exploradas as funcionalidades do visual de Matriz, e estudadas em detalhes outras diversas funcionalidades do Power BI.

### 8.1. Dashboard - Balanço Patrimonial
![Lab_3](https://github.com/Gui-lherme-Oliv/Business-Intelligence_PowerBI/assets/123426025/a3eb827f-6e24-4f0f-8108-9940245d2cf2)

#### [Voltar ao Sumário](#sumário)
## 9. Mini-Projeto 6 - Análise de Dados do Mercado de Ações
Neste Mini-Projeto foi construído um Dashboard Analítico do Mercado de Ações. Duas funcionalidades do Power BI foram exploradas: a Narrativa Inteligente e a Time Intelligence (manipulação de data). Foram utilizados dados reais, disponíveis publicamente, extraídos do portal da NASDAQ ([link](https://www.nasdaq.com/market-activity/stocks)). Os dados da NASDAQ incluem várias colunas, cada uma fornecendo informações específicas sobre o preço e o volume de negociação das ações negociadas no mercado. Foram escolhidos dados de 5 empresas: IBM, Microsoft, Oracle, Tesla e Walmart.

O Dashboard deverá responder às seguintes perguntas de negócio e seguir as seguintes especificações:
- Qual o total de volume negociado de ações ao longo do tempo para as 5 empresas que estão sendo analisadas? Permita que essa análise seja feita para uma única empresa ou combinação de empresas.
- Qual o valor médio de abertura (Open), mais alto (High), mais baixo (Low) e de fechamento (Close) das ações de todas as empresas para todos os meses do período de  dados  analisado  (1 ano em nosso exemplo)? Mostre no formato de tabela e permita que essa análise seja feita para uma única empresa ou combinação de empresas.
- Qual a variação da média do valor de fechamento (close) das ações de todas as empresas ao longo do tempo, mês a mês? Permita que essa análise seja feita para uma única empresa ou combinação de empresas.
- Use a Narrativa Inteligente para explicar as principais características e tendências nos dados.
- O Dashboard deve ser formatado.

### 9.1. Dashboard - Análise de Dados do Mercado de Ações
![MP_6](https://github.com/Gui-lherme-Oliv/BI_DS_PowerBI/assets/123426025/a953d7c1-f0b9-4bde-afac-3d18eb525374)

#### [Voltar ao Sumário](#sumário)
## 10. Laboratório Prático 4 - Limpeza e Manipulação de Dados de Cadastro de Clientes
Este laboratório prático foi focado na limpeza e manipulação de dados com Power BI, utilizando dados fictícios. Atividades realizadas durante o laboratório:
- Identificação e tratamento de registros duplicados.
- Identificação e tratamento de valores ausentes.
- Identificação e tratamento de valores outliers.

### 10.1. Visualizando os outliers
![Lab_4](https://github.com/Gui-lherme-Oliv/BI_DS_PowerBI/assets/123426025/25104ff5-b1f2-4dcf-b413-fa6853186b27)

#### Soluções:
- Registros duplicados foram removidos.
- Valores ausentes foram preenchidos com a mediana da variável.
- Valores outliers foram substituídos pela mediana da variável.

#### [Voltar ao Sumário](#parte-2-data-science)
## 11. Laboratório Prático 5 - Engenharia de Atributos com Linguagem M
Neste Laboratório foi demonstrado como a Linguagem M pode ser usada no Power BI para realizar uma das mais importantes tarefas em Ciência de Dados: a Engenharia de Atributos. Utilizando dados fictícios, foram aplicadas diversas tarefas e etapas como criação de novas variáveis, remoção de variáveis desnecessárias, transformações e correções.

### 11.1. Script em Linguagem M
```
let
    Fonte = Csv.Document(File.Contents("C:\Users\Lenovo\Documents\Cursos\Data Science Academy\Microsoft Power BI Para Business Intelligence e Data Science\Laboratorios\Lab_5\Clientes.csv"),[Delimiter=",", Columns=10, Encoding=65001, QuoteStyle=QuoteStyle.None]),
    #"Cabeçalhos Promovidos" = Table.PromoteHeaders(Fonte, [PromoteAllScalars=true]),
    #"Tipo Alterado" = Table.TransformColumnTypes(#"Cabeçalhos Promovidos",{{"ID_Cliente", type text}, {"Idade", type text}, {"Peso", Int64.Type}, {"Altura", Int64.Type}, {"Estado Civil", type text}, {"Estado", type text}, {"Limite de Credito", Int64.Type}, {"Valor Desconto", Int64.Type}, {"Valor Compra", Int64.Type}, {"Tipo de Cliente", type text}}),
    
    //Substituindo valor
    #"Valor Substituído" = Table.ReplaceValue(#"Tipo Alterado","?","45",Replacer.ReplaceText,{"Idade"}),

    //Ajustando o tipo da variável
    #"Tipo Alterado2" = Table.TransformColumnTypes(#"Valor Substituído",{{"Idade", Int64.Type}}),

    //Removendo coluna
    #"Colunas Removidas" = Table.RemoveColumns(#"Tipo Alterado2",{"Estado Civil"}),

    //Adicionando coluna
    #"Personalização Adicionada" = Table.AddColumn(#"Colunas Removidas", "Valor Final", each [Valor Compra] - [Valor Desconto]),

    //Dividindo coluna
    #"Dividir Coluna pelas Posições" = Table.SplitColumn(#"Personalização Adicionada", "ID_Cliente", Splitter.SplitTextByPositions({0, 4}), {"ID_Cliente.1", "ID_Cliente.2"}),
    #"Tipo Alterado1" = Table.TransformColumnTypes(#"Dividir Coluna pelas Posições",{{"ID_Cliente.1", type text}, {"ID_Cliente.2", Int64.Type}}),

    //Renomeando coluna
    #"Colunas Renomeadas" = Table.RenameColumns(#"Tipo Alterado1",{{"ID_Cliente.1", "Codigo"}, {"ID_Cliente.2", "ID"}}),

    //Coluna condicional
    #"Coluna Condicional Adicionada" = Table.AddColumn(#"Colunas Renomeadas", "% Desconto Especial", each if [Tipo de Cliente] = "Bronze" then 5 else if [Tipo de Cliente] = "Prata" then 10 else if [Tipo de Cliente] = "Ouro" then 15 else if [Tipo de Cliente] = "Diamante" then 20 else 0),
    
    //Ajustando a escala dos dados com transformação logarítmica
    #"Logaritmo de Base 10 Calculado" = Table.TransformColumns(#"Coluna Condicional Adicionada",{{"Limite de Credito", Number.Log10, type number}})
in
    #"Logaritmo de Base 10 Calculado"
```
#### [Voltar ao Sumário](#parte-2-data-science)
## 12. Laboratório Prático 6 - Integrando Banco de Dados com Power BI para Extração e Análise de Dados 
Neste laboratório foi demonstrado como conectar o Power BI a bancos de dados para extrair dados e criar análises, através de uma conexão ODBC (Open Database Connectivity). Utilizados dados fictícios e o banco de dados SQLite.

### 12.1. Exibição do Modelo
![Lab_6](https://github.com/Gui-lherme-Oliv/BI_DS_PowerBI/assets/123426025/ce237b76-c519-473e-ba7d-2c54515253ab)

#### [Voltar ao Sumário](#parte-2-data-science)
## 13. Laboratório Prático 7 - Machine Learning com Linguagem Python e Power BI dentro do Jupyter Notebook
Este laboratório prático apresentou o seguinte estudo de caso com dados fictícios: Imagine que uma empresa tenha dados históricos de clientes que fizeram compras de produtos ou serviços. Os dados incluem, para cada cliente: idade, renda anual e uma pontuação de gasto (poder de compra do cliente). A empresa gostaria de segmentar esses clientes em 3 grupos de acordo com similaridades a fim de personalizar as campanhas de Marketing. O gestor da área de Marketing espera receber um relatório com os 3 segmentos e para cada segmento a média de idade, renda anual e pontuação de gastos dos clientes. Seu trabalho é fazer isso acontecer utilizando Machine Learning.

Para escrever e executar o Python no navegador, foi utilizado o Google Colaboratory e foram empregadas as seguintes etapas:
1. Carregamento dos dados
2. Análise exploratória
3. Pré-processamento dos dados
4. Construção e treinamento do modelo de Machine Learning
5. Publicação do Relatório no Power BI Online
6. Edição do Relatório no Power BI Desktop
7. Publicação do Relatório editado no Power BI Online

### 13.1. Dashboard - Segmentação de Clientes
![Lab_7](https://github.com/Gui-lherme-Oliv/BI_DS_PowerBI/assets/123426025/9d7953bc-918f-4009-a7a9-2d0665861c0b)

#### [Voltar ao Sumário](#parte-2-data-science)
## 14. Laboratório Prático 8 - Detecção de Anomalias em Transações Financeiras com Linguagem R e Power BI
Este laboratório prático apresentou o seguinte estudo de caso com dados fictícios: Imagine que uma empresa da área financeira tenha dados históricos de clientes com duas transações financeiras (aqui chamadas de “transacao1” e “transacao2”). Os gestores acreditam que algumas dessas transações possam ser fraudulentas e gostariam de identificar as eventuais anomalias. Os gestores não fazem ideia do que seria uma anomalia e pediram sua ajuda para encontrar uma solução. De fato, eles não sabem se anomalias realmente ocorreram. Seu trabalho é usar Machine Learning para agrupar os dados de transações financeiras dos clientes e então detectar e definir as anomalias (se existirem). O resultado deve ser entregue no formato visual através de gráficos no Power BI.

Para este laboratório foi utilizado o RStudio e foram executadas as seguintes etapas:
1. Instalação e carregamento dos pacotes para detecção de anomalias, manipulação e visualização de dados
2. Carregamento dos dados
3. Criação e treinamento do modelo de Machine Learning
4. Previsões com o modelo usando os dados históricos
5. Definição das anomalias de acordo com o *anomaly score*
6. Aplicação do modelo de detecção de anomalias a novos dados
7. Análise das anomalias com boxplot em linguagem R
8. Análise das anomalias com boxplot no Power BI

Obs.: Algumas etapas intermediárias de preparação dos dados, como a análises exploratórias, limpezas e checagens, não foram realizadas pois os dados fictícios já foram previamente corrigidos e formatados.

### 14.1. Boxplot de Dados Anômalos e Dados Normais
![boxplot-Lab_8](https://github.com/Gui-lherme-Oliv/BI_DS_PowerBI/assets/123426025/2d966cfe-d4fc-418a-8310-90b4e6cec500)

### 14.2. Dashboard - Detecção de Anomalias em Transações Financeiras
![Lab_8](https://github.com/Gui-lherme-Oliv/BI_DS_PowerBI/assets/123426025/d9f73022-8bd9-4c2a-a5c9-0736b821439a)

#### [Voltar ao Sumário](#parte-2-data-science)
## 15. Laboratório Prático 9 - Engenharia de Producão com Power BI e IA: Prevendo a Produção Industrial ao Longo do Tempo
Neste laboratório o Power BI foi usado para manipular e compreender os dados, explorando alguns conceitos de análise de séries temporais utilizando dados fictícios. Por fim, foram apresentados recursos de IA do Power BI para prever a média de unidades produzidas ao longo do tempo e detecção de anomalias. O Dashboard criado ao final do laboratório serve como ponto de partida para o dia a dia de Engenheiros de Produção.

### 15.1 Dashboard - Produção Industrial ao Longo do Tempo
![Lab_9](https://github.com/Gui-lherme-Oliv/BI_DS_PowerBI/assets/123426025/bd808c9a-f0c5-4f92-800d-7c32913a3b09)

#### [Voltar ao Sumário](#parte-2-data-science)
</div>

