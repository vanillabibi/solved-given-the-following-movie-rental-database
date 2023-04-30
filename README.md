Download Link: https://assignmentchef.com/product/solved-given-the-following-movie-rental-database
<br>
<ol>

 <li>Given the following movie rental database:</li>

</ol>




<em>CUSTOMER (<u>customerID</u>, customer_name, street, city, zip)</em>

<em>RENTAL (<u>rentalID</u>, rental_date, return_date, due_date, <u>customerID</u>, <u>movieID</u>)</em>

<em>MOVIE (<u>movieID</u>, movie_title, movie_desc)</em>




Where the primary keys are underlined with a solid line and any foreign keys are underlined with a dashed line, give an expression in SQL for each of the following queries:




<ul>

 <li>Display the customer name for all customers that rented the movie ‘TOP_GUN’. (4 points)</li>

 <li>Display the customer name for all customers that rented the movie ‘TOP GUN’ and the return date was past the due date. (4 points)</li>

 <li>Display the customer name for all customers that rented the movie ‘TOP GUN’, that have passed the due date, and that have not returned the movie yet. (hint: SYSDATE and NULL should be used) (4 points)</li>

 <li>Display the movie title of all movies that have ‘ANIMAL’ somewhere in the title or in the movie description. (hint: use the LIKE keyword) (4 points)</li>

 <li>Display the number of customers that have outstanding rentals. (hint: use a SQL function to accomplish this) (4 points)</li>

</ul>




<strong>Part 1. </strong>

<ul>

 <li>Consider a database used in a doctor’s office. Construct an ERD that defines <u>ternary</u> relationship to record information about patients, doctors, and treatment. (5 points)</li>

 <li>Consider a business that needs to store data about its employees. The business rules for the relationship between employees and managers is listed below.  Construct the portion of the ERD that satisfies the rules. Note: Your diagram should only contain <u>one</u> (5 points)</li>

</ul>

<u>Business Rules:</u>

An EMPLOYEE can manage one or more EMPLOYEEs

An EMPLOYEE can be managed by one and only one EMPLOYEE

<strong>Part 2.  </strong>

Consider a real estate company that rents as well as sells properties.  Using the following list of entities, construct an ER diagram that satisfies the following business rules. If any many-to-many relationships exist, resolve them by creating bridge/composite entities. (10 points)

<u>Entity List:  </u>

CUSTOMER, PROPERTY

<u>Business Rules:</u>

A CUSTOMER can rent one or more PROPERTIES

A PROPERTY can be rented by one or more CUSTOMERs

A CUSTOMER can purchase one or more PROPERTIESA PROPERTY can be purchased by one or more CUSTOMERs


