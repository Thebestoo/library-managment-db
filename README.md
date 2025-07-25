# Library Management Database

This project is a MySQL database schema for a library management system designed to store information about book categories, authors, books, and students borrowing books.

## Tables

- **Kategorit**: Book categories
- **Autoret**: Authors of the books
- **Librat**: Books available in the library
- **LibratAutoret**: Many-to-many relationship between books and authors
- **Nxënësit**: Students who borrow books

## How to use

1. Import `schema.sql` to create the tables.
2. Import `sample_data.sql` to insert test data.
3. Use `queries.sql` for sample queries such as listing all books by author or category.

## Example Queries

- List all books and their authors
- Find books by category
- List students who borrowed a particular book

---

Feel free to explore and modify the schema to suit your needs!

