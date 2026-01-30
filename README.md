# Playwright Testing

This project contains automated end-to-end tests using Playwright.

## Prerequisites

- Node.js (version 14 or higher)
- yarn

## Installation

Install the project dependencies:

```bash
yarn install
```

Install Playwright browsers:

```bash
yarn playwright install
```

## Running Tests

Run all tests:

```bash
yarn playwright test
```

Run tests in headed mode:

```bash
yarn playwright test --headed
```

Run a specific test file:

```bash
yarn playwright test tests/example.spec.ts
```

Run tests in UI mode:

```bash
yarn playwright test --ui
```

## Viewing Test Results

After running tests, view the HTML report:

```bash
yarn playwright show-report
```

## Project Structure

```
.
├── tests/                  # Test files
│   ├── example.spec.ts
│   ├── my_first_test.spec.js
│   └── test-1.spec.ts
├── test-results/          # Test execution results
├── playwright-report/     # HTML test reports
├── playwright.config.ts   # Playwright configuration
└── package.json          # Project dependencies
```

## Configuration

Test configuration can be modified in `playwright.config.ts`.

## Documentation

- [Playwright Documentation](https://playwright.dev)
- [Best Practices](https://playwright.dev/docs/best-practices)
