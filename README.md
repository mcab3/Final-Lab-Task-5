# Final Lab Task 5. Views Stored Procedures and Functions
I gained hands-on experience with SQL views, stored procedures, and functions. I learned how to filter data, update vendor information, and display product details using SQL. These tasks helped me improve my understanding of data manipulation and the importance of writing efficient queries.

This is the following instructions that were given by our advisor: 
1. To have an idea of how SQL views work, kindly read the lecture on SQL views and stored procedures, then you may try the following examples in MySQL Workbench: 
2. Start Xampp and MySQL Workbench – create or start a connection 
4. Open the democodes.sql, and you may try executing all the examples using the hrd.sql file
5. AFTER the practice codes…. Perform the required SQL statements of the ff: use inventory.sql for this.
6. Print screen the appropriate sql and output per item  

   1. CREATE A VIEW that will display the vendors_code, vendors name, product description p_indate, of all products with p_indate from 2002 onwards

   2. CREATE a VIEW that will display all products whose price range is between 100-150

   3. Create a VIEW that will COMPUTE for the (TOTAL_PRICE) of ALL PRODUCTS by getting the (P_ONHAND x P_PRICE) Sold by vendors with the following v_code (21344, 23119 and 24288)


   4. CREATE a STORED PROCEDURE that WILL take a SINGLE PARAMETER and UPDATED the Name of Vendor ‘Bryson,Inc.’ to ‘Bryson and Co’.

   5. CREATE A Function that will take 2 parameters(v_code and v_state) and display All the product description and price based on the parameters passed to the function

## QUERY STATEMENTS:
 - **Step 1. CREATE A VIEW that will display the vendors_code, vendors name, product description p_indate, of all products with p_indate from 2002 onwards**  
<img src="Images/view1.png" width="500">
  
- **Step 2. CREATE a VIEW that will display all products whose price range is between 100-150**  
<img src="Images/view2.png" width="500">
  
- **Step 3. Create a VIEW that will COMPUTE for the (TOTAL_PRICE) of ALL PRODUCTS by getting the (P_ONHAND x P_PRICE) Sold by vendors with the following v_code (21344, 23119 and 24288)**
<img src="Images/view3.png" width="1000">
  
 - **Step 4. CREATE a STORED PROCEDURE that WILL take a SINGLE PARAMETER and UPDATED the Name of Vendor ‘Bryson,Inc.’ to ‘Bryson and Co’.**  
<img src="Images/1pm.png" width="500">
  
 - **Step 5. CREATE A Function that will take 2 parameters(v_code and v_state) and display All the product description and price based on the parameters passed to the function.**  
<img src="Images/2pm.png" width="500">

## TABLE STRUCTURES:
 - **Output of Step 1:**
  <img src="Images/view1_tbl.png" width="500">  
   
 - **Output of Step 2:**
  <img src="Images/view2_tbl.png" width="500">  
   
 - **Output of Step 3:**
  <img src="Images/view3_tbl.png" width="500">  
   
 - **Output of Step 4:**
  <img src="Images/1pm_tbl.png" width="500">  
   
 - **Output of Step 5:**
  <img src="Images/2pm_tbl.png" width="500">   
 
