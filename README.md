# Capital Game

Welcome to the Capital Game repository! This project is a web application that challenges users to test their knowledge of world capitals. Users are provided with a country, and they must input the correct capital to earn points. The application is built using EJS for the frontend, Node.js with Express for the backend, and PostgreSQL as the database.


https://github.com/divyansharma001/capitalsGame/assets/140371139/47cfafbb-ff77-45f7-9d2e-c8544cac6e8b





## Table of Contents

- [Features](#features)
- [Getting Started](#getting-started)
  - [Prerequisites](#prerequisites)
  - [Installation](#installation)
- [Usage](#usage)
- [Database Setup](#database-setup)
- [Contributing](#contributing)
- [License](#license)

## Features

- Test your knowledge of world capitals.
- Score points by correctly identifying the capital of a given country.
- Store user scores in a PostgreSQL database.
- Responsive design for an optimal user experience.

## Getting Started

### Prerequisites

Make sure you have the following installed on your machine:

- Node.js: [Download and Install Node.js](https://nodejs.org/)
- PostgreSQL: [Download and Install PostgreSQL](https://www.postgresql.org/)

### Installation

1. Clone the repository:

   ```bash
   git clone https://github.com/your-username/capital-game.git
   ```

2. Navigate to the project directory:

   ```bash
   cd capital-game
   ```

3. Install dependencies:

   ```bash
   npm i
   ```

## Usage

1. Start the application:

   ```bash
   npm start
   ```

   The application will be accessible at [http://localhost:3000](http://localhost:3000).

2. Play the Capital Game and try to score as many points as possible!

## Database Setup

1. Create a PostgreSQL database.

2. Update the database configuration in the `config.js` file:

   ```javascript
   // config.js

   module.exports = {
     database: {
       host: 'your-database-host',
       port: 'your-database-port',
       user: 'your-database-user',
       password: 'your-database-password',
       database: 'your-database-name',
     },
     // other configurations...
   };
   ```

3. Run the database migration script to set up the necessary tables:

   ```bash
   npm run migrate
   ```

## Contributing

Contributions are welcome! If you'd like to contribute to this project, please follow the [Contributing Guidelines](CONTRIBUTING.md).

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

Happy playing! 🌍
