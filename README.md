# Altınyıldız Petstore UI & API Cypress Automation

![Cypress](https://img.shields.io/badge/Cypress-17202C?style=for-the-badge&logo=cypress&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)
![Node.js](https://img.shields.io/badge/Node.js-339933?style=for-the-badge&logo=nodedotjs&logoColor=white)
![REST API](https://img.shields.io/badge/REST-API-blue?style=for-the-badge)

## Introduction

Altinyildiz Petstore UI & API Cypress Automation is a comprehensive end-to-end testing project that covers both UI and API testing using [Cypress](https://www.cypress.io/). The project tests functionalities such as:
- User login
- Account registration
- User actions including creation, update, and deletion
- API requests for user management

The tests are conducted on the following platforms:
- **UI Tests:** [https://www.altinyildizclassics.com/login](https://www.altinyildizclassics.com/login)
- **API Tests:** [https://petstore.swagger.io/v2](https://petstore.swagger.io/v2)

The goal is to ensure seamless user workflows and robust API validation.

---

## Features

- Full coverage of UI and API tests.
- Modular Page Object Model (POM) for UI automation.
- API test implementation using Cypress commands.
- Custom error handling and reusable test utilities.

---

## Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/cihat-kose/altinyildiz-petstore-ui-api-cypress-automation.git
   ```
2. Navigate to the project directory:
   ```bash
   cd altinyildiz-petstore-ui-api-cypress-automation
   ```
3. Install dependencies using npm:
   ```bash
   npm install
   ```

---

## Usage

### Run All Tests
To execute all Cypress tests (UI and API), run:
```bash
npx cypress run
```

### Open Cypress Test Runner
To open the interactive Cypress test runner:
```bash
npx cypress open
```

### Record Tests
To record tests with the Cypress Dashboard:
```bash
npx cypress run --record --key <your-key>
npx cypress run --record --key e500100b-c83d-432a-92b7-a854f2f81838
```
Replace `<your-key>` with the actual project key.

---

## Project Structure

- **`cypress/e2e`**: Contains all test files for UI and API tests (`login-tests.cy.js`, `user-tests.cy.js`).
- **`cypress/pages`**: Page Object files for UI automation.
- **`cypress/support`**: Custom commands and global configurations.
- **`cypress/fixtures`**: Test data for API tests.

---

## Dependencies

This project uses the following dependencies:
- **Cypress**: ^13.17.0
- **Node.js**: 16 or above

Dependencies are managed in `package.json`.

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

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

---

## Contact

For issues or questions, please open an issue in this repository.

