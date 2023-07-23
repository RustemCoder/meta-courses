# meta-courses


Object Relationship Mapping - ORM
What is ORM 
Usually, the type of system used in an Object-Oriented language such as Python contains types that are non-scalar and every time, they cannot be represented only in primitive types such as integers and strings. 

On the other hand, data types in tables of a relational database are of primary types, that is integer and string. 

Therefore, the program needs to convert objects in scalar data to interact with a backend database.

Object-oriented programming languages use Object Relation Mapping (ORM) to interact with Structured Query Language (SQL), both of which are incompatible.

The ORM layer maps a class to a table in a relational database, with its attributes matching the table's field structure. 

The ORM library lets you perform the database operations in an object-oriented way instead of executing raw SQL queries. 

This allows you to focus more on the programming logic than the backend database operations.

Object Relational Mapping or ORM is the ability to create a SQL query using object-oriented programming language such as Python. This enables a quick turnaround time in fast production environments that need constant updates. 

Each model is a Python class that subclasses django.db.models.Model

Each attribute of the model represents a database field. Essentially you can think of a model as a Python object, and models help developers create, read, update and delete objects, commonly called the CRUD operations.

Django has its own ORM layer. Its migration mechanism propagates the models in database tables. 

You need to construct a QuerySet via a Manager of your model class to retrieve objects from your database.
