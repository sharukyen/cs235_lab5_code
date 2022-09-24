# COMPSCI 235 Lab Report 5
### Stanley Wu
## Notes
1. ```./app/models/person.py``` file contains the Person model.

2. ```./app/adapters/repository.py``` contains the AbstractRepository

3. ```people_repo``` is a static object which simulates a database.


## Reflection

I have learnt how to render pages using flask and also how to create the WTForm class.


## Solutions

Question 1.
All templates in the app extend from `layout.html`. What is the syntax for
extending from a layout template?

- By using the {% extends %} tag 

Question 2.
What method should you call to generate a dynamic URL for
```localhost/people/40```?

- By using ```https://localhost:8080/localhost/people/40```

Question 3.
What the benefit of using the blueprint compare with using the default route
(app.route())?

- Blueprints can make the process easier as it simplifies larger applications. 
### Github Account

[Link](https://github.com/sharukyen) to my GitHub account.