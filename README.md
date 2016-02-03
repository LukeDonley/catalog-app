Catalog App
===========

An app for creating a list of categories with items and descriptions.


To Run:
-------

Navigate to ./catalog/ enter the following at the prompt:

>python database_setup.py
>python project.py

This will set up the database and start the web server. To view the app navigate to:

>localhost:5000/


Add/Edit Categories/Items:
--------------------------

Adding and editing requires a user to be logged in. Click the login button from the upper right corner and log in using google or facebook.

All adding and editing functions are accessed using the navigation bar menu. 

Any logged in user can create a category or item. A user must be the creator of a cetegory or item in order to edit or delete it. Deleting a category will also delete all items contained within that category.