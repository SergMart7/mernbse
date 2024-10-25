
# MERN Book Search Engine

## Description

This MERN stack application allows users to search for books using the Google Books API and save their favorite books to a personal list. The app uses GraphQL with Apollo Server for backend API requests and JWT for authentication. Refactoring the original RESTful API to GraphQL enhances performance and flexibility in querying and mutating data.

## Technologies Used

- MongoDB
- Express.js
- React.js
- Node.js
- GraphQL
- Apollo Server
- JWT Authentication
- Google Books API

## Table of Contents

- [Description](#description)
- [Technologies Used](#technologies-used)
- [Installation](#installation)
- [Usage](#usage)
- [License](#license)

## Installation

To get a local copy up and running, follow these steps:

1. Clone the repository:

   ```bash
   git clone https://github.com/SergMart7/mernbse.git
   ```

2. Navigate to the project directory and install dependencies:

   ```bash
   cd mernbse
   npm install
   ```

3. Set up your environment variables:

   Create a `.env` file in the root directory and add the following variables:

   ```plaintext
   MONGODB_URI=mongodb+srv://<username>:<password>@cluster.mongodb.net/<your-db-name>?retryWrites=true&w=majority
   JWT_SECRET=<your-jwt-secret>
   ```

4. Start the application:

   ```bash
   npm start
   ```

5. Open your browser to `http://localhost:3000` to view the application.

## Usage

- **Search for Books**: Enter a book title in the search bar to find books via the Google Books API.
- **Sign Up/Login**: Create a new account or log in to save books to your personal list.
- **Save Books**: While logged in, save books to your account by clicking the "Save This Book" button.
- **View Saved Books**: Access your saved books list to manage and remove books.

## License

This project is licensed under the MIT License.
