README - Relational Algebra and ER Diagram
Overview
This project is part of a workshop for Databases Foundations (Season 2024-III) at Universidad Distrital Francisco José de Caldas. It focuses on practicing relational algebra queries based on the design of an apartment management system database and creating an Entity-Relationship (ER) diagram to illustrate the relationships between entities in the database.

Key Objectives:
Relational Algebra Queries: Write relational algebra expressions to extract meaningful information from the provided database tables. For each query, a result table is generated to validate the solution.

Entity-Relationship Diagram: Create an ER diagram showing the relationships between the tables used in the queries. This step helps to visualize the structure and relationships of the entities in the system.

Files
relational_algebra_queries.pdf: This document contains the following relational algebra queries:
Queries based on apartment information (e.g., filtering apartments by area, rooms, and owners).
Queries based on owner data (e.g., filtering owners by age, number of children, and pets).
Queries based on reservation data (e.g., filtering reservations by date, apartment number, and common space).
ER_diagram.png: An entity-relationship diagram showing the structure of the database. The diagram includes the following entities:
Apartment: Represents the apartment details (number, block, area, owner, and rooms).
Owner: Represents the apartment owners (name, age, number of children, and pets).
Reservations: Represents reservation data (apartment number, owner, date, and common space).
Public Services: Represents public services available in the apartments (water, electricity, gas).
Relational Algebra Queries
The following types of queries were written using relational algebra:

Apartment Queries:

Select apartments with an area greater than 50.
Select apartments with more than 2 rooms but fewer than 4.
Filter apartments based on the area between 40 and 70.
List apartments owned by people with "Van Halen" in their name.
Show apartments with an area greater than 60 and all available public services.
Owner Queries:

Select owners older than 50 years.
List owners with 1 to 3 children.
Filter owners based on age and the number of children and pets.
Reservation Queries:

Show reservations for the date 2020-01-01.
Select reservations made after a specific date and with certain criteria (e.g., pool, apartment number).
Show all reservations by reservation ID and common space.
Entity-Relationship Diagram
The ER diagram provides a visual representation of how the entities are connected:

Owner has a one-to-many relationship with Apartment (a single owner can have multiple apartments).
Apartment has a one-to-many relationship with Reservations (an apartment can have multiple reservations).
Owner also has a one-to-many relationship with Reservations (a single owner can make multiple reservations).
Apartment and PublicServices have a many-to-many relationship (an apartment can have multiple services, and a service can be available to multiple apartments).
