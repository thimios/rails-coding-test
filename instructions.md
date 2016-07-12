# Code

## Instructions

To showcase your Ruby on Rails skills, please perform this exercise and submit your  results. You should use Rails 4+ and any gems you find useful.

Please spend no more  than six consecutive hours.
The starting application is a scaffolded Rails application that satisfies the stories  below.

For evaluation, please submit an archive of your project results. Include a readme  file explaining your assumptions, providing any necessary assumptions, and stating  what you would accomplish with more time.

Submission evaluation will focus more  upon functionality and less upon styling design. Evaluation will include review of the submissions design, programming, and testing.

Thank you for committing this time and effort, we are looking forward to seeing  your results.


## Existing Application

We have a (very) basic e-commerce platform, with the four models (Product, Order, Item and ProductItem). You can find the relationships (if not figured already) in the models files and the database design in the schema file.



## Enhancements

Please implement the following  stories.

- ### Customers
All order belongs to a Customer.

- ### Categories
A product belongs to a Category.

- ### Multi-tenant app
Any customer browse to an account page and is prompted with a login page. They enter their credentials (login and password) and are presented with exactly their orders (sorted by status).

- ### Analytics
We need a weekly summary page displaying:
  - Breakdown by product of sold quantities (based on orders.created_at)
  - Breakdown by items of sold quantities (based on orders.created_at)
  - Add asynchronous navigation to change the displayed week
  - Display order uniq customer count by number of orders (see example 1)
  - (*On a separate view*) Display repartition between reccuring and new customers for each month (see example 2)

***Example 1***

|Orders|Customers|Percentage|
|--|--|--|
|1 order|70|70%|
|2 orders|20|20%|
|3 orders|5|5%|

***Example 2***

|Month|Reccuring Customer|New customer|Total
|--|--|--|
|June 2016|0|800|800
|July 2016|15|290|305


# Questions
*No coding necessary, explain the concept or sketch your thoughts.*

- We want to add a subscription feature to allow our customers to receive flower automaticaly. How would you design the tables, what are the pros and cons of your approach?

- When facing a high traffic and limited supply, how do you distribute the stock among clients checking out?
