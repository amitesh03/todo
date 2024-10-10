# Todo App

This is a simple Todo application built using React, JWT for authentication, PostgreSQL as the database, and Prisma as the ORM.

## Features

- User authentication with JWT
- Create, read, update, and delete todos
- Responsive design

## Technologies Used

- **React**: Frontend library for building user interfaces
- **JWT**: JSON Web Tokens for secure authentication
- **PostgreSQL**: Relational database for storing todos
- **Prisma**: ORM for database management

## Installation

1. Clone the repository:

   ```sh
   git clone https://github.com/yourusername/todo-app.git
   cd todo-app
   ```

2. Install dependencies:

   ```sh
   npm install
   ```

3. Set up environment variables:
   Create a `.env` file in the root directory and add the following:

   ```env
   DATABASE_URL=your_postgresql_database_url
   JWT_SECRET=your_jwt_secret
   ```

4. Run database migrations:

   ```sh
   npx prisma migrate dev
   ```

5. Start the development server:
   ```sh
   npm start
   ```

## Usage

1. Register a new account or log in with an existing account.
2. Create new todos, mark them as complete, edit, or delete them.

## Contributing

Contributions are welcome! Please open an issue or submit a pull request.

## License

This project is licensed under the MIT License.
