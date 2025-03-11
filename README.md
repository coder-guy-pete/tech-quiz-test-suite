# tech-quiz-test-suite

  [![License: MIT](https://img.shields.io/badge/License-MIT-blue.svg)](https://opensource.org/licenses/MIT)

## Description

    a tech quiz application built using the MERN stack that allows users to take a quiz of ten random questions and view their final score.

## Table of Contents

* [Description](#description)
* [Dependencies](#dependencies)
* [Installation](#installation)
* [Usage](#usage)
* [Contributing](#contributing)
* [License](#license)
* [Questions](#questions)

## Dependencies

  This project relies on the following dependencies:

* **Express**: Used as the core web server to handle API requests from the React client, routing GraphQL queries, and managing middleware for authentication and authorization.
* **Mongoose**: Defines the data models (schemas) for User and Book collections in MongoDB, facilitating data validation and interaction with the database for user authentication, book management, and data retrieval via GraphQL.
* **Dotenv**: Loads environment variables from a .env file to securely manage sensitive information, such as database connection strings and JWT secrets, ensuring they are not exposed in the codebase.
* **MongoDB**: Stores all persistent data, including user accounts, book information, and any other application-specific data models defined using Mongoose.
* **React**: Builds the interactive client-side application, consuming the GraphQL API to display and manage book and user data, and providing a dynamic user experience.
* **Cypress**: for component and end-to-end testing.

## Installation

**Prerequisites:**

* Node.js and npm (or yarn) installed.
* MongoDB installed.

**Steps:**

1. Clone this repository
2. `cd` into the project folder
3. Install the dependencies by runnning `npm install` in the command line
4. `npm run build` to build the application
5. `npm run seed` to seed the database
6. `npm run start:dev` to test the application locally
7. `npm run cypress` to open cypress and initiate the tests or `npm run test` to initiate tests in a headless browser

## Usage

[Video Walkthrough](<https://drive.google.com/file/d/1io_WqA5LcR3KOoV_Cvfpv7q3h-sowUjw/view?usp=sharing>)

## Contributing

Contributions are what make the open source community such an amazing place to learn, inspire, and create. Any contributions you make are **greatly appreciated**.

If you have a suggestion that would make this better, please fork the repo and create a pull request. You can also simply open an issue with the tag "enhancement".
Don't forget to give the project a star! Thanks again!

1. Fork the Project
2. Create your Feature Branch (`git checkout -b feature/AmazingFeature`)
3. Commit your Changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the Branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

## License

  This project is licensed under MIT. For more information, see (<https://opensource.org/licenses/MIT>)

## Questions

  **GitHub**: [coder-guy-pete](https://github.com/coder-guy-pete)

  If you have any questions, please contact me at: <hintze.peter@gmail.com>
