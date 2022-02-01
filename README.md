# TECHNICAL TEST Free2Move : ANALYZE E-COMMERCE DATA

You were recently hired by an E-commerce company. Your mission is to provide insights on sales.

There are four datasets :
* *Products*: a list of available products.
* *Items*: a list of items.
* *Orders*: a list of customer orders on the website.
* *Customers*: a list of customers.

Please provide any scripts you used (SQL, Python/R...), answers (jupyter notebook, markdown, text file, tableau workbook etc.) as well as the final SQLite database you obtained. You may also provide a description of any other tools you used, such as ETL tools.

**Construct an SQL Database**
1. Create and insert data in an SQLite database.
2. Create a customer vision that centralizes sales by customers and identify top customers.
3. How many customers are repeaters ?

**Sales:**
1. What is the average basket by product category?
2. What is the average number of items per basket? What are the most popular products?
3. What are repeat customers mostly buying ?
4. How do sales evolve over time ? Provide some vizualisations.

**Customer Segmentation**
Propose a simple customer segmentation. You may use any tool you find relevant.

*******************************************************************************

*******************************************************************************

# Steps to run the project


## 1) Have Python 3 - Version Used for the project: Python 3.7.5

## 2) Install libsqlite3-dev (Linux)

$ sudo apt-get install libsqlite3-dev

## 3) Create a new venv for this project

$ python3 -m venv venv_faycal_test

## 4) Activate venv_faycal_test

$ source venv_faycal_test/bin/activate

## 5) Install all dependencies 

$ pip3 install -r requirements.txt

## 6) Check dependencies installation

$ pip3 freeze

## 7) Add venv_faycal_test as Python Kernel

$ python3 -m ipykernel install --user --name venv_faycal_test --display-name "venv_faycal_test"

## 8) Run Jupyter Notebook

$ jupyter-notebook

## 9) A web browser should be open automaticly. If not, check your terminal, copy the url printed and past the url in your browser

ex: http://localhost:8888/?token=1c29e4f4891688fc5256a68be3d74088e3c329a7c59c88a1

## 10) Run main.ipynb using venv_faycal_test Kernel

## 11) Once finished, you can deactivate venv_faycal_test and also close the SQLite3 connexion

$ deactivate

Go at the end of main.ipynb, remove # in '#conn.close()' and run code cell 
