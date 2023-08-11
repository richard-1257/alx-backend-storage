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
     
+ [x] 1. **In and not out**<br/>[1-country_users.sql](1-country_users.sql) contains a SQL script that creates a table `users` following these requirements:
  + With these attributes:
    + `id,` integer, never null, auto increment and primary key.
    + `email,` string (255 characters), never null and unique.
    + `name,` string (255 characters).
    + `country,` enumeration of countries: `US,` `CO` and `TN,` never null (default value will be the first element of the enumeration, which is `US`).
  + If the table already exists, your script should not fail.
  + Your script can be executed on any database.

+ [x] 2. **Best band ever!**<br/>[2-fans.sql](2-fans.sql) contains a SQL script that ranks country origins of bands, ordered by the number of (non-unique) fans.
  + Import this table dump: [metal_bands.sql](metal_bands.sql)
  + Column names must be: `origin` and `nb_fans.`
  + Your script can be executed on any database.
  + Context: Context: Calculating/computing something is always power intensive… better to distribute the load!
