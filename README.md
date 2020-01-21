# Interview Problem

 The following tasks assess ability to manage data files effectively.

 The data here represents the different houses a house buyer is considering. Each entry is a house,
 with a number of criteria for comparison such as cost, size, distance to work etc.
 Some of the criteria the buyer would want to minimise such as cost but others you want to maximise, such as area.

 The data is stored in a JSON file, which is not very user friendly. The task is to reformat the data
 in order to help the house buyer to make the right decision.


## Tasks
1. Using the language of your choice, read the `house_data.json` file, and print the top-level keys to __stderr__.
2. Having read the file, help readability by writing the data to a tabular file format such as CSV.
3. Design a SQL schema to store the data, and save the data in a database. __HINT__: In addition to the house details, there will need to be a way to represent the criteria for comparison (their relative importance and direction (min/max))
4. Create an API which will read the data from the database and return it.
5. Write a simple web front-end which accesses the API and displays the requested data.
6. How could we help the user make a decision by allowing them to visualise the trade-offs between the houses? Create a graph which will demonstrate this.

 - You have __3 hours__ to get as far as you can into this task.
 - Using comments note any assumptions made, improvements which could be made etc.
 - While some tasks may seem simple, a strong emphasis will be placed on code reusability and readability.
