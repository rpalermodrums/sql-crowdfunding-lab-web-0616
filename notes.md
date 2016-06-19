SQL

- order of execution
  -
- group by and aggregates, and how to they relate?
  - vs order by

- what can be accessed by another table
  - when can i access attributes from another table?

1. domain modeling and joins
  - has many/belongs to
  - joins
   - foreign id -- a primary id from another table



Books, authors, and genres.
Books have one author.
Authors may have many books.
An author's genres are defined by the genre
of each book that he has written


Table Books

id | name | genre | author_id
1

Table Author
id | name | book_id

Table author_genres
id | book_id | author_id

a. consider belongs_to and has_many relationships
b. start with the belongs to relationships
  - in a belongs to relationship, the
    foreign id must be on the table
