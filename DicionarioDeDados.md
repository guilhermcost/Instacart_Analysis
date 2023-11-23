# Dicionário de Dados

**Há cinco tabelas no conjunto de dados, e você vai precisar usar todas elas para pré-processar os dados e fazer a AED. Abaixo está um dicionário que lista as colunas de cada tabela e descreve os dados contidos nelas.**

**instacart_orders.csv:** cada linha corresponde a um pedido no aplicativo da Instacart
- 'order_id': é o número de identificação unívoco de cada pedido  
- 'user_id': é o número de identificação unívoco da conta de cada cliente
- 'order_number': é o número de vezes que o cliente fez um pedido
- 'order_dow': é o dia da semana em que o pedido foi feito (0 é domingo)
- 'order_hour_of_day': é a hora do dia em que o pedido foi feito
- 'days_since_prior_order': é o número de dias desde que o cliente fez seu pedido anterior
  
**products.csv:** cada linha corresponde a um produto unívoco que os clientes podem comprar
- 'product_id': é o número de identificação unívoco de cada produto
- 'product_name': é o nome do produto
- 'aisle_id': é o número de identificação unívoco de cada categoria de seção do supermercado
- 'department_id': é o número de identificação unívoco de cada categoria de departamento do supermercado
  
**order_products.csv:** cada linha corresponde a um item incluído em um pedido  
- 'order_id': é o número de identificação unívoco de cada pedido
- 'product_id': é o número de identificação unívoco de cada produto
- 'add_to_cart_order': é a ordem sequencial em que cada item foi colocado no carrinho
- 'reordered': 0 se o cliente nunca comprou o produto antes, 1 se já o comprou
  
**aisles.csv**
- 'aisle_id': é o número de identificação unívoco de cada categoria de seção do supermercado
- 'aisle': é o nome da seção
  
**departments.csv**
- 'department_id': é o número de identificação unívoco de cada categoria de departamento do supermercado
- 'department': é o nome do departame
