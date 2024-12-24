# Keycloak CRUD API Quick Reference

![Version](https://img.shields.io/badge/version-1.0.0-blue.svg)
![License](https://img.shields.io/badge/license-MIT-green.svg)
![Keycloak](https://img.shields.io/badge/Keycloak-26.0.7-orange.svg)

## Table of Contents

- [Introduction](#introduction)
- [Features](#features)
- [Installation](#installation)
- [API Endpoints](#api-endpoints)
  - [Create](#create)
  - [Read](#read)
  - [Update](#update)
  - [Delete](#delete)
- [Examples](#examples)
- [Contributing](#contributing)
- [License](#license)
- [Contact](#contact)

## Introduction

Welcome to the **Keycloak CRUD API Quick Reference**! This project serves as a concise reference guide for performing Create, Read, Update, and Delete (CRUD) operations using the Keycloak API. Navigating the official Keycloak documentation can be challenging, so this quick reference aims to simplify your development workflow by providing clear and direct API endpoints and usage examples.

## Features

- **Comprehensive CRUD Operations**: Covers all essential CRUD functionalities for managing Keycloak resources.
- **Easy Navigation**: Organized sections for quick reference.
- **Up-to-Date**: Based on Keycloak version 26.0.7
- **Examples Included**: Practical examples to demonstrate API usage.

## Installation

This quick reference is a documentation resource and does not require installation. However, if you wish to contribute or host it locally, follow the steps below.

### Clone the Repository

```bash
git clone https://github.com/yourusername/keycloak-crud-cheatsheet.git
cd keycloak-crud-cheatsheet
```

then open index.html file on your browser

## Examples

Here ie an example of how to update a user using curl

```bash
curl -X PUT "https://<keycloak-server>/auth/admin/realms/${realm}/users/${user_id}" \
-H "Content-Type: application/json" \
-H "Authorization: Bearer <access_token>" \
-d '{
  "email": "updateduser@example.com",
  "enabled": false
}'
```

## Contributing

Contributions are welcome! Please follow these steps:

1. Fork the repository.
2. Create a new branch: git checkout -b feature/YourFeature
3. Commit your changes: git commit -m 'Add some feature'
4. Push to the branch: git push origin feature/YourFeature
5. Open a pull request.

Please ensure your contributions adhere to the project's coding standards and include relevant documentation.

## License

This project is licensed under the MIT License.

## Contact

For any questions or suggestions, feel free to reach out:

GitHub: @iamannani

Happy coding! 🚀
