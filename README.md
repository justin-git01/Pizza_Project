# Pizza Project

This pizza project and all data is fetched and inspired by the video [Data Analyst Portfolio Project - SQL](https://www.youtube.com/watch?v=0rB_memC-dA&list=LL&index=3&t=5s).

### Scenario

The client, Pizzeria - a no dine-in local pizza restaurant requests us to build a tailor-made bespoke relational datbase for his business that will allow him to capture and store all of the important information and data that the business generated. We are also required to build a business performance dashboards

#### Main areas to focus

* Orders

* Stock Control

* Staff


### Building relational database

The relational database will be built using MySQL and the help of a third-party tool called [QuickDBD](https://app.quickdatabasediagrams.com/#/).

#### Orders data required

* Row ID

* Order ID

* Item name

* Item category

* Item size

* Item price

* Quantity

* Customer first name

* Customer last name

* Delivery address 1

* Delivery address 2

* Delivery city

* Delivery zip code

#### Stock management requirements

* Wants to be able to know when it's time to order new stock

* Need information about:

  * what ingredients go into each pizza

  * their quantity based on the size of the pizza

  * the existing stock level 

#### Staff data requirements

* Wants to know which staff members are working when

* Based on the staff salary information, how much each pizza costs (ingredients + chefs + delivery)


### Writing SQL queries

#### Dashboard 1 - Order activity

For this, we will need a dashboard with the following data:

1. Total orders
2. Total sales
3. Total items
4. Average order value
5. Sales by category
6. Top selling items
7. Orders by hour
8. Sales by hour
9. Orders by delivery/pick up

#### Dashboard 2 - Inventory Management

For this dashboard, we need to calculate how much inventory we are using and then identify inventory that needs reordering.

We also want to calculate how much each pizza costs to make based on the cost of the ingredients and thus keep an eye on pricing and P/L.

We need:

1. Total quantity by ingredient
2. Total cost of ingredients
3. Calculated cost of pizza
4. Percentage stock remaining by ingredient
5. List of ingredients to re-order based on remaining inventory

#### Dashboard 3 - Staff dashboard

For this dashboard, we will need the exact start time and end time of each staff for every shift, their hourly rate and thus can calculate the total staff cost.


### Building Interactive Dashboards

Dashboards for this project will be built using Tableau instead of Looker Studio as guided in the video, and thus there will be some differences. 

**NOTE**: I have included Tableau files for dashboards, but it may be not accessible because I have linked the dashboards with local data source from MySQL. Therefore, I have included *pptx* file of all dashboards.

