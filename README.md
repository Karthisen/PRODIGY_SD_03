 PRODIGY_SD_03- CONTACT MANAGEMENT SYSTEM

Overview
This is a simple command-line Contact Manager built with Python. It allows users to:
- Add new contacts
- View all saved contacts
- Edit existing contacts
- Delete contacts
- Save contacts to a JSON file for future use
It’s a great project for learning file handling, list operations, and user input in Python.

How to Run the Program
- Make sure Python 3 is installed on your system.
- Save the code in a file named contact_manager.py.
- Open your terminal or command prompt.
- Run the program using:
python contact_manager.py



Files Used
- contact_manager.py: The main Python script containing all the logic.
- contacts.json: A file that stores your contact data in JSON format. It is automatically created if it doesn’t exist.

Sample Interaction
Contact Manager
1. Add Contact
2. View Contacts
3. Edit Contact
4. Delete Contact
5. Exit
Choose an option (1–5): 1
Enter name: Alice
Enter phone number: 1234567890
Enter email address: alice@example.com
Contact added successfully.

Code Highlights
- Uses the json module to read/write contact data.
- Checks if the contact file exists using os.path.exists.
- Handles invalid input with try-except.
- Stores contacts as a list of dictionaries.

 Notes
- Contacts are saved automatically when you exit the program.
- If contacts.json doesn’t exist, it will be created on first run.
- While editing, you can leave a field blank to keep the current value.


