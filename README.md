# orm-ecomerce-backend



  [![npm](https://badge.fury.io/js/inquirer.svg)](http://badge.fury.io/js/inquirer)
  [![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
  
  ## Description
This repo houses the assets used to build the orm-ecomerce-backend this command-line application, this application was developed using Js and sequilize to conect to the database and express.js to build the API.


#### User story:

AS A manager at an internet retail company,I want a back end for my e-commerce website that uses the latest technologies
so that my company can compete with other e-commerce companies.


#### This App creates and perfoms changes into ecommerce_db.



## Table of Contents
- [Description](#description)
- [Installation](#installation)
- [Video](#video)
- [Credits](#credits)
- [Technology Used](#technology-used)
- [License](#license)

## Installation


In order of being able to run this application you'll need

### Step 1:

```sh
git clone https://github.com/enanesh/orm-orm-ecomerce-backend

git status 
```

### Step 2:

In the terminal run the command `npm init`

### Step 3:
To create the database you must be on /db the you'll have to run the command `mysql -u root -p` then is going to ask you for your password.Then when you are connected to the database run the command `source schema.sql;`, to exit this terminal you must press`\q`.

### Step 4:

To seed the database go to the path /seed and run the command `node index.js`.

### Step 5:

Finally to run the server go to the path /Develop and then run the commant `node server.js` in the terminal.








## Video






https://user-images.githubusercontent.com/111031708/210694608-c7eb5597-b6e0-4f30-8dc7-89ea3db5dc26.mp4













## Credits

Node.js : https://www.stanleyulili.com/node/node-modules-import-and-use-functions-from-another-file/
sequilize : https://sequelize.org/
express : https://expressjs.com/



## Technology Used
- JavaScript
- MySQL
-express node library
-Sequilize node library

## License

MIT
