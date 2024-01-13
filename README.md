

# ContactBook Application

The ContactBook application is a console-based program that allows users to manage their contacts. Users can perform various operations such as adding new contacts, editing existing ones, searching for contacts, deleting contacts, displaying all contacts, and deleting all contacts.

 Features

1. Add Contact:
   - Users can add a new contact by providing the name and phone number.
   - Contacts are stored in a linked list.

2. Edit Contact:
   - Users can edit existing contacts by searching for them either by name or phone number.
   - They can update the name and phone number of the selected contact.

3. Search Contact:
   - Users can search for a contact by providing either the name or phone number.
   - The application displays the contact information if found.

4. Delete Contact:
   - Users can delete a specific contact by searching for it either by name or phone number.
   - Confirmation is required before deletion.

5. Display All Contacts:
   - Users can view a sorted list of all contacts in alphabetical order by name.

6. Delete All Contacts:
   - Users can delete all contacts in the contact book.
   - Confirmation is required before deletion.

7. Offline Save:
   - Contacts are saved to a text file (`contactbook.txt`) for offline storage.
   - The application reads contacts from this file when started.


 Sample Usage

1. Adding a Contact:
   - Select option 1, provide the name and phone number, and the contact will be added.

2. Editing a Contact:
   - Select option 2, search for the contact by name or phone number, and provide updated information.

3. Searching for a Contact:
   - Select option 4, choose to search by name or phone number, and enter the relevant details.

4. Deleting a Contact:
   - Select option 3, search for the contact, and confirm the deletion.

5. Displaying All Contacts:
   - Select option 5 to view a sorted list of all contacts.

6. Deleting All Contacts:
   - Select option 6 and confirm to delete all contacts.

File Structure

- `contactbook.cpp`: Contains the main C++ code for the ContactBook application.
- `contactbook.txt`: Text file for offline storage of contacts.

Note

- The application utilizes a linked list to manage contacts.
- Contacts are sorted alphabetically by name using the Bubble Sort algorithm.
- The contact information is saved to a text file (`contactbook.txt`) for offline usage.

