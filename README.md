1. Cats Dealer
==================

### Hi, there!
You are going to create a simple service that allows finding the best cat with the best price for customer location.

There are cat shops that have pricelists accessible via REST API. What your service will do is just get prices from each shop, compare them and suggest the best deal for a customer!

We created 2 fake test shops for you.
1. "Cats Unlimited" API (JSON response) - [https://nh7b1g9g23.execute-api.us-west-2.amazonaws.com/dev/cats/json](https://nh7b1g9g23.execute-api.us-west-2.amazonaws.com/dev/cats/json)
2. "Happy Cats" API (XML response) - [https://nh7b1g9g23.execute-api.us-west-2.amazonaws.com/dev/cats/xml](https://nh7b1g9g23.execute-api.us-west-2.amazonaws.com/dev/cats/xml)


### The task is the following:
1. The script must accept part of the product name (e.g. `curl`) as input.
2. At the output it returns the full name of the product, its price and the store name.
3. Implement "XML" and "JSON" integration, and improve business logic to find the best deal amongst two shops.


#### Things to watch out for:
* Right now our product supports only two cat shops. However, that can change in a future.
* As you know, 3rd-party integrations often behave unpredictably. Let's make sure that our product can handle errors from these services.
* In the response, some APIs can return really a lot of data. How would you solve this problem?

### Good luck and looking forward to seeing a finished project.

1. SQL
==================

You are given a table in postgres which is a list of employees with their salaries and departments. You need to write a query that will select the person with the maximum salary from each department (or several if the amounts are the same).

You can use dump of table employee.sql as a test data, sample schema:

```
postgres=# \d employee
            Table "public.employee"
   Column   |         Type          | Modifiers
------------+-----------------------+-----------
 id         | integer               | not null
 name       | character varying(30) |
 department | character varying(30) |
 salary     | integer               |
Indexes:
    "employee_pkey" PRIMARY KEY, btree (id)
```
