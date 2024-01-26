## main

...

    When you run models.Base.metadata.create_all(bind=engine), SQLAlchemy will examine your URL model, understand the structure of the table you want, and create that table in the database. 
    It's like telling SQLAlchemy to take the blueprint (Base and URL model) and build the actual structure in the database.


    Define the get_db() function, which will create and yield new database sessions with each request. Once the request is finished, you close the session with db.close(). You use the try … finally block to close the database connection in any case, even when an error occurs during the request.
...


