# Bamazon
Julian Villalba
Week 12 mySQL and NODE HW assignment

So in this assignment we needed to create a system using Node and MySQL that tracked a stores inventory and allowed people to make purchases.

<img src="https://i.imgur.com/gMLH4f1.png" alt="" />
<img src="https://i.imgur.com/DyVUxkd.png" alt="" />
This was done by running in mySQL workbench the following:
CREATE DATABASE bamazon2
and then USE bamazon2;
(as seen below)
<img src="https://i.imgur.com/Vmdqcrs.png" alt ="" />

As you can see here using mySQL I created a DB called "bamazon2" and filled it with the data contained in the table. The columns I had include : product, department, price, and quantity. I created 2 tables one named "Products" and the other named "Departments"

I had trouble with the creation of the database only to realize that wasn't the issue at all. I was having mySQL errors in terminal and after some googling fixed it by running this in SQL "ER 'root'@'localhost' IDENTIFIED WITH mysql_native_password BY 'password'" and fixed it entirely.

Once running on my local host server, I went ahead and opened visual studio code and used javascript to code "BamazonCustomer.js" and "BamazonManager.js". I also typed into terminal:
"npm install" and downloaded the node modules.

I worked first on the BamazonCustomer file and it's ability to process and calculate the data from the mySQL database that would use prompts to select whatever item desired.
when finished I'd get this after typing "node BamazonCustomer" in terminal and would get this result<img src="https://i.imgur.com/aJ5TZ3h.png" alt="" />

I'd then select the item number and the quantity and it subtracts it from the mySQL database and returns a price total
<img src ="https://i.imgur.com/1pPRNdl.png" alt="" />
As you can see it works without any issue whatsoever.

After what took a LONG time of trial and error, I worked on the BamazonManager js file. The whole goal was to be able to add and edit the inventory used by the BamazonCustomer.js file.
<img src="https://i.imgur.com/0jbeJ57.png" alt="" />


As you can see everything is working as it should!


Youtube video showing everything works:
https://www.youtube.com/watch?v=fGUNz2ct_bA
