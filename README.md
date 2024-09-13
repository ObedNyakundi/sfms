![SFMS logo](./images/logo_2.png)
# School Fees Management System (SFMS)

<iframe width="560" height="315" src="https://www.youtube.com/watch?v=LAHG9zAEwDM" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" allowfullscreen></iframe>

## Background
Among the most challenging tasks in managing academy schools in Kenya is the task of accounting. Especially in school fees collections and managing accounting for expenses. With the change of our academic system and growing changes in technology, there is need to develop systems that are friendly, easy to use, and adaptable for future technological changes. 

Our SFMS was built to solve this issue.

## System Outline

Our approach to solve this issue was through creating a finance account for all admitted students, and billing the students based on the fee structure that is given.

We also created a different pooling account for the entire school where all transactions that include debiting of account and all expenses can be accounted for. 

These two statements are the summary of our entire system.

# Hardware Requirements
Any computer setup able to run the software specifications below. 

# Software Requirements
- PHP v8.x^
- Laravel 11.x^
- Mysql - (or an alternative DBMS)
- NPM

# Database Structure.
![Database Schema](./images/database.png)
*The structure of the database is as shown above.*

# Gallery of the system overview
## Landing Page
![Landing Page](./images/landing.png)
*Current Landing Page Image*

## Dashboard page
![Dashboard Page](./images/dashboard_black_2.png)
*current dashboard page image*

## Table Sample
![Students Table](./images/table.png)
*a sample table view*

## Form sample
![Student Admission form](./images/form.png)
*a sample form view*

# How to Install
- Download the project files into a folder.
- Open terminal in the project folder. In some Linux distros, you might need to grant permissions to the project. Do so with:
 ` sudo chmod -R 755 ./`
- Install project dependencies using:
 `composer install`
- Install Node dependencies with:
 `npm install`
- Update the `.env` file.
- Generate the application key:
 `php artisan key:generate`
- Run the database server (optional for those using sqlite)
- Run laravel server 
 `php artisan serve`
- Make database migrations.
 `php artisan migrate`
- Seed the DB with the original values
 `php artisan db:seed`
- Run the jobs in the queue (optional)
 `php artisan queue:work`

 ENJOY!

 # Special Credits
 - [MCBAnks](https://github.com/MCBANKSKE)
 - [AceNyakundi](https://github.com/ObedNyakundi/)