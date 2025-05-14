# Library Management System Database

![Database ER Diagram](docs/ERD.png)

## Project Description

A comprehensive MySQL database design for a Library Management System. This database supports:

- Member management and membership tracking
- Book catalog with authors, publishers, and genres
- Inventory management for physical book copies
- Loan and reservation systems
- Fine calculation and tracking
- Staff management
- Audit logging for security

## Database Schema Features

- 11 normalized tables with proper relationships
- Constraints for data integrity (PK, FK, NOT NULL, UNIQUE, CHECK)
- Support for one-to-one, one-to-many, and many-to-many relationships
- Enforced business rules through constraints
- Audit trail for important operations

## Setup Instructions

### Prerequisites

- MySQL Server (8.0+ recommended)
- MySQL Workbench or another MySQL client

### Installation

1. Clone this repository:
   ```bash
   git clone https://github.com/yourusername/library-management-db.git