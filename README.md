# Cypress_testing_project


Following these steps:

Step 1 - Install Node.js

Step 2 - Install Visual Studio Code

Step 3 - Create a new folder for Cypress project

Step 4 - Open the folder in VS Code

Step 5 - Open VS Code terminal & run command ( npm init -y)

Step 6 - Install Cypress (npm install cypress)

Step 7 - Open Cypress(npx cypress open)

Step 8 - Create a file under cypress ＞ integration folder

Step 9 - At the top mention
>>
/// ＜reference types="cypress" /＞
>>
To write a test we need a test runner - mocha
mocha comes built-in with cypress

Step 10 - Write test function
>>
it('login and navigate to homepage', () =＞
    cy.visit('https://google.com/'
})
>>
Step 11 - Run test
npx cypress open

See what happens when you make any changes & save
 "watchForFileChanges": true
cypress.json
Step 12 - Access elements

