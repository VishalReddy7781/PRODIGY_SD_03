# PRODIGY_SD_03

Develop a program that allows users to store and manage contact information. The program should provide options to add a new contact by entering their name, phone number, and email address. It should also allow users to view their contact list, edit existing contacts, and delete contacts if needed. The program should store the contacts in memory or in a file for persistent storage.

explanation:
Data Structures:

Contact struct: Holds the contact information (name, phone, and email).
contacts array: Stores all contacts.
contactCount variable: Tracks the number of contacts.
Functions:

addContact(): Adds a new contact.
viewContacts(): Displays the list of contacts.
editContact(): Edits an existing contact.
deleteContact(): Deletes a contact.
Main Loop:

Displays a menu and prompts the user for an action.
Calls the appropriate function based on the user's choice.
Loops until the user chooses to exit.
Notes:
For simplicity, the program uses scanf to read input. In a more robust application, you'd want to handle input more carefully to avoid issues with buffer overflows and other input-related bugs.
To store contacts in a file for persistent storage, you can extend the program with file handling functions using fopen, fwrite, fread, etc.
