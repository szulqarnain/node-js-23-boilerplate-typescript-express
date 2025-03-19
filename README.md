# Node.js 23 Boilerplate (TypeScript + Express)

This is a simple boilerplate for setting up a Node.js application with TypeScript and Express. It provides a minimal structure to quickly get started with a TypeScript-based Express server.

## Features
- TypeScript for type-safe development
- Express.js for server handling
- Nodemon for automatic server restart on file changes
- ts-node for running TypeScript files directly
- Simple and clean project structure

## Installation

Ensure you have **Node.js (>=14.0.0)** installed on your system. Then, follow these steps:

1. Clone this repository:
   ```sh
   git clone https://github.com/szulqarnain/node-js-23-boilerplate-typescript-express.git
   ```
2. Navigate to the project directory:
   ```sh
   cd node-js-23-boilerplate-typescript-express
   ```
3. Install dependencies:
   ```sh
   npm install
   ```

## Running the Application

### Development Mode
To start the application in development mode with automatic reloading using **nodemon**, run:
   ```sh
   npm run serve
   ```

### Production Mode
To run the compiled JavaScript files in production mode:
   ```sh
   npm run build
   npm start
   ```

## Project Structure
```
project-root/
│── src/
│   ├── index.ts     # Main server file
│── dist/            # Compiled JavaScript files (after build)
│── package.json     # Dependencies and scripts
│── tsconfig.json    # TypeScript configuration
│── README.md        # Project documentation
```

## API Endpoint
The server runs by default on `http://localhost:3000/` and has a simple route:

- **GET /** - Returns `"Hello, TypeScript Express!"`

## Scripts
- `npm run start` - Runs the server in production mode.
- `npm run build` - Compiles TypeScript into JavaScript.
- `npm run serve` - Starts the server in development mode using nodemon.

## License
This project is licensed under the ISC License.

