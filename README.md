# MuleSoft-PracticeExercises

1. Create a flow that accepts the HTTP path /flights and show the output as "Flight Info" as string in browser.

getting flight path using http connector

2. Update exercise 1 to get the json data from database using mule training MySQL database and data from table Americans.

3.Update exercise 2 to get the data for specific flight only. Change the database query to 

"SELECT * FROM American WHERE ID = :ID" and query input param to {'ID' : attributes.uriParams.ID}

The url http://localhost:8081/flights/3 should give the json of flight 3 only.

4.Create a POST request to url http://localhost:8081/flights that return payload as {"message": "Flight virtually added"}

5.Create a flow that accepts the HTTP path /users and show the json data from mysql database and data from table users.

hostname: 192.168.0.102

port:3306

username: dbuser3

passowrd: dbuser3

Default schema : practiceDB

Table : users

6.Update  exercise 5 for HTTP path /users/{name}  and show the json data from mysql database and data from table users for specific user name.
