# mySQL-inquirer-tracker
This code uses mySQL, sequelize, express, dotenv to create a backend for a ecommerce site.

Models: Category, Product, ProductTag, Tag  
Associations:  
```
    Product belongs to Category, as a category can have multiple products but a product can only belong to one category.

    Category has many Product models.

    Product belongs to many Tag models. Using the ProductTag through model, allow products to have multiple tags and tags to have many products.

    Tag belongs to many Product models.
```

## Installation
Download the code and run **npm install** 
Make your own env file with mysql credentials.
Enter the following after entering mysql:
**
source db/schema.sql;  
use ecommerce_db;  
**
Then you can exit out of mysql. 

## Usage
Run **npm seeds** to seed the database  
Run **npm start**


## Known Issues

