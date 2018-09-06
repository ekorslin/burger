# Eat-Da-Burger App

Using MySQL, Node, Express, Handlebars, and a homemade ORM, I've built the perfect app for burger enthusiasts and foodies everywhere.  Eat-Da-Burger serves as a bucket list, of sorts, for its users to more easily remember the names of those mouth-watering burgers that have crossed their minds in the recent past during moments of weakness & hunger.  Additionally, the app even features an option to check off those burgers the user has had a chance to devour, reminding them of those they've yet to try.  

Users are encouraged to try out the app by clicking [here](https://thawing-beach-52915.herokuapp.com/).

## Cloning the app for local use:

If a user wishes to clone the app locally, it is recommended that the user install the following npm packages from terminal to their local folder after cloning the repository to their machine:
1.  npm init
2.  npm install express
3.  npm install mysql
4.  npm install express-handlebars
5.  npm install orm

### Setting up your MySQL database from terminal:
1.  Start MySQL command line tool and login: `mysql -u root -p`.
2.  With the `mysql>` command line tool running, enter the command `source schema.sql`. This will run your schema file and all of the queries in it -- in other words, you'll be creating your database.
3.  Now insert the entries you defined in `seeds.sql` by running the file: `source seeds.sql`.
4.  Close out of the MySQL command line tool: `exit`.

#### Also remember!
1.  Navigate to the connection.js file within the 'config' folder.  
2.  Make sure you have the correct password loaded for the MySQL connection -- in quotes!

It should also be noted that server port 8080 is reserved for running this app locally in the browser.  


