K jewelry shop database
------------------------

The database "Jewelry.accbd" is about a jewelry store and was created with MS Access. 

 
Normalization of the database:

1. Conceptual design:

![conceptual_design_db](https://github.com/user-attachments/assets/80d1c07d-74e9-4e37-828d-fc12f17207d0)

2. Logical design:

![Logical_deisgn_DB](https://github.com/user-attachments/assets/fcc6e8c4-e504-4b35-ae8f-60e713f2cb8c)

The prices in the table, Final price, are calculated as follows: 
1. Price without labor: (([Price for materials]+([Price for a single stone]*[Number of stones]))*1.2) 
2. The final price is: (([Price for materials]+([ ]+([Price for a single stone]*[ Number of stones]))*1.2)*1.2
3. Price for labor: ([Final price]-[Price without labor])
This gives 20% for labor and a 20% markup for each product.


Queries:
 
qryEmployees Master jeweler -> information for senior jewelers(name,last name, phone number and position held) 

qrySelect gemstones -> a window pop up in which we can enter the crystal we want, to show us all the information about all crystals with that name

qrySelect material -> a window pop up in which we can enter the material we want, to show us all the information about all materials with that base name


Forms:

 frmMain menu -> contains the company logo, as well as buttons to add:
 
 frmAdd gemstones -> made from the table "Gemstones"
 
 frmAdd materials -> made from the table "Materials"
 
 frmAdd employees -> made from the table "Empoyees"
 
 frmAdd products -> made from the table "Products"
 
 frmAdd order -> made from the table "Empoyees"


