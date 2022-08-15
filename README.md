  ## **`Purwadhika Capstone Project Data Analysis - Northwind (Products)`**

![logo](https://user-images.githubusercontent.com/94034809/161473874-c3687611-7e39-4b47-bcd8-fde68d98ee73.png)
## **Database Information**<br>
The Northwind database is a sample database that was originally created by Microsoft and used as the basis for their tutorials in a variety of database products for decades. The Northwind database contains the sales data for a fictitious company called “Northwind Traders,” which imports and exports specialty foods from around the world. The Northwind database is an excellent tutorial schema for a small-business ERP, with customers, orders, inventory, purchasing, suppliers, shipping, employees, and single-entry accounting.

**Source** : https://drive.google.com/drive/folders/1fTHrwh_gcLsOFKXHnUzUGEu_APxLoD9i

**Tables Information :**
- Suppliers : Suppliers and vendors of Northwind
- Customers : Customers who buy products from Northwind
- Employees : Employee details of Northwind traders
- Products : Product information
- Shippers : The details of the shippers who ship the products from the traders to the end-customers
- Orders and Order_Details : Sales Order transactions taking place between the customers & the company

**Northwind - Entity Relationship Diagram** :
![northwind_erd](https://user-images.githubusercontent.com/94034809/161475344-b6302245-1eb5-43d9-85dd-b50e0cb9c04d.png)

**`Northwind - Products`**<br>
This Projects, we only focus on products analysis but several columns from another tables will be use to help analyzing process.

**Retrieved Data Overview**
![2](https://user-images.githubusercontent.com/94034809/161476025-9f995dce-e5d6-43fa-a276-add864cbee40.png)


## **`Products Analyzing :`**
1. Find the most selling products, to maintain product stock available
1. Find most customer company, based on their orders for better handling in future orders
1. Find most supplier company, based on their orders for better handling in future orders
1. Find most customer country, to manage sales and best shipper company for shiping process 
1. Find most supplier country, to manage sales and best shipper company for shiping process
<br>

`Tableau Visualization :`<br>
![northwindTableau](https://user-images.githubusercontent.com/94034809/161478417-9e7991e6-5b0f-42e6-ad21-634c824af85e.png)

## **`Conclusion :`**
1. **Camembert Pierrot** is the most ordered products with total 1577.<br>
From ff all the existing products, there must be products that are popular. therefore based on the data above, we need to increase sufficient reserves according to the most popular products and we need to keep good communication well with suppliers, so that theirs product are always available.
1. **Beverages** is the dominated products category by total order quantity.
Beverages is a product category whose sales are very high. we need a special treatment to keep the other categories can meet customer needs.
1. Based on the visualization, There are some products that need attention. Because all these products are the most ordered, stock addition needs to be done immediately to keep products sufficient stock if there is an order.
1. **Richter Supermarkt** is the customer with the highest total order products
Richter Supermarkt is a very good customer in terms of ordering, we need to maintain a good relationship with this company. maybe we can give special discount for some products. We also need to do the same thing with some of the companies as listed above.
1. **Gai pturage** is the supplier company with the highest supply products
Gai pturage is a very good supplier in terms of supply, we need to maintain a good relationship with Gai pturage and so the other companies as listed above.
1. **Germany** the country with the most highest total order compared to the other countries.<br>
From data result, we need to maintain good relations with customers who are in different countries. therefore maybe we can assign a salesperson that who has the language skills according to the country they work in, in order to improve relations and good communication.
1. **United States** is the highest supplier of products, followed by United Kingdom at second place.<br>
From this data, we can improve shipping performance by selecting more shipper companies that we used to. It would be better if we communicate and cooperation with the sippher company to ensure that we have reserves in case of problems in terms of shipping method sea, air and land freight.

**Tableau :**<br>
https://public.tableau.com/views/ProjectModule2_16490125235130/NorthwindProducts?:language=en-US&:display_count=n&:origin=viz_share_link

With this Analyzing, i hope that audience understand what the data tells and to find the insight. and i feel sorry if theres some errors in data analyzing.<br>
## **`Thank You in Advance`**
<br>
<br>
James Nainggolan
