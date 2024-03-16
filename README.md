# Modelagem de dados

No desenvolvimento deste projeto, foram realizadas diversas etapas de limpeza e organização dos dados para preparar o dataset para modelagem de dados RFM (Recency, Frequency, Monetary). Inicialmente, foi feita uma análise exploratória dos dados para entender sua estrutura, identificar possíveis problemas e definir quais ações seriam necessárias para preparar o conjunto de dados.

As principais etapas realizadas no processo de limpeza e organização dos dados incluem:

1. **Remoção de Dados Duplicados**: Identificação e remoção de registros duplicados, garantindo a consistência e integridade do dataset.

2. **Tratamento de Dados Ausentes**: Avaliação e tratamento de valores ausentes em todas as colunas relevantes, utilizando técnicas como preenchimento por média, mediana ou moda, dependendo da natureza dos dados.

3. **Padronização de Dados**: Padronização de formatos de dados, como datas e códigos de estoque, para garantir consistência e facilitar análises futuras.

4. **Cálculo de Métricas RFM**: Para cada cliente, foram calculadas as métricas de Recency (tempo desde a última compra), Frequency (quantidade de compras) e Monetary (valor médio gasto por compra). Isso envolveu a manipulação das datas de faturamento e o cálculo do valor total gasto por cliente.

6. **Exportação do Dataset Final**: O resultado final foi exportado para um arquivo CSV contendo apenas as informações necessárias para a modelagem.

Em suma, a limpeza e organização de dados são etapas cruciais para qualquer projeto de ciência de dados, especialmente quando se trata de construir modelos preditivos ou analíticos. Com um dataset bem preparado e técnicas adequadas de análise, é possível extrair insights valiosos e tomar decisões estratégicas fundamentadas.

