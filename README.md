# dbms-transactions-Iri25

Implement the following scenarios for your own database:

- Create a stored procedure that inserts data for entities that are in an m-n relationship.
If an insertion operation fails, the entire procedure must be rolled back stored.
- Create a stored procedure that inserts data for entities that are in an m-n relationship.
If an insert operation fails you will need to keep as much of it as possible what has changed so far. For example, if you try to insert a book and its authors, and the authors have been successfully inserted but a problem arises at book insertion, then roll back to book insertion but its authors to remains in the database. 
