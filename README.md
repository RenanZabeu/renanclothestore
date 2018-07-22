# Clothes Store - Stream 3

## Overview



### What does it do?

The store is to sell clothes online and also sign a monthly package of clothes. 
The users have to be signed the monthly package that cost $1 dollar or they can buy the clothes immediately with paypal.

### How does it work

 

    ### Some the tech used includes:
- [Python](https://www.python.org/)
    - [Django] (https://www.djangoproject.com/)
    I used **Django** – framework  used to serve our data from the server to our web based interface
- [Bootstrap](http://getbootstrap.com/)
    - I use **Bootstrap** to give our project a simple, responsive layout
- [DB.sqlite3](https://sqlitebrowser.org/)
    - I use **DB.sqlite3** DB Browser for SQLite is a high quality, visual, open source tool to create, design, and edit database files compatible with SQLite.
- [Stripe](https://stripe.com/ie)
    - **Stripe** used for the website to take subscription payments.
- [Paypal](https://developer.paypal.com/)
    - **Paypal** I used for the users buy at anytime the products using this single payment system.

   
    ## Contributing

### Getting the code up and running
1. Firstly you will need to clone this repository by running the ```git clone <project's Github URL>``` command
2. Install the requirements: pip install -r requirements.txt
	Setup the local configurations:
	cp .env.example .env
	Create the database:
	python manage.py migrate
	Finally, run the development server:
	python manage.py runserver
	The project will be available at 127.0.0.1:8000.