# Exercício Day 7 - DEX - DNC

Durante a pandemia os números de vendas da Razzle Dazzle (e-commerce de variedades) dispararam, bem como o da concorrência. Uma das maneiras de se destacar nesse mercado cada vez mais competitivo é oferecer o produto certo para a pessoa certa. Então, você foi contratado desenvolver pelo menos um modelo de recomendação, que será disponibilizado no novo site da empresa. Além do modelo, é necessário informar qual o melhor momento para usá-lo, em propagandas, quando o cliente estiver fazendo uma pesquisa ou quando o cliente estiver vendo um produto. É fundamental que isso seja pensado no desenvolvimento do modelo.

- **DNC_orders_dataset:**
- order_id – Id do pedido de compra;
- customer_id – Id do consumidor que realizou a compra;
- order_status – Status da compra;

- **DNC_order_items_dataset:**
- order_id - Id do pedido de compra;
- order_item_id – Número de produtos em uma mesma compra;
- product_id – Id do produto;
- price - preço;

- **DNC_products_dataset:**
- product_id – Id do produto;
- product_category_name – Categoria do produto;
- product_name_length – Tamanho do nome do produto;
- product_description_length – comprimento do produto;
	
- **DNC_products_dataset:**
- products_weight_g – peso do produto em g;
- products_lenght_cm – comprimento do produto em cm;
- products_height_cm – Altura do produto em cm;
- product_widht_cm – largura do produto em cm;

- **Milistones:**

- Definição do Modelo: Com a base de dados disponibilizada, quais modelos de recomendação podem ser feitos? 

- Exploração dos Dados: O que os dados nos dizem?  Quais são as hipóteses que podem ser levantadas disso? Será que os dados são suficientes para o modelo que se propôs a fazer?

- Estruturação dos Dados: Quais devem ser os dados de Treino? E os de Teste? Preciso juntar as informações entre as tabelas?

- Tratamento: Como pode ser feita a seleção e filtragem dos dados? Quais tratamentos devem ser feitos considerando os dados existentes?

- Criação do Modelo: Desenvolva o modelo!

- Teste do Modelo: Faça testes para validar se os modelos estão retornando valores esperados.	
