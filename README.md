# Case-Study-Supply-Chain
![case_study](https://github.com/Kindkrishna/Case-Study-Supply-Chain/blob/main/supply_db.sql)

(https://github.com/Kindkrishna/Case-Study-_-Supply-Chain/blob/main/supply_db.sql)
Case Study Supply Chain
The tables present in the supply chain data set are as follows:
Orders: Order_Id is the primary key.

Ordered_items: Order_Item_Id is the primary key, and Customer_Id is the unique identifier for the customers who placed the order and acts as a foreign key to the customer_info table. Category_Id is the unique identifier of the category of the product and acts as a foreign key to the category table.

Product_info: Product_Id is the primary key.

customer_info: Id is the primary key.

category: Id is the primary key.

department: Id is the primary key.
# Problem No -1
## “Get the number of orders by the Type of Transaction excluding the orders shipped from Sangli and Srinagar. Also, exclude the SUSPECTED_FRAUD cases based on the Order Status, and sort the result in the descending order based on the number of orders.”
