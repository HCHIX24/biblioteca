# biblioteca

##17/09/2024

#in this project you'll implement a simple system to manage books library

#1. create a simple sqlite DB with 3 tables: with flask-sqlalchemy

#Books -> ID(PK), NAME, AUTHOR, YEAR PUBLISHED, TYPE(1/2/3) [type of ENUM]

#Customers -> ID(PK), NAME, CITY, AGE

#Loans -> CUSTOMER_ID, BOOK_ID, LOAN_DATE, RETURN_DATE

#2. The book type sets the maximum loan time for the book:

# -> 1 - up to 10 days
# -> 2- up to 5 days
# -> 3- up to 2 days
#3. Create the DAL: (DATA ACCESS LAYER)

# -> build a class for each entity 
# -> create a seperate module for each class
# -> build unit tests

##usage of GITHUB, ENUM, BOOTSTRAP, SQLALCHEMY, UNITEST, DELETION -> active/inactive customers, ability to search author, client, book_name.

##ReadME, seperation of books, atleast 3 components(bootstrap) carousel, cards, button..

#LOGGER, "about" in website including resume

##4. Build a client application to use the DAL. simple menu: 
# -> add a new customer
# -> add, loan, return a new book
# -> display all books, customers, loans. late loans
# -> search books by name, customer by name
# -> remove book, customer (active/inactive)

##using gunicorn to deal with HTTP requests "gunicorn --bind 0.0.0.0:8000 app:app"


