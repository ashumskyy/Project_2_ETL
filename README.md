# Project_2_ETL

### Part 1
In the first part of this Project on ETL (extract, transform, load) we extracted the data set from crowdfunding.xlsx excel file. We cleand the data set by assigning the category and subcategory values to category and subcategory columns, then we got the unique categories and subcategories in separate lists. After that we created a category DataFrame with the category_id array as the category_id and categories list as the category name, and a category DataFrame with the subcategory_id array as the subcategory_id and subcategories list as the subcategory. Finaly, we exported categories_df and subcategories_df as CSV files.

### Part 2
In the secont part we create a copy of the crowdfunding_info_df DataFrame named it campaign_df. We converted the goal and pledged columns to a `float` data type, converted Unix to datetime objects and merged the campaign_df with the category_df on the "category" column and the subcategory_df on the "subcategory" column. Then we droped unwanted columns and exported the DataFrame as a CSV file. 

### Part 3
In the tird part we extracted the Data from the contacts.xlsx excel file. We had to create a Contacts DataFrame that has the following columns: 
- A column named "contact_id" that contains the unique number of the contact person.
- A column named "first_name" that contains the first name of the contact person.
- A column named "last_name" that contains the first name of the contact person.
- A column named "email" that contains the email address of the contact person.
We did it by using Pandas as the Option 1 and by using REGEX as the Option 2. 
At the end of each option we exported the DataFrame as a CSV file. 

### Bonus
We also added the ERD document and schema file based on the tables we created.
