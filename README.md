# Inventory
Manage inventory Information

This project has been developed using PHP MVC framework Codeignitor, Jquery, Bootstrap and MySql

Contoller: inventory.php
Model: main_db.php
Views: spending_view.php, spending_view.php

To rum this project please load the files to their respective folder.
In main_db.php please change database credentials and also change table name.
Call upload() function to upload CSV file to database.
Call index() function to view total spending
spending_view.php: will show a Form with dropdown of Month-Year'. Under the form is a table with columns 'Month-Year','Category' ,'Pre Tax Amount' ,Tax Amount,Amount
Rows are grouped by category.
Change of Month-Year value in the dropdown will submit the form and show spending based on selected Month-Year grouped by category
Using Month-Year together because same month can exist in mutiple years
Used bootstrap to make the page responsive.
