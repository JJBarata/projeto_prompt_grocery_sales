Contexto:

Este é um projeto onde um ChatGPT customizado poderá gerar insights e dados de vendas, à partir de um conjunto de datasets de um supermercado fictício, baixados do site [Kaggle](https://www.kaggle.com/datasets/andrexibiza/grocery-sales-dataset).
O arquivo original contém mais de 1 milhão de entradas e por motivos de falta de recursos computacionais, a amostra utilizada neste projeto utilizou o mesmo dataset com somente 5 mil entradas sem as entradas (1.555) com dados faltantes (~1% do total original).
O período utilizado foi de 01/01/2018 a 09/05/2018.

Datasets:

- Categorias (categories.csv)
- Cidades (cities.csv)
- Países (country.csv)
- Clientes (clients.csv)
- Funcionários (employees.csv)
- Produtos (products.csv)
- Vendas (sales.csv)

Pré-requisitos (antes de fazer as devidas perguntas):

- Verifique o formato de data do campo "SalesDate" do dataset "sales"
- Converta para o format yyyy-mm-dd

Perguntas (comandos):

- Calcule as vendas totais do mês de janeiro
- Calcule as vendas totais de cada mês
- Comparar o desempenho de vendas em diferentes categorias de produtos a cada mês
- Compare o desempenho através de gráficos
- Classifique os produtos com base na receita total de vendas
- Analisar a quantidade de vendas e a receita para identificar produtos de alta demanda
- Segmentar os clientes com base na frequência de compra e no gasto total
- Mapear os dados de vendas para cidades e países específicos para identificar regiões de alto desempenho
- Comparar volumes de vendas entre diversas áreas geográficas
- Compare agora por cidades

Regras:

- Sempre que citar alguma dependência do projeto, deixe-a com hiperlink para a página oficial daquela dependência
- Organize as dependências em uma sessão em formato de tabela
- Crie uma estrutura do projeto com base na árvore de pastas abaixo, e crie uma sessão para explicitar as técnicas utilizadas