# Interview Problem

 The following tasks assess ability to manage data files effectively.

 The data here represents the different houses a house buyer is considering. Each entry is a house,
 with a number of criteria for comparison such as cost, size, distance to work etc.
 Some of the criteria the buyer would want to minimise such as cost but others you want to maximise, such as area.

 The ideal outcome of this 'project' is to create a web-based front-end which allows the user to compare
 their choices, to help them make an informed decision.

 The data is stored in a JSON file, which is not very user friendly. The task is to reformat the data
 in order to help the house buyer to make the right decision.


## Tasks
1. Make a branch of master and push your commits to this branch. This branch will be deleted after the interview.
2. Using the language of your choice, read the `house_data.json` file, and print the top-level keys to __stderr__.
3. Having read the file, help readability by writing the data to a tabular file format such as CSV.
4. Design a database schema to store the data, and save the data in a database.
5. Create an API which will read the data from the database and return it.
6. Write a simple web front-end which accesses the API and displays the requested data.
7. How could we help the user make a decision by allowing them to visualise the trade-offs between the houses? Create a graph which will demonstrate this.

- Before you begin, read all the tasks so you can plan your approach
- You have __3 hours__ to get as far as you can into this task.
- Using comments note any assumptions made, improvements which could be made etc.
- In addition to the house details, there will need to be a way to represent the criteria for comparison (their relative importance and direction (min/max))
- While some tasks may seem simple, a strong emphasis will be placed on code reusability and readability.
