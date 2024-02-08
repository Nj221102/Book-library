# Book Library Application

This project is a book library application built using React.js for the frontend and Node.js with Express.js for the backend. It provides functionalities to search for books, filter them based on various criteria such as author, country, title, and year, and view detailed information about each book.

## Features

- Search for books by author, country, title, or publish year.
- Filter books based on multiple criteria.
- View detailed information about each book, including author, year, country, pages, and language.

## Installation

To run this project locally, follow these steps:

1. Clone the repository:

    ```bash
    git clone https://github.com/Nj221102/Book-library.git
    ```

2. Navigate to the project directory:

    ```bash
    cd book-library
    ```

3. Install dependencies for both the frontend and backend:

    ```bash
    cd client
    npm install
    cd ../server
    npm install
    ```

4. Start the backend server:

    ```bash
    npm start
    ```

5. Start the frontend development server:

    ```bash
    cd ../client
    npm start
    ```

6. Open your browser and visit `http://localhost:3000` to access the application.

## Backend API Endpoints

The backend provides the following API endpoints:

- `GET /api/all-books`: Retrieve all unique books.
- `GET /api/books`: Retrieve books based on query parameters (author, country, year, title).
- `GET /api/book/details`: Retrieve details of a specific book by title.
- `GET /api/authors`: Retrieve a unique list of authors.
- `GET /api/countries`: Retrieve a unique list of countries.

## Frontend Components

### App.js

The main component responsible for rendering the book library interface. It includes search functionality and displays a list of books based on the search criteria.

### Book.js

A component to display detailed information about a specific book. It fetches book details based on the title from the backend API.

## Technologies Used

- React.js
- Node.js
- Express.js
- MongoDB
- Mongoose
- Axios
- React Router

## Contributing

Contributions are welcome! If you find any issues or have suggestions for improvements, feel free to open an issue or submit a pull request.

## License

This project is licensed under the [MIT License](LICENSE).
