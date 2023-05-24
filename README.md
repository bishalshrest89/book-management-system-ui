# Book Management System UI

This is the frontend application for the Book Management System. It is built using React, Apollo Client, and JavaScript. The frontend allows users to interact with the book management system through a user-friendly interface.

## Features

- Display a list of books with titles, authors, and publication years.
- Add new books with proper validation for required fields.
- Edit and delete existing books.
- Implements Apollo Client to communicate with the GraphQL backend.

## Getting Started

To run the frontend application locally, follow these steps:

### Prerequisites

- Node.js (v14 or higher) should be installed on your machine.

### Installation

1. Clone this repository to your local machine.
2. Navigate to the project directory: `cd book-management-system-frontend`.
3. Install the dependencies: `npm install`.

### Configuration

1. Open the `src/index.js` file.
2. Update the `uri` property in the `ApolloClient` configuration to the appropriate URL of your backend server. By default, it is set to `http://localhost:4000/graphql`.

### Starting the Application

1. Run the following command to start the application:

   ```bash
   npm start
