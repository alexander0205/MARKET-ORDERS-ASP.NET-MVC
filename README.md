# MARKET-ORDERS-C--MVC
Was a technical  test for a application in ASP.NET MVC implements goods practice 


Step 1:
Create a database in MS SQL Server with the following 4 tables and their relationships

1) Customers:
Id
First name
Surname
Address
Active (Boolean field)
Creation date

2) Products:
Id
First name
Quantity
Price

3) Teacher Order:
Id
Customer Id
Created Date
State (states can be created or dispatched)

4) Detail Order:
Id
IdOrden
Product Id
Quantity
Price

Feed the table, manually, of Products with 5 products and that of Customers with 3 customers.

Step 2:
Create a new ASP.NET MVC or ASP.NET CORE project preferably, or in ASP.NET Web Forms, using Visual Studio (in C #) that contains the following:
Using the Entity Framework, create a model (edmx) that contains the database created in step 1.
Create an Orders page, which allows you to select a customer and add any (n) quantity of products to the order.
In the list of products, I must show the remaining amount of the product.
When the order is saved, the products must be deducted from the quantity field, and if at the time of saving, the quantity is 0, I must issue an alert and prevent the creation of the order.



![alt text](https://raw.githubusercontent.com/alexander0205/MARKET-ORDERS-C--MVC/master/Capture.PNG)
![alt text](https://raw.githubusercontent.com/alexander0205/MARKET-ORDERS-C--MVC/master/3.PNG)
![alt text](https://raw.githubusercontent.com/alexander0205/MARKET-ORDERS-C--MVC/master/Capture2.PNG)
