<H2> GO-Book-Managament-System <H2>

GO-Book-Managament-System is a simple book management system written in Go (Golang) using the GORM ORM and SQLite as the database. It provides basic CRUD (Create, Read, Update, Delete) operations for managing books.

## Features
- Create Book: Add a new book to the system with details such as name, author, and publication.
- Get All Books: Retrieve a list of all books stored in the system.
- Get Book by ID: Retrieve a specific book by its unique identifier.
- Delete Book: Remove a book from the system based on its ID.


## Usage
1. Ensure that you have Golang installed on your system.

2. Configure the database connection in the `config/config.go` file.

3. Run the application using the `go run main.go` command.

4. Access the API endpoints to interact with the book management system.

## API Endpoints

- Create Book:
  - Endpoint: `POST /books`
  - Payload: JSON object with book details (name, author, publication).

- Get All Books:
  - Endpoint: `GET /books`
  - Response: JSON array containing a list of all books.

- Get Book by ID:
  - Endpoint: `GET /books/{id}`
  - Response: JSON object representing the book with the specified ID.

- Delete Book:
  - Endpoint: `DELETE /books/{id}`
  - Response: JSON object confirming the deletion of the book.

## Database
This project uses SQLite as the database. You can configure the database connection in the `config/config.go` file.

## Dependencies
- [GORM](https://gorm.io/): The fantastic ORM library for Golang.

## Contributing
Contributions are welcome! If you find any issues or have suggestions for improvements, please create an issue or a pull request.

## License
This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.