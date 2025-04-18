# Análise de Lojas para Decisão de Venda

Este programa em Python realiza uma análise abrangente de quatro lojas, com o objetivo de auxiliar na decisão de qual delas possui o melhor potencial de venda e, portanto, seria a candidata ideal para uma possível venda. A análise considera diversos indicadores de desempenho, com visualizações gráficas para facilitar a interpretação.

## Funcionalidades

O programa analisa as seguintes métricas para cada uma das quatro lojas:

* **Faturamento Total:** O valor total das vendas geradas por cada loja. Apresentado visualmente através de um **gráfico de pizza** comparando a participação de cada loja no faturamento total.
* **Vendas por Categoria:** A distribuição das vendas entre diferentes categorias de produtos em cada loja. Exibido através de **gráficos de barras** separados para cada loja, mostrando o volume de vendas por categoria.
* **Média de Avaliação das Lojas:** A satisfação média dos clientes com cada loja, baseada em avaliações. Apresentado em formato textual para comparação direta.
* **Produtos Mais e Menos Vendidos por Loja:** Identificação dos três produtos com maior e menor volume de vendas em cada unidade. Exibido em formato de lista para cada loja.
* **Valor Médio de Frete em Cada Loja:** O custo médio de envio dos produtos para os clientes de cada loja. Apresentado em formato textual para comparação direta.
* **Desempenho Geográfico (Quantidade de Vendas):** A quantidade de vendas realizadas em diferentes regiões geográficas atendidas por cada loja. Visualizado através de um **gráfico geográfico** (mapa) indicando a intensidade de vendas por região para cada loja.

## Como Utilizar

1.  **Dados de Entrada:** O programa espera que os dados de cada loja sejam fornecidos em um formato específico (por exemplo, arquivos CSV, dicionários Python). Certifique-se de que os dados para cada uma das métricas mencionadas acima estejam disponíveis para as quatro lojas. A estrutura dos dados deve permitir a identificação da loja a qual cada dado pertence.

2.  **Bibliotecas Necessárias:** Certifique-se de ter as seguintes bibliotecas Python instaladas:
    * `matplotlib` para geração de gráficos de pizza e barras.
    * `` e `matplotlib` (ou `plotly`) para a geração do gráfico geográfico. 

    ```bash
    pip install matplotlib geopandas shapely
    # Ou para plotly: pip install plotly
    ```

3.  **Execução do Programa:** Execute o script Python. O programa processará os dados fornecidos e gerará as visualizações.

4.  **Análise dos Resultados:**
    * **Gráfico de Pizza (Faturamento):** Visualize a proporção do faturamento de cada loja em relação ao total. Lojas com maior fatia podem indicar maior potencial de receita.
    * **Gráficos de Barras (Vendas por Categoria):** Analise as categorias de produtos com melhor desempenho em cada loja. Isso pode indicar o foco de cada loja e o interesse do público.
    * **Média de Avaliação:** Compare as médias de avaliação para entender a satisfação dos clientes com cada loja. Lojas com avaliações mais altas podem ter uma base de clientes mais leal.
    * **Produtos Mais e Menos Vendidos:** Identifique os produtos de sucesso e os que precisam de atenção em cada loja. Isso pode influenciar decisões de estoque e marketing.
    * **Valor Médio de Frete:** Compare os custos de frete para entender a competitividade de cada loja em termos de entrega.
    * **Gráfico Geográfico (Desempenho Geográfico):** Observe as regiões com maior concentração de vendas para cada loja. Isso pode indicar o alcance geográfico e o potencial de expansão em diferentes áreas.

5.  **Tomada de Decisão:** Com base na análise das métricas e nas visualizações fornecidas, avalie qual loja apresenta o melhor conjunto de indicadores para justificar uma possível venda. Considere seus critérios de priorização (por exemplo, faturamento alto, boa avaliação, forte presença em regiões específicas).
