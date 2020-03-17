![Image description](https://i1.faceprep.in/ProGrad/face-logo-resized.png)

# ProGrad Lab | ProGrad Premier League

Like the Indian Premier League (IPL) which happens during April & May every year. Our team organizes ProGrad Premier League at the same time for all the Cricketers in our team. Our PPL schema is a complete repository of limited-over format of Cricket, that includes details like teams competing, player representing each team, scoring details, umpire details etc.

We are glad you had helped with building a database for the below schema. Now, could you help with quering a few queries from the database you have created?


## What Should You Do
```
Go to Oracle SQL Developer and connect to SYSTEM schema or hr schema.
Start writing your queries in the query builder.
Save the .sql file and upload it in github.
Practice Oracle SQL - DDL Statements.
```

## How To Submit
```
Upon completion, run the following commands:

git add .
git commit -m "ProGrad ID"
git push origin master

And finally, create a pull request so your ProGrad Mentor (PM) can review your work.
```

## Instructions

1. ***Do not erase the existing queries.***
2. ***Use the same file to write all your queries.***
3. ***Select the entire query and run it to see the output.***
4. ***Save the file as your_file_name.sql and upload it in github.***
5. ***Refer dml-select-2.sql file.*** 

## ER diagram

![sql](https://i1.faceprep.in/ProGrad/sql-ddl-lab2.png)

![sql](https://i1.faceprep.in/ProGrad/sql-ddl-lab1-instructions.png)


## PROGRESSION 1:


1. Write a query to display the name,coach,captain id of all the teams. Display the records sorted in descending order based on team name.
2. Write a query to display all the details regarding the Country. Display the records sorted in order based on country name.
3. Write a query to display the players details who do not belong to the country `South Africa` and `India`. Display the records sorted in ascending order based on player name.
4. Write a query to display the player names who haven't bagged the player of match award in the team `India`. Display the records sorted in ascending order based on player name.<br/>
>
>    `Hint`
>    `Step 1:First retrieve the player name who have bagged player of match in the team 'India')`
>    `Step 2:Then retrieve player name who haven't bagged player of match using 'not in(step 1)'`

5. Write a query to display the Umpire names who have not take part of any of the matches. Display the records sorted in ascending order based on umpire name.
6. Write a query to display the name of the winning team in the game played on `2020-01-05`. Display the records sorted in ascending order based on team name.
7. Write a query to display the Coach name of the team `Bangladesh`.
8. Write a query to display the Coach name of the team `Pakistan`.
9. Write a query to display the player of the match in the game played on `2020-02-11`. Display the records sorted in ascending order based on player name.
10. Write a query to display the name of all the players in the team `Ireland`. Display the records sorted in ascending order based on player name.
11. Write a query to display the Captain of the team `Afghanistan`.
12. Write a query to display the teams those which hasn't won any of the PPL matches. Display the records sorted in ascending order based on team name. `[HINT:select winner_team_id which is not null]`
13. Write a query to display the names of teams that has won matches in the month of January 2020. Display the records sorted in ascending order based on team name.
14. Write a query to display the name of the player who is an All Rounder and has won the player of the match award. Display the records sorted in ascending order based on player name.
15. Write a query to display the names of the team which have won the PPL tournament. Display the records sorted in ascending order based on team name.

Happy Coding ❤️
