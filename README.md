# DevOps CI Demo

This project showcases a basic **Continuous Integration (CI)** setup using **GitHub Actions**.

### Overview

1. A simple Node.js script outputs `"Hello CI from Node.js!"`.
2. A Jest test verifies that the output is correct.
3. GitHub Actions automatically executes the tests whenever a Pull Request is opened or updated.

### Commands

* `npm install` — install project dependencies
* `npm test` — run all tests

---

### GitHub Actions Workflow

The CI pipeline is triggered automatically on every Pull Request creation or update, ensuring that all tests pass before merging.
