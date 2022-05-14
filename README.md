# Dollar Exchange Rate

## Features
- User Login/User registration
- Record a transaction with your own buy and sell rate using a selector
- Display the rates (Buy and Sell USD/LBP)
- Instant calculator (USD to LBP (With updated rates) and vice versa)
- Graph that show the fluctuation of the rates depending on the inputs
- Exchange system between users to buy and sell dollars in LBP or in USD
- Statistics off all the database inputs (USD to LBP price and vice versa) : Median, standard deviation, Min/Max price.
- When signed in, users will be able to see all their past transactions


## Tech
Uses a number of open source projects to work properly:

- [ReactJS] - HTML enhanced for web apps!
- [Flask] - Our server
- [Mui] - The React component library you always wanted
- [React Google chart] - A chart library easy enough to use
- [JWT] - Makes the use of token very easy 
- [MySql] - For our infamous database
- [Python] - Backend (APIs)

----  open source with a [repository]
 on GitHub.

## Installation
[Flask]
[React]
[MySql]
[Python]

1- Install my Sql workbench and community server on your machine.

2- Create a schema .

3- Edit the db_config.py file to match your database.

4- Open the terminal in app.py and then run a python shell on the terminal outside of the virtual environment.

5- Run the following commands in order : from app import db
							      db.create_all()
							      exit()

6.a- You should be able to see in MySQLWorkbench the different tables and columns.

6.b- In MySQLWorkbench go to Server > Data import > import from self contained file + default target schema = exchange

7- Using the same terminal, install the virtual environment using : py -3 -m venv venv

8- Run your virtual environment using :  venv\Scripts\activate

9- In the Venv, install the requirements.txt file using pip install -r requirement.txt
	/!\ In case this does not work, troubleshoot it by installing all dependencies manually.

10- Still in the Venv, run flask using : Flask run. Your server should be running.

11- On another terminal, run the following command npm Start 

12- You should be able to use the website.



