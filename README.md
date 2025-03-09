# Inventory-management-system
its a python based project that uses tkinter modules for Graphical User Interface(GUI)
there are total 8 python scripts which are connected to each other. The eight python scripts are as follows:-

dashboard.py,
employee.py,
supplier.py,
product.py,
category.py,
sales.py,
create_db.py,
billing.py,
### 1. dashboard.py
This script is the dashboard of Inventory Management System containing buttons, images and labels and timing.
The screen shows the options for Employee, Supplier, Category, Products and Sales to perform CRUD operations.
This screen also updates timely as you perform operations on any of these Labels.
![image](https://github.com/user-attachments/assets/a4f190e7-b9a8-4c32-833a-c8cc60847d6b)


### 2. employee.py
This screen collects and shows the complete data regarding an employee.
Buttons are functionalised accordingly.
You can search an employee by its email, name or contact.

![image](https://github.com/user-attachments/assets/5054641b-c872-4966-a4a3-1ba031594913)

### 3. supplier.py
This screen collects and shows the complete data regarding suppliers.
Buttons are functionalised accordingly.
You can search a particular supplier details by invoice no.
![image](https://github.com/user-attachments/assets/2a384abf-ac4a-4e61-a69e-1cb016e5c4ee)


### 4. product.py
This screen collects and shows the complete data about the product.
It also ensures the availability of the product
Buttons are functionalised accordingly.
You can search a product by its category, supplier or name.
![image](https://github.com/user-attachments/assets/c8424435-cbd6-43bd-be3a-97aa183494e8)

### 5. category.py
This screen collects and shows the information about the category of the product. LIKE:- If Product name is IPhone then its category is Phone.
This screen contains 2 buttons namely add and delete. These buttons are functionalised accordingly.
![image](https://github.com/user-attachments/assets/b6ca47af-cad2-47e3-a551-1daf97bf79b7)


### 6. sales.py
This screen stores and shows the bills by an invoice no.
Buttons are functionalised accordingly.
![image](https://github.com/user-attachments/assets/c5bbc83b-8005-406b-9db7-277630a67794)


 7. creat_db.py
This is the database file for all the tables.
You have to run this file first before running the dashboard.py file otherwise it will throw an error.
### 8. billing.py
This screen contains all the billing part.
This screen contains information regarding the products, customers, the products they are buying, billing structure, price of product, discout on the products.
This screen also contains a calculator to calculate the total amount.
Buttons are functionalised accordingly.
![image](https://github.com/user-attachments/assets/268b0135-ac01-48a4-802c-dc09d29a654d)


# Detailed Steps:
Click on the create_db.py file first and run it.
Click on the dashboard.py file and run it
Click on the employee button to add employees.
Click on the supplier button to add suppliers.
Click on the products button to add products.
Now click on the billing.py file for billing.
Now click on the dashboard.py file and run it.
Click on the sales button to see your billing.
### Configuration
- Before running `dashboard.py`, make sure to run `create_db.py` file first and create a folder named `bill` and `images`.
- In `images` folder save your images regarding this project and in `bill` folder bills will automatically be saved.
