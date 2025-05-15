# Library Management System 📚

## Description

This project is a relational database system designed for managing a library's book inventory, members, borrowing records, and administrative staff. It uses MySQL to define and enforce relationships between entities such as books, members, authors, and loans.

The system is designed to:

* Track library members and their borrowing history
* Manage book records, including copies and authors
* Enforce data integrity with foreign keys and constraints
* Provide a solid base for building a library management application

## How to Run / Setup

1. **Clone this repository**:

```bash
git clone https://github.com/your-username/library-management-db.git
```

2. **Open MySQL or a GUI tool like MySQL Workbench**

3. **Run the SQL script**:

* Locate the file `library_management.sql`
* Execute it in your SQL environment

This will:

* Create a database named `library_management`
* Create all required tables with proper constraints and relationships

## Entity-Relationship Diagram (ERD)

### ERD link

👉 [View ERD on dbdiagram.io](https://dbdiagram.io/d/682382c55b2fc4582f703349)


## Contents

```
📂 library-management-db/
├── library_management.sql       # Main SQL file with CREATE TABLE statements
├── README.md                    # Project documentation
└── screenshots/
    └── erd.png                  # ERD image (optional)
```

## Author

* \[Eliud Ndiege]

## License

This project is open source under the MIT License.
