<img width="100%" src="https://i.imgur.com/CYx9Es5.png" />

## Instructions

Solve each clue in the `questions.sql` file in your starter code repo.

Run the SQL file in the terminal as you solve each clue: `psql -f questions.sql`


## Setup
1. We need to create and seed the `ladder` database in our local postgresql.
   1. `psql -f ladder.sql`
2. Start `psql` and connect to the new database called `ladder`:
   1. `psql -d ladder` 
3. Check the information was created in the psql shell:
   1. `\d`

**You should see:**

| Schema | Name             | Type  | Owner         |
| ------ | ---------------- | ----- | ------------- |
| public | cities           | table | your-username |
| public | countries        | table | your-username |
| public | countrylanguages | table | your-username |

4. Exit the `psql` shell with: `\q`
5. Create your sequel queries in the `questions.sql` file.
6. Run your `questions.sql` file with: `psql -f questions.sql` or `\i queries.sql` in psql shell to see the results.
7. Exit the `psql` shell with: `\q` to add more code and run `psql -f questions.sql` again to check the data. Comment out the code as needed to more easily see the data in the terminal.