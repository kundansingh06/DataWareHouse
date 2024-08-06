* A Foreign key is a column in one table which is the primary key on another table. 
* A foreign key and a Primary key are used to define the relationship between two tables in a relational database. 

For example in Employee and Department relationship, we have two tables: 

Department(dept_id, dept_name) and  
Employee (emp_id, emp_name, dept_id). 

dept_id is the primary key in the Department table and the foreign key in the Employee table.


![primaryVsForeignKey.png](primaryVsForeignKey.png)

* Name of foreign key can be different than the name of primary key it represent in other table. 
For example in our Employee and Department relationship, Primary key in Department table is dept_id  and 
we have used same name in Employee table to create foreign key. 
It could have been different e.g. departmentId or departmentID t etc.

* Table on which a column is declared as a primary key is known as parent table in the relationship and foreign key table is known as child table in a relationship. 
For example in Customer and ORDER relationship, Customer is parent table because cust_id is primary key there and ORDER is child table because cust_id is a foreign key in this table.


```
CREATE TABLE Customer (
cust_id INT NOT NULL, 
cust_name VARCHAR(256),                      
PRIMARY KEY (cust_id)
)

CREATE TABLE ORDER (
order_id INT NOT NULL,
amount INT NOT NULL,
cust_id INT,
FOREIGN KEY (cust_id) REFERENCES Customer(cust_id) ON DELETE CASCADE
) 
```