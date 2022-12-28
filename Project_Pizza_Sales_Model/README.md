# DASHBOARD
![Screenshot (84)](https://user-images.githubusercontent.com/113659167/209840184-73bc0cd1-e1ca-4f0b-9dc2-9a3f9625b8a9.png)

About Dataset

This dataset contain 12 columns are as below:

<details><summary> order id </summary>
<p>
Unique identifier for each order placed by a table
</p>
</details>

<details><summary> order details id </summary>
<p>
Unique identifier for each pizza placed within each order (pizzas of the same type and size are kept in the same row, and the quantity increases)
</p>
</details>

<details><summary> pizza id </summary>
<p>
Unique key identifier that ties the pizza ordered to its details, like size and price
</p>
</details>

<details><summary> quantity </summary>
<p>
Quantity ordered for each pizza of the same type and size
</p>
</details>

<details><summary> order date </summary>
<p>
Date the order was placed (entered into the system prior to cooking & serving)
</p>
</details>

<details><summary> order time </summary>
<p>
Time the order was placed (entered into the system prior to cooking & serving)
</p>
</details>

<details><summary> unit price </summary>
<p>
Price of the pizza in USD
</p>
</details>

<details><summary> total price </summary>
<p>
unit_price * quantity
</p>
</details>

<details><summary> pizza size </summary>
<p>
Size of the pizza (Small, Medium, Large, X Large, or XX Large)
</p>
</details>

<details><summary> pizza type </summary>
<p>
Unique key identifier that ties the pizza ordered to its details, like size and price
</p>
</details>

<details><summary> pizza ingredients </summary>
<p>
ingredients used in the pizza as shown in the menu (they all include Mozzarella Cheese, even if not specified; and they all include Tomato Sauce, 
unless another sauce is specified)</p>
</details>

<details><summary> pizza name </summary>
<p>
Name of the pizza as shown in the menu</p>
</details>
