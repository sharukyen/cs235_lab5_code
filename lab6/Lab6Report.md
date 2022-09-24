# COMPSCI 235 Lab Report 6
### Stanley Wu
## Notes
1. Retrieve all data
```SELECT * FROM Book;```

2. Retrieve certain data
```SELECT Title, Author, Date FROM Book;```

3. The following retrieves Author with the alias BookAuthor
```SELECT Title, Author AS BookAuthor, Date FROM Book;```


## Reflection

I have learnt how to create and visualize a SQLite database from DB Browser.
I have also practised executing SQL queries and running SQL queries in Python using the built-in sqlite packages.

## Solutions

Question 1.
Whatʼs the query for selecting  the 2nd page of articles with title contains “US” with each page limits to 
10 rows?

- ```SELECT * FROM articles WHERE title LIKE '%US%' AND id>10  LIMIT 10;```

Question 2.
Does search keyword case sensitive? If it doesnʼt, how can we only select 
“US” but not “us”?

- No its not, we can use ```SELECT *FROM articles WHERE id>10 AND  title like '%US%' COLLATE Latin1_General_CS_AS LIMIT 10 ;```

Question 3.
How can “mjackson” find all articles he has commented? Only returns 
article_id and article title. Note that he may comment multiple times on 
1 article, but we only want to return the same article in 1 row.

- ```SELECT * FROM comments LEFT JOIN users on user_id = comments.user_id WHERE users.user_name = 'mjackson';```

Question 4.
Give one example for each type of joins: inner, left, right and outer.

- `INNER JOIN` − Returns all records that have matching values in **both** tables.

- `LEFT JOIN` − Returns all records from the left table, and the matched records from the right table.

- `RIGHT JOIN` − Returns all records from the right table, and matched records from the left table.

- `FULL OUTER JOIN` − Returns all records when there is a match from either left or right table.


Question 5.1
We want a new table called “readinglists” (Note the naming convention for 
tables), so a user can add articles into a reading list. 
Just like Netflix, each user can only has one reading list.

▹ What fields would you include in the table?

- articles, id, title, user

Question 5.2

▹ Whatʼs the schema of the table?

- ```articles(Fk), user(PK)```


### Github Account

[Link](https://github.com/sharukyen) to my GitHub account.