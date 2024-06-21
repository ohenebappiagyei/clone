# Webpack Development Server and Modularization

This project demonstrates setting up a Webpack development server with modularized code for a web application. The project is divided into header, body, and footer modules, each with its own CSS and JavaScript files. The Webpack configuration is optimized for development and includes features such as inline source mapping, automatic HTML file generation, and code splitting.

## Table of Contents

- [Getting Started](#getting-started)
- [Project Structure](#project-structure)
- [Development](#development)
- [Building for Production](#building-for-production)
- [Features](#features)
- [Contributing](#contributing)
- [License](#license)

## Getting Started

To get a local copy up and running, follow these steps.

### Prerequisites

Ensure you have Node.js and npm installed. You can download them from [nodejs.org](https://nodejs.org/).

#### Installation

1. Clone the repository:
   ```bash
   git clone <repository-url>
   cd task_3
2. Install the dependencies:
    ```bash
    npm install

### Project Structure for task_3/
task_3/
├── css/
│   ├── body.css
│   ├── footer.css
│   └── header.css
├── js/
│   ├── body.js
│   ├── footer.js
│   └── header.js
├── assets/
│   └── holberton-logo.jpg
├── public/
│   ├── index.html
│   └── (generated files)
├── .gitignore
├── package.json
├── webpack.config.js
└── README.md

### Development
To start the development server, run:
```bash
npm run start-dev

This will start a development server at http://localhost:8564 and automatically open it in your default web browser.

### Building for Production
To build the project for production, run:
```bash
npm run build

This will generate the optimized files in the public directory.

### Features
- Development Server: Easily start a development server with hot-reloading.
- Modular Code: Code is divided into header, body, and footer modules.
- CSS and Images Support: CSS and images are included in the Webpack bundle.
- Source Mapping: Inline source mapping for easier debugging.
- Code Splitting: Optimized bundles with code splitting to improve performance.
- Automatic HTML Generation: Webpack generates the index.html file automatically.
- Clean Build Directory: The build directory is cleaned before each build.


### Contributing
Contributions are welcome! Please fork the repository and create a pull request with your changes.

### License
This project is licensed under the MIT License - see the LICENSE file for details.
