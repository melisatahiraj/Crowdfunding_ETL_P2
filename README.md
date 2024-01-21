# Crowdfunding_ETL_P2

![connections_1](https://github.com/melisatahiraj/no_sql_challenge_2/assets/147450801/c5c51698-d3c1-4e15-a907-14b4c9709ca1)

## Requirements


### Create Category DataFrame
###### - The DataFrame contains a "category_id" column that has entries going sequentially from "cat1" to "catn", where n is the number of unique categories
###### - The DataFrame has a "category" column that contains only the category titles
###### - The category DataFrame is exported as category.csv


### Create Subcategory DataFrame
###### - The DataFrame contains a "subcategory_id" column that has entries going sequentially from "subcat1" to "subcatn", where n is the number of unique subcategories
###### - The DataFrame contains a "subcategory" column that contains only the subcategory titles
###### - The subcategory DataFrame is exported as subcategory.csv


### Create Campaign DataFrame

###### - The DataFrame has the following columns: 
    - "cf_id" column
    - "contact_id" column
    - "company_name" column
    - "description" column
    - "goal" column that is a float data type
    - "pledged" column that is a float data type
    - "outcome" column
    - "backers_count" column
    - "country" column
    - "currency" column
    - "launch_date" with the time formatted as "YYYY-MM-DD"
    - "end_date" with the time formatted as "YYYY-MM-DD"
    - "category_id" column that contains the unique identification numbers matching those in the "category_id" column of the Category DataFrame
    - "subcategory_id" column that contains the unique identification numbers matching those in the "subcategory_id" column of the Subcategory DataFrame

###### - The campaign DataFrame is exported as campaign.csv


### Create Contacts DataFrame

###### - The DataFrame has the following columns: 
    - "contact_id" column
    - "first_name" column
    - "last_name" column
    - "email" column

###### - The contacts DataFrame is exported as contacts.csv


### Create Crowdfunding DataFrame
###### - A database schema labeled, crowdfunding_db_schema.sql is created
###### - A crowdfunding_db is created using the crowdfunding_db_schema.sql file
###### - The database has the appropriate primary and foreign keys and relationships
###### - Each CSV file is imported into the appropriate table without errors
###### - The data from each table is displayed using a SELECT * statement


## References
Data for this dataset was generated by edX Boot Camps LLC, and is intended for educational purposes only.
