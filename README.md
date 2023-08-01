# MySQL All for One

Feito por [Thiago Papim](https://www.linkedin.com/in/thiago-papim/)


## Sobre o Projeto 📝
 
 O "MySQL All for One" é um projeto incrível do meu portfólio, consistindo em 27 desafios de consultas SQL desenvolvidos para aprimorar minhas habilidades em manipulação de dados no banco de dados MySQL.<br><br>
 Através do "MySQL All for One", pude aprimorar minhas habilidades em consultas SQL, aprendendo a formular queries mais eficientes.<br><br>
 Meu primeiro e simples projeto em MySQL, uma emocionante jornada de aprendizado e descobertas!
 🚀

## Ferramentas e Habilidades utilizadas ⚙️
- MySQL
- JavaScript

 ## Como Executar o Projeto ✅
<details><summary><strong>Passo a passo</strong></summary><br/>


1. Clone o repositório
```
git clone git@github.com:thiago-papim/mysql-all-for-one.git
```
2. Copiar arquivo de configuração do DB<br>
```
Dentro do arquivo northwind.sql copiar todo o texto
```
3. Criar o DB com Workbench ou Beekeeper
```
Execute uma query com o texto do arquivo copiado
```

Com isso estará funcionando.

</details>

 ## Desafios 🔽
<details><summary><strong>Como executar os desafios</strong></summary><br/>

Na raiz do projeto existem 27 desafios, somente copiar o texto do desafio e executar no Workbench ou Beekeeper.

</details>

<details><summary><strong>Desafio 01</strong></summary>

`Exiba apenas os nomes dos produtos da tabela 'products'`
</details>

<details><summary><strong>Desafio 02</strong></summary>

`Exiba os dados de todas as colunas da tabela 'products'`
</details>
<details><summary><strong>Desafio 03</strong></summary>

`Escreva uma query que exiba os valores da coluna que contém a primary key da tabela 'products'`
</details>
<details><summary><strong>Desafio 04</strong></summary>

`Conte quantos registros existem na coluna 'product_name' da tabela 'products'`
</details>
<details><summary><strong>Desafio 05</strong></summary>

`Monte uma query que exiba os dados da tabela 'products' a partir do quarto registro até o décimo terceiro`
</details>
<details><summary><strong>Desafio 06</strong></summary>

`Exiba os dados das colunas 'product_name' e 'id' da tabela 'products' de maneira que os resultados estejam em ordem alfabética dos nomes`
</details>
<details><summary><strong>Desafio 07</strong></summary>

`Mostre apenas os ids dos 5 últimos registros da tabela 'products' ordenados por 'id'`
</details>
<details><summary><strong>Desafio 08</strong></summary>

`Faça uma consulta na tabela 'employees' que retorne o nome completo da pessoa colaboradora (colunas 'first_name' e 'last_name') com o nome 'full_name' e também a localização completa (colunas 'city', 'state_province' e 'address') com o nome 'location'.`
</details>
<details><summary><strong>Desafio 09</strong></summary>

`Mostre todos os valores da coluna 'notes' da tabela 'purchase_orders' que não são nulos`
</details>
<details><summary><strong>Desafio 10</strong></summary>

`Mostre todos os dados da tabela 'purchase_orders' em ordem decrescente ordenados por 'created_by' em que o 'created_by' é maior ou igual a 3`
</details>
<details><summary><strong>Desafio 11</strong></summary>

`Exiba os dados da coluna 'notes' da tabela 'purchase_orders' em que seu valor de 'Purchase generated based on Order' é maior ou igual a 30 e menor ou igual a 39`
</details>
<details><summary><strong>Desafio 12</strong></summary>

`Mostre os resultados da coluna 'submitted_date' da tabela 'purchase_orders' em que a 'submitted_date' é do dia 26 de abril de 2006`
</details>
<details><summary><strong>Desafio 13</strong></summary>

`Mostre o resultado da coluna 'supplier_id' da tabela 'purchase_orders' em que o 'supplier_id' seja 1 ou 3`
</details>
<details><summary><strong>Desafio 14</strong></summary>

`Mostre os resultados da coluna 'supplier_id' da tabela 'purchase_orders' em que o 'supplier_id' seja maior ou igual a 1 e menor ou igual 3`
</details>
<details><summary><strong>Desafio 15</strong></summary>

`Mostre somente as horas, sem os minutos e os segundos, da coluna 'submitted_date' de todos registros da tabela 'purchase_orders'`
</details>
<details><summary><strong>Desafio 16</strong></summary>

`Exiba os resultados da coluna 'submitted_date' da tabela 'purchase_orders' que estão entre '2006-01-26 00:00:00' e '2006-03-31 23:59:59'`
</details>
<details><summary><strong>Desafio 17</strong></summary>

`Mostre os registros das colunas 'id' e 'supplier_id' da tabela 'purchase_orders' em que os 'supplier_id' sejam tanto 1, ou 3, ou 5, ou 7`
</details>
<details><summary><strong>Desafio 18</strong></summary>

`Mostre todos os registros da tabela 'purchase_orders' que tem o valor na coluna 'supplier_id' igual a 3 e o valor na coluna 'status_id' igual a 2`
</details>
<details><summary><strong>Desafio 19</strong></summary>

`Mostre a quantidade de pedidos que foram feitos na tabela 'orders' pelo 'employee_id' igual a 5 ou 6, e que foram enviados através do método coluna 'shipper_id' igual a 2`
</details>
<details><summary><strong>Desafio 20</strong></summary>

`Adicione à tabela 'order_details' um registro com 'order_id': 69, 'product_id': 80, 'quantity': 15.0000, 'unit_price': 15.0000, 'discount': 0, 'status_id': 2, 'date_allocated': NULL, 'purchase_order_id': NULL e 'inventory_id': 129`
</details>
<details><summary><strong>Desafio 21 </strong></summary>

`Adicione com um único 'INSERT', duas linhas à tabela 'order_details' com os mesmos dados do requisito 20`
</details>
<details><summary><strong>Desafio 22</strong></summary>

`Atualize todos os dados da coluna 'discount', na tabela 'order_details', para 15.`
</details>
<details><summary><strong>Desafio 23</strong></summary>

`Atualize os dados da coluna 'discount' da tabela 'order_details' para 30, onde o valor na coluna 'unit_price' seja menor que 10.0000`
</details>
<details><summary><strong>Desafio 24</strong></summary>

`Atualize os dados da coluna 'discount' da tabela 'order_details' para 45, onde o valor na coluna 'unit_price' seja maior que 10.0000 e o id seja um número entre 30 e 40`
</details>
<details><summary><strong>Desafio 25</strong></summary>

`Delete todos os dados na coluna 'unit_price' da tabela 'order_details' em que o valor seja menor que 10.0000`
</details>
<details><summary><strong>Desafio 26</strong></summary>

`Delete todos os dados na coluna 'unit_price' da tabela 'order_details' em que o valor seja maior que 10.0000`
</details>
<details><summary><strong>Desafio 27</strong></summary>

`Delete todos os dados da tabela 'order_details'`
</details>

