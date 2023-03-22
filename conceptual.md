### Conceptual Exercise

Answer the following questions below:

- What is PostgreSQL?

its a database management system

- What is the difference between SQL and PostgreSQL?

postgresql is object relational and sql is just relational

- In `psql`, how do you connect to a database?

\c database

- What is the difference between `HAVING` and `WHERE`?

WHERE is used to filter single rows based on something. HAVING filters a bunch of rows based on something.

- What is the difference between an `INNER` and `OUTER` join?

an inner join joins matching rows between tables. an outer join returns all rows from one table and matching rows from the others

- What is the difference between a `LEFT OUTER` and `RIGHT OUTER` join?

left outer returns all rows from the left table, and matching from the right. right outer returns all rows from the right table, and matching from the left

- What is an ORM? What do they do?

an ORM is used to map objects models to database models.

- What are some differences between making HTTP requests using AJAX 
  and from the server side using a library like `requests`?

 ajax is not able to make requests to a different domain than what the webpage originated on. ajax is vulnerable to people injecting malicious code to steal data or perform actions

- What is CSRF? What is the purpose of the CSRF token?

the CSRF token is used to verify information sent through a form

- What is the purpose of `form.hidden_tag()`?

to single out the CSRF token and hide it
