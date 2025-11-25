-- DATABASE: SQL Basic Query Workstation
-- QUESTION: Combine Two Tables
-- LANGUAGE: PostgreSQL

-- by looking at the output table decide the columns needed in presented order
select Person.firstName, Person.lastName, Address.city, Address.state
-- columns are not from one specific table 
-- so we need to select the columns from the first presented table in the output
from Person 
-- and join on the next table
left join Address -- NOTE: left join is used so null values are displayed
-- through the common primary key
on Person.personID=Address.personID;
