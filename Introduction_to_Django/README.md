Model Migration:
Prepare your model for database integration by running python manage.py makemigrations bookshelf to create migration files.
Apply migrations to update the database with python manage.py migrate.
Interact with the Model via Django Shell:
Open the Django shell with python manage.py shell and execute CRUD operations:
Create a Book instance.
Retrieve the book you created.
Update the title of the created book.
Delete the book instance.
Perform Specific CRUD Operations in the Django Shell: - Document each operation in separate Markdown files (create.md, retrieve.md, update.md, delete.md) detailing both the Python command used and its output.
Detailed CRUD Operations and Documentation:
Create:
Command: Create a Book instance with the title “1984”, author “George Orwell”, and publication year 1949.
Document in: create.md
Expected Documentation: Include the Python command and a comment with the expected output noting the successful creation.
Retrieve:
Command: Retrieve and display all attributes of the book you just created.
Document in: retrieve.md
Expected Documentation: Include the Python command and a comment with the expected output showing the details of the book.
Update:
Command: Update the title of “1984” to “Nineteen Eighty-Four” and save the changes.
Document in: update.md
Expected Documentation: Include the Python command and a comment with the expected output showing the updated title.
Delete:
Command: Delete the book you created and confirm the deletion by trying to retrieve all books again.
Document in: delete.md
Expected Documentation: Include the Python command and a comment with the expected output confirming the deletion.
Implementation and Submission Instructions:
Code Implementation: Your models.py file should correctly define the Book model as specified. Ensure that all field types and options are accurately implemented.
Database Operations: Perform and document each CRUD operation in the Django shell. Save your commands and their outputs in a file named CRUD_operations.md.
Repo:
GitHub repository: Alx_DjangoLearnLab
Directory: Introduction_to_Django
