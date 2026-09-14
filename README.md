# Project 3 – Playwright / Gherkin BDD Test Automation

## Overview
This project demonstrates behaviour-driven test automation using Playwright with Gherkin (BDD) syntax, targeting ParaBank (https://parabank.parasoft.com), a public demo banking application. It highlights readable, business-facing test scenarios alongside solid technical automation.

## Objectives
- Write clear Gherkin feature files describing user-facing banking scenarios
- Implement Playwright step definitions to automate those scenarios
- Cover key UI flows: login, account overview, transactions, transfers
- Integrate with CI for automatic test runs

## Tech Stack
- Language: TypeScript / JavaScript (or Python, TBD)
- Automation: Playwright
- BDD: Cucumber / playwright-bdd (TBD)
- Target app: ParaBank (https://parabank.parasoft.com)
- CI: GitHub Actions

## Test Scope
- [ ] Login / authentication scenarios
- [ ] Account overview / balance display
- [ ] Transaction history
- [ ] Fund transfer flow
- [ ] Negative/error scenarios (invalid login, failed transfer, etc.)

## Example Feature (placeholder)
\```gherkin
Feature: Account login
  Scenario: Successful login with valid credentials
    Given the user is on the ParaBank login page
    When they enter valid credentials
    Then they should see their account dashboard
\```

## Setup
\```bash
# TBD once implementation starts
npm install
npx playwright test
\```

## Status
🚧 Skeleton — implementation not yet started.

## Roadmap
1. Explore ParaBank site structure and identify key flows
2. Write feature files for core scenarios
3. Implement Playwright step definitions
4. Add CI pipeline
5. Document coverage & results
