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








