# Acquire

The framework is created using Cypress.io as an automation tool, therefore the programming language is JavaScript.
In order to run the project, it is best to have Visual studio Code as IDE
Install node.js and Cypress
I utilized POM (Page Object Model) design pattern, as it will allow me to separarte each page of the application and store its locators separately
 fixture-> credentials contains frequiently used data
 integration -> acquire is where the test scripts are stored
 plugins-> index.js used to connect to the DB, and add different plugins like faker
 reports-> is where the set up and preferences of the reports are reflected
 support has two main folders -page Object and util.
    in utils-> commands I store methods that can be used 
cypress.json - is where environments are stored
package.json - all framework settings


