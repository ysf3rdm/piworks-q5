# User Management Screen User Interface Specification

## Requirements

1. Users should be able to create new users, edit existing users, and disable users.
2. Users can manage user roles.
3. Users can filter and sort by name, email, and other columns.

## Components

### Adding new User

- There should be a button at the upper left corner for adding a new user. Clicking it opens a form with the following inputs:
  - Username (Text Input)
  - Display Name (Text Input)
  - Phone (Text Input)
  - Email (Text Input)
  - User Roles (selectable from a hardcoded list)
  - Enabled (checkbox input)
- There should be a button at the upper right corner to save the new user.

### User List

- Displayed as a table with columns: ID, Username, Email, Enabled, and actions (delete, edit, activate, deactivate).

### Editing Existing User

- When a user clicks the edit button, the form for adding a new user opens with pre-filled inputs. The username input should be disabled.
- Users can make changes and click the 'update user' button.

## Page Behavior

- When the page first loads, all users are listed regardless of activity status.
- Users can add a new user by clicking the "Add New User" button.
- Users can edit a user's information by clicking the "Edit" button.
- Users can deactivate a user by clicking the "Deactivate" button.

## Extra Notes

- User roles can be managed on a separate user roles management screen.
