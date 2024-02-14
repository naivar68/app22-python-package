This package can be used to convert Excel invoices to PDF invoices using parameters supplied by the user.

The user needs to import the file:
pip install invoice-creator

In their own python project the developer/user needs to create a directory called "invoices" in the root directory of the project. The package will automatically create a folder in the
same directory called "output" where the new pdfs will be stored. The Excel files from the database need to be sored in the "invoices" folder created.

When running the program you will need to supply the parameters, and then the execution will create pdf invoices from the Excel files.

