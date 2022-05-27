# Playwright Qase Reporter

## How to use

Install dependecies
```
npm i
```
You should also have an active item in the project settings at
```
https://app.qase.io/project/QASE_PROJECT_CODE/settings/options
```

options in the `Test Runs` block:

```
Auto create test cases
```
and

```
Allow submitting results in bulk
```

Change `api_key` and `project_code` from `playwright.config.js` to actual for you.

---
To run tests and create a test run, execute the command (for example from folder examples):
```bash
QASE_REPORT=1 npx playwright test
```
or
```bash
npm test
```