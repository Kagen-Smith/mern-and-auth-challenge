# mern-and-auth-challenge

# Description

This project is a refactor of a Google Books API search engine. Initially built with a RESTful API, it has been updated to use a GraphQL API with Apollo Server. The application is developed using the MERN stack (MongoDB, Express.js, React, Node.js) and features a React-based front end. Users' book search data is stored in MongoDB. 

The main goal of this refactor was to learn how to integrate GraphQL into a real-world application, enhancing performance and optimizing data fetching. By switching from REST to GraphQL, this project improves the efficiency of book searching and saving while reducing the number of API calls. Key takeaways include setting up Apollo Server, integrating GraphQL within a MERN stack, and deploying the app with MongoDB Atlas.

**Deployed Application**: [mern and auth challenge](https://mern-and-auth-challenge.onrender.com)

## Table of Contents

- [Installation](#installation)
- [Usage](#usage)
- [License](#license)
- [Contributing](#contributing)
- [Questions](#questions)

## Installation

### 1. Clone the Repository
To clone this repository to your local machine, run:

```bash
git clone git@github.com:Kagen-Smith/mern-and-auth-challenge.git
```
### 2. Navigate to the Project Directory
After cloning, navigae to the project's root directory:

```bash
cd mern-and-auth-challenge
```
### 3. Install Dependancies
Install the necessary dependencies with:

```bash
npm install
```

### 4. Run the application locally
To start the application in development mode, use:

```bash
npm run develop
```

## Usage

### 1. Search for Books

-Use the search bar on the homepage to enter a book title.
-Press the "Submit Search" button to search for books through the Google Books API.
-A list of books matching your query will appear on the page.

### 2. Save Books to Your List

-Each book in the search results has a "Save this book!" button.
-Clicking this button will add the book to your personal list, stored in your MongoDB database.

### 3. View Saved Books

-Access your saved books by navigating to the "See Your Books" page via the top menu or sidebar.
-Here, you'll see all the books you've saved.

### 4.Remove Books from Your List

-In the "Saved Books" section, each book has a "Delete this Book!" button.
-Clicking this button will remove the book from your saved list.

## License
This project is licensed under the MIT License. 

## Contributing

## Third-Party Assets
This project utilizes the following third-party tools and libraries:

-Apollo Server – Used to set up the GraphQL server, handling queries and mutations.
-GraphQL – Improves data fetching and API efficiency.
-MongoDB Atlas – Cloud database service used for storing user data, such as saved books.

## Questions
for further questions or inquiries, feel free to reach out at my

- GitHub: https://github.com/Kagen-Smith
- Email: kagensmith27@gmail.com