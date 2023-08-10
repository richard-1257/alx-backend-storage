# MySQL advanced
This project contains tasks for learning advanced MySQL features.

## Tasks To Complete
+ [x] 0. **We are all unique!**<br/>[0-uniq_users.sql](0-uniq_users.sql) contains a SQL script that creates a table `users` following these requirements:
  + With these attributes:
    + `id,` integer, never null, auto increment and primary key.
    + `email,` string (255 characters), never null and unique.
    + `name,` string (255 characters).
  + If the table already exists, your script should not fail.
  + Your script can be executed on any database.
  + **Context:** Make an attribute unique directly in the table schema will enforced your business rules and avoid bugs in your application
