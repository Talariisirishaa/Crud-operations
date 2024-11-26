# Crud-operations

This is a simple web-based CRUD(Create,Read,Update,Delete) application that manages user data such as name, Password,email,  and date of birth.
The application uses HTML, CSS , JavaScript and LocalStorage to store and display user data without requiring a backend server.


# Features :
Add Users: Allows users to enter their name, password, email, and date of birth and save the data.
View Users: Displays a table of all saved users with their information.
Edit Users: Lets users edit previously entered data.
Delete Users: Provides an option to delete any user's data.
LocalStorage Integration: Data is stored in the browser's LocalStorage, ensuring it persists even after refreshing the page.

# Technologies Used :
HTML: For the structure of the webpage.
CSS: For styling the application.
JavaScript: For form validation, LocalStorage interaction, and dynamic table updates.
LocalStorage: To store and retrieve user data.

# How to Use:
->Clone or download the repository to your local machine.
->Open the Home.html file in your browser.
# Use the form to:
->Add Users: Fill in the name, password, email, and date of birth in the form and click the "Create Account" button.
->Edit Users: Click the "Edit" button next to a user's entry in the table. Modify the data in the form and re-add the user.
->Delete Users: Click the "Delete" button to remove a user's entry from the table and LocalStorage.

# Input Validation Rules :
Name: Required (cannot be empty).
Password: Cannot be less than 8 characters
Email: Must be in a valid email format (e.g., example@domain.com).
Date of Birth (DOB): Must follow the format dd-mm-yyyy (e.g., 03-08-2003).

If any validation fails, an alert message is shown to guide the user.
