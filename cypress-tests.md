# Testing with Cypress

Cypress is a testing software or program mainly used to conduct UI tests in a webpage.

### Installation:

`npm install cypress --save-dev`

### To run:

`npx cypress open`


### Write your first test:

`describe('The home page', () => {
it.('Successfully opens the landing page', () => {
cy.visit('http://localhost:3000')
})
}
)`

Visit: https://docs.cypress.io/guides/getting-started/installing-cypress#Opening-Cypress
