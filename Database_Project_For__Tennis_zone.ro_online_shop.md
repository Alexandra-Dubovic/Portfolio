<h1>Database Project for Tennis-zone.ro online shop </h1>

The scope of this project is to use all the SQL knowledge gained throught the Software Testing course and apply them in practice.

Application under test: Tennis-zone.ro

Tools used: MySQL Workbench

Database description: The scope of created database is to gather information about available products and placed orders for online shop dedicated to tennis lovers. Database consist of 7 tables providing main informtaion about products in their quantity and quality aspect. 

<ol>
<li>Database Schema </li>
<br>

You can find below the database schema that was generated through Reverse Engineer and which contains all the tables and the relationships between them

![Database scheme](https://github.com/Alexandra-Dubovic/Portfolio/assets/155356578/7ce93dde-b61d-4c9a-8c7f-185b6d59cb17)


The tables are connected in the following way:

<ul>
  <li> Table Brands  is connected with tables: Rackets, Shoes, Orders, New_Arrivals through a one-to-many relationship which was implemented through Brands.Brand_ID as a primary key and Rackets.Brand_ID, Shoes.Brand_ID, Orders.Brand_ID and New_Arrivals.Brand_ID as a foreign key in each mentioned table</li>
  <li> Table Products  is connected with tables: Orders, Clothing, and New_Arrivals through a one-to-many relationship which was implemented through Products.Category_ID as a primary key and Orders.Product_type, Clothing.Product_ID and New_Arrivals.Product_category as a foreign key in each mentioned table</li>

</ul><br>

<li>Database Queries</li><br>

<ol type="a">
  <li>DDL (Data Definition Language)</li>

  The following instructions were written in the scope of CREATING the structure of the database (CREATE INSTRUCTIONS)

![Create queries](https://github.com/Alexandra-Dubovic/Portfolio/assets/155356578/badda059-be9e-42fe-b72c-b28f603da1c1)

  After the database and the tables have been created, a few ALTER instructions were written in order to update the structure of the database, as described below:
![Alter queries](https://github.com/Alexandra-Dubovic/Portfolio/assets/155356578/2dd577b1-4031-42a3-8528-c34a335b6973)

 
  <li>DML (Data Manipulation Language)</li>

  In order to be able to use the database I populated the tables with various data necessary in order to perform queries and manipulate the data. 
  In the testing process, this necessary data is identified in the Test Design phase and created in the Test Implementation phase. 

  Below you can find all the insert instructions that were created in the scope of this project:
  ![insert queries](https://github.com/Alexandra-Dubovic/Portfolio/assets/155356578/1c601db2-8d98-403a-9969-f1420ba185ae)

  After the insert, in order to prepare the data to be better suited for the testing process, I updated some data in the following way:

  ![Update queries](https://github.com/Alexandra-Dubovic/Portfolio/assets/155356578/8a79a3f7-6c63-497d-8dfe-96af7f4c5648)


  <li>DQL (Data Query Language)</li>

After the testing process, I deleted the data that was no longer relevant in order to preserve the database clean: 

![delete queries](https://github.com/Alexandra-Dubovic/Portfolio/assets/155356578/00d4037b-7c68-45c3-9b9b-baa5b326222c)

In order to simulate various scenarios that might happen in real life I created the following queries that would cover multiple potential real-life situations:

1. SELECT clause with filters:
   
**- where**<br>
**- AND**<br>
**- OR**<br>
**- NOT**<br>
**- like**<br>

![Select + and or not like](https://github.com/Alexandra-Dubovic/Portfolio/assets/155356578/23914ffe-3aa1-49ad-b826-7d46ddb77ce2)




2. SELECT clause with aggregate functions:

![SElect + aggregate](https://github.com/Alexandra-Dubovic/Portfolio/assets/155356578/7319151b-33a9-4ff0-b808-8104c19b3e5a)



3. SELECT clause with JOIN
   
**- INNER JOIN**<br>
**- LEFT JOIN**<br>
**- RIGHT JOIN**<br>

![Select + join](https://github.com/Alexandra-Dubovic/Portfolio/assets/155356578/3b1e5ef0-2d92-49e5-b93e-f82ca95e8bc4)

4. SELECT clause with:
   
**- GROUP BY**<br>
**- HAVING**<br>

![SElect+ group by+ having](https://github.com/Alexandra-Dubovic/Portfolio/assets/155356578/37899d86-e9f7-4d5e-b073-672f7dc61b77)

5. Subqueries

![Subqueries](https://github.com/Alexandra-Dubovic/Portfolio/assets/155356578/0854c272-ad01-4e15-bf20-d38c8b6d1a92)


</ol>

<li>Conclusions</li>

**Inserati aici o concluzie cu privire la ceea ce ati lucrat, gen lucrurile pe care le-ati invatat, lessons learned, un rezumat asupra a ceea ce ati facut si orice alta informatie care vi se pare relevanta pentru o concluzie finala asupra a ceea ce ati lucrat**

</ol>
