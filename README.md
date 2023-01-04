# cypress-reporter-poc
This a Cypress Reporter POC

### NPM Command
- `npm run cy:run` - to run cypress headless and generate allure results
- `allure:clear": "rm -r allure-results/ allure-report cypress/screenshots || true` - to clear allure-results folder
- `allure generate allure-results --clean -o allure-report` - to generate allure-report
- `mv -f allure-report/history allure-results/history && rm -r allure-report || true` - to generate allure-history

### NPM Package Use
- cypress
- @shelex/cypress-allure-plugin
- cypress-mochawesome-reporter