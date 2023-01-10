# Cypress + Mocha

# Step 1: Open Cypress Runner Window by running the command 'npx cypress open' in the terminal.
# Step 2: Click on Log in Button i.e. present on top right corner of Cypress Runner Window
# Step 3: Now create a Organization by clicking on Create New Organization button.
# Step 4: Now Click on Projects
# Step 5: Click on New Project and create a project.
# Step 6: First, add the projectId to your cypress.config.js file:
```
module.exports = {
  projectId: "ab12c3"
  // The rest of the Cypress config options go here...
}
```
# Step 7: Then run this command with your record key from your terminal or in CI:
```
npx cypress run --record --key 1509fc6c-74da-4e59-a772-1cb4a3903377
```
# Now open Cypress Dashboard again and see the results in Latest Runs