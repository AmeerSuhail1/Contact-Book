# Contact Book Application

This is a simple command-line Contact Book application written in Python. It allows users to manage their contacts effectively.

## Class: ContactBook

The `ContactBook` class is the core of this application. It has the following methods:

- `__init__(self)`: Initializes a new instance of the `ContactBook` class. It creates an empty dictionary `self.contacts` to store contacts.

- `add_contact(self, name, phone, email, address)`: Adds a new contact to the book. Each contact is a dictionary with keys: `'phone'`, `'email'`, and `'address'`.

- `view_contact_list(self)`: Prints all contacts in the book along with their phone numbers.

- `search_contact(self, query)`: Searches for a contact by name or phone number. Returns a list of matching contacts.

- `update_contact(self, name, phone=None, email=None, address=None)`: Updates a contact's information. If the contact does not exist, it prints "Contact '{name}' not found."

- `delete_contact(self, name)`: Deletes a contact from the book. If the contact does not exist, it prints "Contact '{name}' not found."

## Function: main

The `main` function provides a command-line interface for the Contact Book application. It displays a menu with the following options:

1. Add Contact
2. View Contact List
3. Search Contact
4. Update Contact
5. Delete Contact
6. Exit

Users can select an option by entering the corresponding number. The application runs in a loop until the user chooses to exit.

## Usage

To run the application, simply execute the Python script from the command line:

```bash
python contact_book.py
```

This will start the application and display the menu to the user. Users can then interact with the application by choosing options from the menu and following the prompts.
```
