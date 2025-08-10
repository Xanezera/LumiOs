# LumiOs
# LuminO QMS

LuminO QMS is a Quality Management System designed to manage audits efficiently. This application provides a user-friendly interface for managing audit records, user authentication, and data export functionalities.

## Features

- **User Authentication**: Secure login and signup functionalities for users.
- **Dashboard**: Overview of audit statistics, including total audits, pending audits, and completed audits.
- **Audit Management**: View, filter, add, and edit audit records.
- **Data Export**: Export audit data to CSV and PDF formats for reporting purposes.

## Project Structure

```
lumino-qms
├── src
│   ├── main.py               # Entry point of the application
│   ├── db.py                 # Database connection and operations
│   ├── ui                    # User interface components
│   │   ├── __init__.py       # Marks the ui directory as a package
│   │   ├── login.py          # User login interface
│   │   ├── signup.py         # User registration interface
│   │   ├── sidebar.py        # Navigation sidebar
│   │   ├── dashboard.py      # Dashboard overview
│   │   └── audit_manager.py  # Audit management interface
│   ├── export                # Data export functionalities
│   │   ├── __init__.py       # Marks the export directory as a package
│   │   ├── csv_export.py     # Export to CSV
│   │   └── pdf_export.py     # Export to PDF
│   └── utils                 # Utility functions
│       └── __init__.py       # Marks the utils directory as a package
├── requirements.txt           # Project dependencies
└── README.md                  # Project documentation
```

## Installation

1. Clone the repository:
   ```
   git clone https://github.com/yourusername/lumino-qms.git
   cd lumino-qms
   ```

2. Install the required dependencies:
   ```
   pip install -r requirements.txt
   ```

3. Initialize the database:
   Run the application to automatically create the database and necessary tables.

## Usage

1. Run the application:
   ```
   python src/main.py
   ```

2. Use the login interface to access the application. If you do not have an account, you can create one using the signup interface.

3. Navigate through the application using the sidebar to manage audits and view statistics.

## Contributing

Contributions are welcome! Please open an issue or submit a pull request for any improvements or features you would like to add.

## License

This project is licensed under the MIT License. See the LICENSE file for details.
<img width="1024" height="1024" alt="ChatGPT Image 10 de ago  de 2025, 10_24_47" src="https://github.com/user-attachments/assets/5a519752-b322-4002-a8b0-856d551f3ba2" />
