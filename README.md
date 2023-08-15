# CYPRESS-E-COMMERCE-PROJECT
# E-Commerce Project

# ![Uploading image.png…]()

Welcome to the E-Commerce Test Project repository! This project aims to test a fully functional e-commerce website where users can browse products, add them to their cart, and complete purchases using cypress Page Object Model framework.
Out of about 58 test cases to be executed on the AUT, the first commit has 23 test cases executed while other test scenario and test cases shall be executed or can be as a contribution to the repository. 

I used xpath and css selector to locate page elements and the project is easy to understand.

![image](https://github.com/VEBONG/CYPRESS-E-COMMERCE-PROJECT/assets/128030714/5dce019c-643f-4714-8289-5814118fcc7c)



## Features

- Browse and search products by categories.
- Add products to the cart and proceed to checkout.
- User authentication and registration.
- Admin panel to manage products, orders, and customers.

### Prerequisites

Before you begin, ensure you have the following prerequisites:
- Download and install JDK
- Node.js and npm installed. [Download here](https://nodejs.org/)
- install cypress and also install cypress xpath plugin.
   Xpath plugin can be installed on the framework with: npm install -D @cypress/xpath command. Then add the below code to e2e.js file.
require('@cypress/xpath');


### Contributions

Contributions to the project are welcome.

The project seek to also automate the below Test Scenarios and test cases.

T.S 4 On clicking cart

TC 3.1 Verify cart button is enabled and clickable
TC 3.2 Verify user is taken to cart page on clicking cart button
TC 3.3 Verify user view items in cart
TC 3.4 Verify user can remove items from cart
TC 3.5 Verify continue button on cart page is enabled
TC 3.6 Verify user is taken to items page on clicking continue shopping
TC 3.7 Verify checkout button on cart page is enabled and clickable
TC 3.8 Verify user is taken to checkout information form page on clicking checkout button

T.S 5 Checkout Your Info page

TC 4.1 Verify firstName field accept characters
TC 4.2 Verify lastName field accept characters
TC 4.3 Verify zip/postal code accept only numbers
TC 4.4 Verify the cancel button is enabled and clickable Verify user cannot continue with empty firstname field and error message is displayed
TC 4.5 Verify user cannot continue with empty lastname field and error message is displayed
TC 4.6 Verify user cannot continue with empty firstname, lastname and zip/postal code
TC 4.7 Verify user cannot continue with empty zip/postal code and error message is displayed
TC 4.8 Verify user can continue if data are true by clicking the continue button
TC 4.9 Verify user can view Checkout: Overview page
TC 4.10 Verify user can view payment information
TC 4.11 Verify user can view shipping information
TC 4.12 Verify user can view price total
TC 4.13 Verify user can view total price
TC 4.14 Verify the cancel button is enabled and clickable
TC 4.15 Verify the finish button is enabled and clickable
TC 4.16 Verify order is submitted susccessfully on clicking the finish button
TC 4.17 Verify the home page button is enabled and clickable
TC 4.18 Verify user is taken to product page on clicking home page button

T.S 6 Test Menu button

TC 5.1 Verify menu button is enabled and clickable
TC 5.2 Verify user is taken to about page on clicking about
TC 5.2 Verify user can go back to the product page using the back arrow
TC 5.3 Verify the logout button is enabled
TC 5.4 Verify user is logged out on clicking logout button.
TC 5.5 Verify user is logged out on clicking logout button.
TC 5.6 Verify that the Reset App State button is disabled and not clickable.

So, people can contribute to the repo by writing scripts for the above test scenarios.

This Cypress POM project is for an e-commerce application. The Saucedemo site is the test environment. So, for everyone desiring to learn cypress, this is a nice resource material.

VICTOR is saying, never stop learning.
