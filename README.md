# School Portal — User Manual

## About the Application

School Portal is a simple website created using HTML and CSS.
It includes a Registration page, a Login page, and a Dashboard
that displays sample student records.

This project demonstrates HTML forms, consistent CSS styling,
and navigation between web pages.

## Project Files

| File           | Description                                             |
| -------------- | ------------------------------------------------------- |
| register.html  | Registration form for entering sample user information. |
| login.html     | Login form for accessing the Dashboard.                 |
| dashboard.html | Displays sample student records.                        |
| style.css      | Provides the styling for all pages.                     |
| README.md      | Contains instructions for using the application.        |

## Getting Started

1. Download or clone this GitHub repository.
2. If downloaded as a ZIP file, extract it.
3. Keep all project files in the same folder.
4. Open login.html in a web browser.

No additional installation, server, or database is required.

## How to Use the Application

### 1. Open the Registration Page

1. On the Login page, click Register here.
2. The Registration page will appear.
3. Enter sample information in the following fields:
   - Full Name
   - Username
   - Email
   - Password
   - Confirm Password
4. Click Register.
5. You will be redirected to the Login page.

If you want to return directly to the Login page, click Login here
beside "Already have an account?"

Note: This is a registration demonstration. Information is not saved.
The Register control uses an anchor tag, so clicking it navigates
to the Login page without checking the fields or matching passwords.

### 2. Log In

1. Enter a sample username in the Username field.
2. Enter a sample password in the Password field.
3. Click Login.
4. The Dashboard page will appear.

Both fields must contain a value. Since this application has no
backend, any nonempty username and password will work.

### 3. View Student Records

The Dashboard displays a welcome message and a table containing
three sample student records.

| Column | Description                         |
| ------ | ----------------------------------- |
| ID     | Student identification number.      |
| Name   | Student's full name.                |
| Email  | Student's sample email address.     |
| Course | Student's course or degree program. |

The records are for display only. Adding, editing, and deleting
records are not available.

On smaller screens, scroll horizontally within the table to
view any columns that do not fit.

### 4. Log Out

1. Click Logout in the Dashboard header.
2. You will be redirected to the Login page.

## Troubleshooting

| Problem                               | Solution                                                     |
| ------------------------------------- | ------------------------------------------------------------ |
| The page has no styling.              | Make sure style.css is in the same folder as the HTML files. |
| A page cannot be found.               | Check that the filenames match the links exactly.            |
| Login does not continue.              | Fill in both Username and Password.                          |
| Register continues with empty fields. | This is expected because Register uses an anchor link.       |
| Changes do not appear.                | Save the edited file and refresh your browser.               |

## Application Limitations

This application is a front-end activity using only HTML and CSS.

- Registration does not create or save accounts.
- Registration fields and matching passwords are not validated
  when the Register link is clicked.
- Login does not verify credentials.
- The Dashboard can also be opened directly.
- Logout demonstrates navigation; it does not end a login session.
- Student records are fixed sample data.
- No JavaScript, backend, or database is included.
