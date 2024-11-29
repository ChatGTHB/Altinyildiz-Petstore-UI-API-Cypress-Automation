
# Cypress Testing Project

![Cypress](https://img.shields.io/badge/Cypress-17202C?style=for-the-badge&logo=cypress&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)
![Node.js](https://img.shields.io/badge/Node.js-339933?style=for-the-badge&logo=nodedotjs&logoColor=white)

## Introduction

This project demonstrates end-to-end testing using [Cypress](https://www.cypress.io/), a powerful and developer-friendly testing framework. The tests include:
- User login functionality
- Account registration
- User actions such as creation, update, and deletion

The primary goal is to ensure seamless user workflows and robust application testing.

---

## Features

- Comprehensive end-to-end tests for user and account workflows.
- Page Object Model (POM) structure for reusable and maintainable code.
- Configured Cypress custom commands for simplified test logic.

---

## Installation

1. Clone the repository:
   ```bash
   git clone <repository-url>
   ```
2. Navigate to the project directory:
   ```bash
   cd cypress-testing-project
   ```
3. Install dependencies using npm:
   ```bash
   npm install
   ```

---

## Usage

### Run All Tests
To execute all Cypress tests, run:
```bash
npx cypress run
```

### Open Cypress Test Runner
To open the interactive Cypress test runner, run:
```bash
npx cypress open
```

### Record Tests
To record tests with the Cypress Dashboard, use:
```bash
npx cypress run --record --key <your-key>
npx cypress run --record --key e500100b-c83d-432a-92b7-a854f2f81838
```
Replace `<your-key>` with the actual project key.

---

## Project Structure

- **`cypress/e2e`**: Contains all test files such as `login-tests.cy.js` and `user-tests.cy.js`.
- **`cypress/pages`**: Includes page object files for modular test structures.
- **`cypress/support`**: Custom commands and global configurations.

---

## Dependencies

This project uses the following dependencies:
- **Cypress**: ^13.15.1
- **Node.js**: 16 or above

Dependencies are managed in `package.json` and `package-lock.json`.

---

## Contributing

We welcome contributions! Follow these steps:
1. Fork this repository.
2. Create a new branch:
   ```bash
   git checkout -b feature-branch
   ```
3. Commit your changes:
   ```bash
   git commit -m "Add new feature"
   ```
4. Push to your branch:
   ```bash
   git push origin feature-branch
   ```
5. Open a pull request.

---

## License

This project is licensed under the MIT License. See the LICENSE file for details.

---

## Contact

For issues or questions, please open an issue in this repository.
