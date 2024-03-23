# Library Management System with Admin Login

This project is a Library Management System with an added feature of an Admin Login system built using Tkinter in Python. It allows users to manage books, borrow and return them, and also provides an interface for admin login to access the system.

## Features

- **Admin Login**: Authenticate admin users before accessing the library management system.
- **Borrow Books**: Users can borrow books by providing necessary details like book ID, name, student details, and issue date.
- **Return Books**: Users can return borrowed books with book ID and return date.
- **Add/Delete Books**: Admins can add new books to the library or delete existing ones.
- **Display Available Books**: View all available books in the library.
- **Search Books**: Search for specific books by their ID or name.
- **Display Borrowing History**: Users can view their borrowing history.
- **Show Last 3 Borrowing Histories**: View the last 3 borrowing histories.

## Prerequisites

- Python 3.x
- Tkinter library
- tkcalendar library (Install using `pip install tkcalendar`)

## Installation

1. Install the required dependencies:

    ```
    pip install tkcalendar
    pip install ttkthemes
    ```

## Usage

1. Run the program:

    ```
    python main.py
    ```

2. Admin Login:
   - Upon running, the program will prompt for admin login details.
   - Enter the username and password to access the library management system.

3. Library Management:
   - Once logged in, you can perform various tasks like borrowing books, returning books, adding/deleting books, and viewing borrowing history.

4. Logout:
   - Click on the "Log Out" button to exit the program.

## Contributing

Contributions are welcome! If you'd like to contribute to this project, feel free to submit a pull request with your changes.

## License

This project is licensed under the [Apache-2.0 license](LICENSE).

---

Feel free to customize this README file according to your project's specific details and requirements.
