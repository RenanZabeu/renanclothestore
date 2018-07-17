# Clothes Store - Stream 3

## Overview



### What does it do?

The store is to sell clothes online and also sign a monthly package of clothes. 
The users have to be signed the monthly package that cost $1 dollar or they can buy the clothes immediately with paypal.

### How does it work

 

    ### Some the tech used includes:
- [Python](https://www.python.org/)
    - [Flask] (flask.pocoo.org/)
    I use **Flask** micro – framework  used to serve our data from the server to our web based interface
- [Bootstrap](http://getbootstrap.com/)
    - We use **Bootstrap** to give our project a simple, responsive layout
- [MongoDB](https://www.mongodb.com)
    - We use **MongoDB** NoSQL Database used to convert and present our data in JSON format
- [D3.js](https://d3js.org/)
    - **D3.js** A JavaScript based visualization engine, which will render interactive charts and graphs based on the data
- [Dc.js](https://dc-js.github.io/dc.js)
    - **D3.js** A JavaScript based wrapper library for D3.js, which makes plotting the charts a lot easier
- [Crossfilter.js](https://dc-js.github.io/dc.js)
    - **Crossfilter.js** A JavaScript based data manipulation library that enables two way data binding.
   
    ## Contributing

### Getting the code up and running
1. Firstly you will need to clone this repository by running the ```git clone <project's Github URL>``` command
2. After you've that you'll update the data to MongoDB:
  3. Run mongoDB by running the command mongod in your Terminal/Command Prompt .
        Leave the prompt running as it is and open another Terminal/Command Prompt window.
        Copy the csv file to the same location as the directory opened in the second terminal window.
        Enter the following command:
        mongoimport -d cryptoBEL -c projects --type json --file cryptoBEL_projects.json
            
4. The project will now run on [localhost](http://127.0.0.1:5000/)
5. Make changes to the code and if you think it belongs in here then just submit a pull request