# modelo_analise_metricas_RFV_desafio7
Utilize um modelo de Clustering para criar um sistema
de agrupamento de perfis de clientes para um e-commerce. Deverá
analisar o modelo mais eficiente, capaz de tornar as análises mais
simplificadas para a empresa.

Você foi contratado por uma empresa de e-commerce que está buscando entender
melhor o comportamento de seus clientes para personalizar as suas campanhas de
marketing. Para isso, a empresa disponibilizou uma base de dados em csv contendo
dados sobre clientes, produtos e transações da loja realizadas entre os anos de 2010 e
2011.

Com base nesses dados, você precisa agrupar os clientes em clusters com base em
seu comportamento de compra. Isso irá permitir identificar padrões e características em
comum entre os clientes, como:

Clientes que compram os mesmos produtos;

Clientes que possuem a mesma frequência de compras;

Clientes que gastam mais dinheiro em suas compras.

A partir desses clusters, gere insights para que a empresa possa segmentar melhor a
sua base de clientes e personalizar as suas campanhas de marketing, direcionando
promoções e ofertas aos clientes com base no comportamento de compras.

Os dados fornecidos possuem informações de transações de compras de uma loja de
e-commerce em 38 países e territórios, com mais de 4.000 clientes únicos e mais de
540.000 transações.

Atenção: as datas estão no formato MM/DD/YYYY HH:mm:ss; existem dados nulos que
precisam ser tratados antes da realização da análise; por mais que os códigos de
identificação sejam numéricos, o modelo não pode considerá-los como grandezas
numéricas.

Coluna | Descrição | Tipo
InvoiceNo | Identificação da transação | Int

StockCode | Código de estoque do produto | String

Description | Descrição do produto | String

Quantity | Quantidade de produtos por transação | Int

InvoiceDate | Data da transação | Datetime

UnitPrice | Preço unitário do produto | Float

CustomerID | Identificação do cliente | Int

Country | País de origem da transação | String

Analise os clusters obtidos para identificar o perfil de cliente, como padrões e
características em comum para determinar o seu comportamento de compra. Utilize
gráficos e visualizações para auxiliar na análise.
