# Project requirements
## Users can...
3. Create instructions
4. Share the product(s) of a project
5. Share the instructions
6. Search for projects
## Project structure
## routes
- [ ] login
  - [ ] GET
    1. direct user to login page
  - [ ] POST
    ###### inputs email & password
    1. set user login property to true
    2. redirects user to account
  - [ ] DELETE
    1. set users logged in property to false
    2. redirects user to login page
- [ ] CreateAccount
  - [ ] GET
    1. direct user to create account page
  - [ ] POST
    ###### inputs first-name & last-name & email & passwordToCheck & password
    1. add values (id, first-name, last-name, email, hashword, created-date, modified-id) to database
    2. create user media folder
    3. login user and redirect user to Account
- [ ] Account
  - [ ] GET
    ###### inputs: isLoggedIn
    1. direct user to Account home page
  - [] PUT
    ###### inputs (first-name | last-name | email | newPassword) & email & password
    1. change values in database (first-name, last-name, email, hashword, modified-id) to appropriate values
  - [] DELETE
    ###### inputs email & password
    1. redirect user to createAccount page
    2. remove user account from data base
- [ ] createInstructions/project-id
  - [ ] GET
    ###### inputs: project-id & isLoggedIn
    1. direct user to create instruction for the project
  - [ ] POST
    ###### inputs: (project-name, steps, pictures, project-parameters) & isLoggedIn
    1. create user project in their folder with appropriate values
    2. create a unique project-id for the project
  - [ ] PUT
    ###### inputs: ( project-name, steps, pictures, project-parameters) & isLoggedIn & project-id
    1. update user project in the user media fold with appropriate files by project-id
  - [ ] DELETE
    ###### inputs: project-id & isLoggedIn
    1. remove user project in media folder by project-id
- [ ] project
  - [ ] GET
    ###### inputs: 
    1. direct user to create product? page
- [ ] 
  - [ ] GET
    ###### inputs: 
    1. 
  - [ ] POST
    ###### inputs: 
    1. 
  - [ ] PUT
    ###### inputs: 
    1. 
  - [ ] DELETE
    ###### inputs: 
    1. 
- [ ] 
  - [ ] GET
    ###### inputs: 
    1. 
  - [ ] POST
    ###### inputs: 
    1. 
  - [ ] PUT
    ###### inputs: 
    1. 
  - [ ] DELETE
    ###### inputs: 
    1. 