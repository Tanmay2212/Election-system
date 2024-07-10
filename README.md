# Election-system
simple election system using PostgreSQL database to store parties and voters. Users can cast votes, and the system displays the current vote count and declares the winner at the end.
In this project, we learned and implemented:

Connecting to a PostgreSQL database using psycopg2
Creating tables and altering table structures using SQL queries
Inserting, updating, and retrieving data from the database
Defining and using Python functions to interact with the database
Using list comprehensions and conditional statements to process data
Implementing a simple voting system with vote counting and winner declaration
Key functions and methods used:

get_party_names(): Retrieves party names from the database
cast_vote(voter_name, party_name): Casts a vote for a party
get_vote_count(): Retrieves the current vote count for each party
more_voters(): Checks if there are more voters to cast their votes
