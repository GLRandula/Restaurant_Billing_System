# Restaurant_Billing_System
C Language Assignment (GNU Utility)

This program is a simple console-based restaurant billing system written in C. It allows users to perform various operations related to generating and managing restaurant invoices.

Features:

    Generate Invoice: Users can generate a new invoice by providing customer details, items purchased, quantity, and unit price for each item. The program calculates        the total, discounts, and the grand total for the invoice.

    Show all Invoices: Users can view all previously generated invoices along with the customer details, items purchased, and total amounts.

    Search Invoice: Users can search for a specific invoice based on the customer's name and view the details of that invoice.

    Delete Invoice: Users can delete an invoice based on the customer's name. Deleted invoices are stored in a separate list for reference.

    Show Deleted Invoices: Users can view the details of previously deleted invoices.

Login Credentials:
The program requires users to log in with a username and password. The default login credentials are as follows:

    Username: admin
    Password: admin6@@!

Data Storage:
Invoices are stored in a file named "RestaurantBill.dat". When an invoice is deleted, it is moved to a temporary file, and then the original file is replaced with the temporary one.

Deleted Invoices Storage:
Deleted invoices are stored in an array named "deletedInvoices" with a maximum capacity of 100. The "numDeletedInvoices" variable keeps track of the number of deleted invoices.

Compilation:
To compile the program, use a C compiler (e.g., GCC) with the following command:

gcc -o restaurant_billing_system restaurant_billing_system.c

Execution:
After compiling, run the program using the following command:

bash

./restaurant_billing_system

Instructions:

    Upon running the program, you will be prompted to log in using the provided username and password.

    After successful login, the main menu will be displayed with various options.

    Choose an option (1-7) by entering the respective number and pressing Enter.

    Follow the on-screen instructions to perform the chosen operation.

    For "Generate Invoice" (Option 1), you will need to enter customer details, item names, quantities, and prices.

    For "Show all Invoices" (Option 2), all previously generated invoices will be displayed.
    
    For "No. of Invoices" (Option 3) Displays the amount of all previously saved invoices.

    For "Search Invoice" (Option 4), enter the customer's name to view their invoice details.

    For "Delete Invoice" (Option 5), enter the customer's name to delete their invoice.

    For "Show Deleted Invoices" (Option 6), deleted invoices will be displayed if any.

    To exit the program, choose "Exit" (Option 7).

Note:

    All generated and deleted invoices are stored in memory during program execution. If you terminate the program, the data will be lost.

    To retain data, consider implementing data storage using external files or a database.

    The program assumes a maximum of 50 items per invoice and can store up to 100 deleted invoices. You can modify these values in the code if needed.

License:
This program is distributed under the MIT License. Feel free to modify and use it according to your needs.

Author:
This program was created by G. Lakith Randula, and the last update was made on 7/31/2023.
