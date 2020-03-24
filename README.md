
# Sakila DVD Rental

### A SQL and Visualization Project to investigate Sakila Movie Database of online DVD rentals.

### Overview
This project uses SQL queries to explore a database related to movie rentals.
This requires you to create four SQL queries and build visualizations to showcase the output of your queries.

The project includes:
* A set of four slides with a question of interest, visualization, and small summary on each slide.
* A text file with your queries needed to answer each of the four questions.

### Deliverables
These are the questions answered in the Project Submission file:

1. What were the total Rentals by Category.
2. What were the Rental durations by Category by Quartile.
3. How are the two stores compared by Monthly Rentals for all the years.
4. Which are the Top 10 highest Paying Customers with the highest payment differences.

### Files Submitted
* PROJECT_QUERIES.txt
* SQL Project Submission_PDF.pdf

### Software Recomendations
* You can either access the PostgreSQL working environment provided by Udacity or you can install PostgreSQL in your local computer following the installation instructions provided in this document.
* MS-Excel - used to create the visualizations.

### Instructions for Software and Database Installation
__Step 1. Downloading PostgreSQL__

 First, you will need to install PostgreSQL on your local machine. The instructions below provide detailed description of the steps you need to take.

 * Installing PostgreSQL for Windows:
[http://www.postgresqltutorial.com/install-postgresql/](http://www.postgresqltutorial.com/install-postgresql/)

* Installing PostgreSQL for Mac OS:
[https://www.postgresql.org/download/macosx/](https://www.postgresql.org/download/macosx/)

Friendly reminder! Please write down the database superuser (postgres) password as you will need it to create the Sakila database once you have installed the PostgreSQL server.

__Step 2. Downloading Sakila database__

Once PostgreSQL server is installed, you will need to download the Movie database from this page: [PostgreSQL Sample Database](https://www.postgresqltutorial.com/postgresql-sample-database/).

Scroll down and click on the orange "Download DVD Rental Sample Database" button.
This will download a zipped file, and you will need to extract the dvdrental.tar file.

__Step 3. Loading database__

The next step is to load the DVD Rental database into your PostgreSQL server on your machine.
We recommend using the PgAdmin tool.

You will find the instructions to do so on the following link: [Load PostgreSQL Sample Database](https://www.postgresqltutorial.com/load-postgresql-sample-database/).

The instructions are down ⅓ on this page under the header “Load the DVD Rental database using pgAdmin tool” .

Now follow the instructions all the way through the header titled "Verify the loaded sample database."

Once you have followed the instructions through the end of "Verify the loaded sample database.", you have now loaded the dvdrental sample database into your local PostgreSQL database server.

__Step 4. Connecting back to the PostgreSQL server__

Relaunch PgAdmin III and click on the PostgreSQL server within the Object browser. The screenshot below shows the red arrow pointing
to PostgreSQL server. Click it and enter your superuser (postgres) password.

__Step 5. Connecting to the DVD rental database__

Next click on the plus sign next to Databases to access the DVD rental database. The screenshot below shows the red arrow pointing to Databases.

__Step 6. Choose the DVD Rental database__

Choose the dvdrental database under Databases. The red arrow in the screenshot is pointing towards the dvdrental database.
You should now be linked to the DVD rental database.

__Step 7. Running Queries on your dvdrental database__

Click on the SQL icon with a magnifying glass.


### Credits
* Installation instructions about how to install PostgreSQL were obtained from Udacity.
* Mentor helped with one of the vizualizations. :octocat:
