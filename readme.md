# Habit Tracker App
This app is my first project that connects CMD App with SQL database file.
It helps to track any habits you wish to, choosing your habit name, unit name.
## Requirments:

`Basic` Requirments:

	- This is an application where you�ll log occurrences of a habit.
	- This habit can't be tracked by time (ex. hours of sleep), only by quantity (ex. number of water glasses a day)
	- Users need to be able to input the date of the occurrence of the habit
	- The application should store and retrieve data from a real database
	- When the application starts, it should create a sqlite database, if one isn�t present.
	- It should also create a table in the database, where the habit will be logged.
	- The users should be able to insert, delete, update and view their logged habit.
	- You should handle all possible errors so that the application never crashes.
	- You can only interact with the database using ADO.NET. You can�t use mappers such as Entity Framework or Dapper.
	- Your project needs to contain a Read Me file where you'll explain how your app works.

`Advanced` Requirments:

	1 If you haven't, try using parameterized queries to make your application more secure.
	2 Let the users create their own habits to track. That will require that you let them choose the unit of measurement.
	3 Seed Data into the database when the database gets created for the first time,  inserting a hundred records.
	4 Create a report functionality where the users can view specific information.

> [!NOTE]
> I changed a bit advanced requirments to challenge myself harder. :frog:


## Features:

![UI Menu Screenshot](/assets/UI.png)

+ Full SQLite Database connection
	- [x] Create, read, update, delete records
	- [x] Create, select, view habits
	- [x] Generate random records with user criterias:
		- Amount of records
		- Amount of units
		- Year of records from 2020 to 2024
+ Console Interface (Navigation with numbers)  
+ Validation for:
	+ Dates
	+ Names for habits[^1]
	+ Numbers
	+ Auto Counter of Records number and total  amount
	
![UI Menu Screenshot](/assets/AutoCounter.png)
	
[^1]Every habit is created in new table, so any symbols that might be wrong for SQL Table name are checked.

## Resources Used:

+ GitHub
+ Stack Overflow 
+ sqlite.org
+ [GitHub Emoji Cheat Sheet](github.com/ikatyang/emoji-cheat-sheet/tree/master)
+ ChatGPT (couple of minor issues)
