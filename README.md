# PIWorks
Case
# User Management Screen
This document describes the user interface specification for the user management screen.

# Requirements
The user management screen should allow administrators to manage users in the system. 
The following features should be provided:

- View a list of all users in the system
- Add a new user
- Edit an existing user
- Delete a user
- 
The following information should be stored for each user:

- First name
- Last name
- Email address
- Password
- Role (administrator or regular user)
- 
# UI Components

The user management screen should consist of the following UI components:

- A table showing a list of all users in the system
- A form for adding or editing a user
- Buttons for deleting a user and submitting the form
- 
## Table

The table should have the following columns:

- User ID
- First name
- Last name
- Email address
- Role
- Edit button
- Delete button
- 
The user ID should be a unique identifier for each user in the system. 
The Edit button should allow the administrator to edit the user's information, and the Delete button should allow the administrator to delete the user from the system.

## Form

The form should have the following fields:

- First name (required)
- Last name (required)
- Email address (required, must be unique)
- Password (required)
- Role (required, with a dropdown menu to select either "Administrator" or "Regular User")
## Page Behavior
Initial Load
When the user management screen is initially loaded, the table should display a list of all users in the system. The table should be sorted by user ID in ascending order.

# Adding a User
To add a user, the administrator should click the "Add User" button. This will display the form for adding a user. The administrator should enter the required information into the form and click the "Submit" button. If the email address is already in use, an error message should be displayed, and the administrator should be prompted to enter a different email address. If all the required information is entered correctly, the new user should be added to the system, and the table should be updated to include the new user.

# Editing a User
To edit a user, the administrator should click the "Edit" button next to the user they wish to edit. This will display the form for editing a user. The administrator should update the user's information as needed and click the "Submit" button. If the email address is already in use by another user, an error message should be displayed, and the administrator should be prompted to enter a different email address. If all the required information is entered correctly, the user's information should be updated in the system, and the table should be updated to reflect the changes.

# Deleting a User
To delete a user, the administrator should click the "Delete" button next to the user they wish to delete. A confirmation dialog should be displayed, asking the administrator to confirm that they wish to delete the user. If the administrator confirms, the user should be deleted from the system, and the table should be updated to reflect the changes.
