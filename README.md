# Bookshelf API using Hapi.js

This repository contains the Bookshelf API project created as part of the Dicoding assessment. The API is developed using Hapi.js, a powerful and flexible JavaScript framework for building web applications and APIs.

## Features

- CRUD operations: Create, Read, Update, and Delete books from the bookshelf.
- Data validation: Input data is validated to ensure consistency and accuracy.
- Error handling: Comprehensive error handling to provide meaningful responses to clients.
- API Documentation: Well-documented API endpoints for easy integration and understanding.

## Requirements

- Node.js: Make sure you have Node.js installed on your system.
- npm: Node Package Manager is needed to install the required dependencies.

## Installation

1. Clone this repository to your local machine.
2. Navigate to the project directory in the terminal.
3. Run `npm install` to install all the required dependencies.

## Usage

1. Start the server: Run `npm start` in the terminal to start the API server.
2. The server will be running at `http://localhost:3000` by default. You can change the port in the configuration file.
3. Access the API documentation at `/documentation` to explore available endpoints and their usage.

## Endpoints

- `GET /books`: Get all books in the bookshelf.
- `GET /books/{bookId}`: Get a specific book by its ID.
- `POST /books`: Add a new book to the bookshelf.
- `PUT /books/{bookId}`: Update an existing book's information.
- `DELETE /books/{bookId}`: Delete a book from the bookshelf.

## Data Format

The API accepts and returns data in JSON format.

### Book Object Format

```json
{
  "id": "string",
  "title": "string",
  "author": "string",
  "year": "number",
  "summary": "string"
}
```

## Examples

**Request:**

```http
GET /books
```

**Response:**

```json
{
  "data": [
    {
      "id": "1",
      "title": "Example Book",
      "author": "John Doe",
      "year": 2022,
      "summary": "This is an example book."
    },
    {
      "id": "2",
      "title": "Another Book",
      "author": "Jane Smith",
      "year": 2021,
      "summary": "Another example book."
    }
  ]
}
```

## License

This project is licensed under the MIT License. Feel free to use, modify, and distribute it as per the license terms.

## Acknowledgments

Thank you to Dicoding for providing the opportunity to learn and demonstrate my skills through this assessment.

---
Feel free to contact me if you have any questions or feedback about the API. Happy coding! 🚀