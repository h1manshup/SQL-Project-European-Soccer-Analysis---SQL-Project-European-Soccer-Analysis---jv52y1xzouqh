uploaded html , ipynb and pdf file for the same atttached for the reference.  






In this project, work on #European Soccer Database**. In this database,data of over 25000 matches, 10000 players, 11 European countries with their lead championships, seasons 2008 to 2016, team lineups with squad formation (X, Y coordinates), betting odds from up to 10 providers, detailed match events like fouls, possessions, corners, etc. 









# Europian-Soccer


functions used in the project - 
1. `SELECT` statement: Retrieve the names of all countries from the "Country" table.
2. `WHERE` statement: Retrieve the names of all leagues from the "League" table for the country with the name 'Spain'.
3. `JOIN` statement: Retrieve the match details (match_api_id, home_team_goal, away_team_goal) along with the names of the home team and away team for the matches played in the '2015/2016' season.
4. `GROUP BY` statement: Retrieve the total number of goals scored by each team in the "Match" table, grouped by the country and league they belong to.
5. `HAVING` statement: Retrieve the average number of goals scored per match for teams that have played at least 10 matches in the "Match" table.
6. `ORDER BY` statement: Retrieve the names of players and their heights from the "Player" table, sorted in descending order of height.
7. `LIMIT` statement: Retrieve the top 10 teams with the highest number of goals scored in a match from the "Team" table.
8. `DISTINCT` keyword: Retrieve the unique seasons from the "Match" table.
9. `NULL` value detection:  Retrieve the names of players from the "Player" table whose height is not recorded (NULL).
10. Subquery: Retrieve the names of players from the "Player" table who have a higher height than the overall average height of all players.
11. `BETWEEN` operator: Retrieve the matches from the "Match" table where the number of goals scored by the home team is between 3 and 5 (inclusive).
12. `LIKE` operator: Retrieve the names of teams from the "Team" table whose long name starts with 'FC'.
13. `COUNT()` function: Retrieve the number of matches played in each league from the "Match" table.
14. `MAX()` function: Retrieve the player name and the highest height from the "Player" table.
15. `MIN()` function:  Retrieve the player name and the lowest weight from the "Player" table.
16. `SUM()` function: Retrieve the total number of goals scored by each team in the "Match" table.
17. `AVG()` function: Retrieve the average weight of players in the "Player" table.
18. `IN` operator: Retrieve the names of teams from the "Team" table that have played matches in either '2012/2013' or '2013/2014' seasons.
19. `JOIN` with multiple tables: Retrieve all the matches played.
20. Complex Query to find the height distribution.



    SQL is a conceptual language for working with data stored in databases. In our case, SQLite is the specific implementation. Most SQL languges share all of the capabilities in this doc. The differences are usually in performance and advances analytical funcionalities (and pricing of course).
Eventually, we will use SQL lunguage to write queries that would pull data from the DB, manipulate it, sort it, and extract it.

The most important component of the DB  is its tables - that's where all the data stored. Usually the data would be devided to many tables, and not stored all in one place (so designing the data stracture properly is very important). Most of this script would han
