# SQL Koans
The SQL koans are a set of koans to introduce you to SQL. See [the website](http://sqlkoans.com) for more information. For the impatient...

## Climb the Mountain
```sh
$ git clone https://github.com/phillipjohnson/sql-koans
$ python ./src/path_to_enlightenment.py
```

## The Path to Enlightenment
- [`basics.sql`](./src/koans/basics.sql)
- [`filtering.sql`](./src/koans/filtering.sql)
- [`joins.sql`](./src/koans/joins.sql)
- [`relationships.sql`](./src/koans/relationships.sql)
- [`update_delete.sql`](./src/koans/update_delete.sql)
- [`subqueries.sql`](./src/koans/subqueries.sql)
- [`aggregates.sql`](./src/koans/aggregates.sql)
- [`presentation.sql`](./src/koans/presentation.sql)

## Takeaways

SQL Koans primary focus seemed to be exposing the learner to a variety of commands to become familiar with:
- how to `SELECT` a record (row)
- how to only return a record from a table `WHERE` a certain condition applies
- how to return records which pass a conditional filter across multiple tables (`JOIN`)

What was not covered at all, or in very little depth was:
- inserting records into a table (not at all)
- one-to-one relations
- altering a table (not at all)
- update and delete statements
- It was unclear what `DESC` was doing (sorting in descending order)

There is plenty more to learn about SQL, this was a nice place to start the process. It drops you into an environment with a set of tables already configured and only has you select, delete and update records throughout the koans. I would have prefered to be encouraged to use the common ALL CAPS syntax, I think there are valid reasons to learn common standards like why tokens are capitalized even though they are not required to be, instead I had to diverge from reading documentation on SQL and hop on over to Stack Overflow to see WHY EVERYBODY IS YELLING.