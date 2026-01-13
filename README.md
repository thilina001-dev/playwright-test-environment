# Playwright Test Environment

A complete Playwright testing setup with MCP integration.

## Setup

1. Clone this repository:
```bash
git clone https://github.com/thilina001-dev/playwright-test-environment.git
cd playwright-test-environment
```

2. Install dependencies:
```bash
npm install
```

3. Install Playwright browsers:
```bash
npx playwright install
```

## Running Tests

```bash
# Run all tests
npm test

# Run tests in headed mode
npm run test:headed

# Debug tests
npm run test:debug

# View test report
npm run report
```

## Project Structure

```
playwright-test-environment/
├── tests/              # Test files
│   └── example.spec.ts
├── playwright.config.ts # Playwright configuration
├── package.json
└── .gitignore
```

## Features

- ✅ TypeScript support
- ✅ Multi-browser testing (Chromium, Firefox, WebKit)
- ✅ Automatic screenshots on failure
- ✅ Video recording on failure
- ✅ HTML test reports
- ✅ Trace viewer integration
