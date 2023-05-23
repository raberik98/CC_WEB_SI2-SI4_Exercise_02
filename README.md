# CC_WEB_SI2-SI4_Exercise_02
Task name: Company Budget and Employees handler 


You are hired to create a project where the finance department can handle employees and the company budget.
The starting files are already added as well as some starting data. Please not that for tasks that require you to validate who triggered the endpoint for now you can just pass the _id in the params.

1; Set up a backend server which will be able to handle our database. If you are already working with MongoDB and Mongoose create a new javascript file which will register all of the employees provided to you and than run it once.

2; During the task the CEO is protected, meaning that the user cannot access or request any data about him. Use a middleware to ensure that users cannot get access to his data.

3; Create an endpoint where we can get all the data from a specific employee, and create another endpoint where we can get all the employees. Please remember that the CEO's data must not be shown.

4; Make our application be able to register new employees, and to also fire employees. Please remember that the CEO cannot be fired.

5; Make our application be able to give a raise to an employee. (Increase the employee's salary to a given amount)

6; You only need to complete the following task if you are using MongoDB, otherwise you already have what you need. Create a new entity (a new Mongoose Model) which will be able to store two things: a number which will represent the company budget, and an array which will represent the transaction history. Each object in the transaction history must contain the date of the transaction, the amount, and the text containing what was it for.

7; Create a middleware which will write the current company budget to the console every time we are triggering one of our endpoints. If you are using MongoDB than it's fine if you also store the company budget in a variable and when you would change the budget for any reason in the database then change this variable too. You don't have to request it from the database every time you trigger one of your endpoints.

8; Create an endpoint that the CEO can trigger, and it will pay all the employees, this also includes that in the transaction history you need to register this transaction, the reason (the text field that shows what was the transaction for) should be: "Monthly salary". If anyone who is not the CEO attempts to trigger this endpoint then respond with an appropriate response and statuscode. You can validate by passing the _id as a params.

TO BE CONTINUED...
