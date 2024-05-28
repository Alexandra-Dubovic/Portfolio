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

**Inserati aici toate instructiunile de DELETE pe care le-ati scris folosind filtrarile necesare astfel incat sa stergeti doar datele de care aveti nevoie**

In order to simulate various scenarios that might happen in real life I created the following queries that would cover multiple potential real-life situations:

**Inserati aici toate instructiunile de SELECT pe care le-ati scris folosind filtrarile necesare astfel incat sa extrageti doar datele de care aveti nevoie**
**Incercati sa acoperiti urmatoarele:**<br>
**- where**<br>
**- AND**<br>
**- OR**<br>
**- NOT**<br>
**- like**<br>
**- inner join**<br>
**- left join**<br>
**- OPTIONAL: right join**<br>
**- OPTIONAL: cross join**<br>
**- functii agregate**<br>
**- group by**<br>
**- having**<br>
**- OPTIONAL DAR RECOMANDAT: Subqueries - nu au fost in scopul cursului. Puteti sa consultati tutorialul [asta](https://www.techonthenet.com/mysql/subqueries.php) si daca nu intelegeti ceva contactati fie trainerul, fie coordonatorul de grupa**<br>

</ol>

<li>Conclusions</li>

**Inserati aici o concluzie cu privire la ceea ce ati lucrat, gen lucrurile pe care le-ati invatat, lessons learned, un rezumat asupra a ceea ce ati facut si orice alta informatie care vi se pare relevanta pentru o concluzie finala asupra a ceea ce ati lucrat**

</ol>
