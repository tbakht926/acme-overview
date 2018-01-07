## Acme Overview

- Acme Prework
  - writing some function to prepare for ACME projects
  *merging a list of products and lineItems*
- Express App with in memory data 
  - storing data as Javascript object
  - using method override to delete data
  - RESTFUL routes
  
  - *A list of products with link to product details*
  - *Ability to delete a product on the detail page*
- SQL App (no ORM)
  - using sqlite3 package to create database access objects
  - ability to insert and delete data using body parsing
  - *A list of products with link to product details*
  - *Ability to delete a product on the detail page*
  - *Ability to add a product on the list page*
  - *Adding a product redirects to detail*
  - *Deleting a product redirects to list*
- Single ORM App (no relations)
  - using a single model in Sequelize
  - insert, update, and delete data
  - *A list of users with first name, last name, email and hire date*
  - *A edit page for a user where the user can be deleted*
  - *Ability to create a user on the list page* 
  - *Ability to sort list of users based on attributes* 
- Multi Relation ORM App with Tests
  - using multiple models in sequelize
  - creating class methods for complex business logic

  - *A list of users with first name, last name, email, hire date, canMentor, mentor, and mentees*
  - *An edit page for a user where the user can be deleted*
  - *A users mentor can be set on the edit page*
  - *Only a user who can mentor can have mentees*
  - *A User who loses the canMentor status loses mentees*
  - *A User who has mentees can not be deleted*
  - *Write tests for complex business logic*
- JQuery Single Page Application
  - use AJAX to fetch data
  - use components to update UI
  - using a third party component
- Using Redux to store client side state
- Building a React Redux Application
