# API demo
## Description
An API desgined in LUMEN to perform CRUD operation on a database.
Unit tests are included. This project includes swagger for API testing.

It uses an Auth0 token for authentication

This could be extended (based on your business strategy) to:
- allow the scanning, uploading and attaching other documents like proof od ID's or ceetificates 
- include other tables like a user table 
- allow permissions could be added for users of the system in the auth0 account
- include blank fields (maybe 3) for future expansion 
- to search by additional fields like firstname, surname etc
- search fields should be indexed to improve response times

## Installation Requirements
- PHP 8.0 
- Lumen 9.0
- MySQL
- Xampp
- Composer 2.0

After configuration, clone this project to your htdocs folder

To test the API with swagger
- start your local server
- type the url https://localhost:8000/api/documentation
<img width="740" alt="Swagger screenshot" src="https://user-images.githubusercontent.com/32204697/180778683-4fe417aa-a1f1-4fe1-a407-dff905856adc.PNG">

### Database
Database file attached



[school.zip](https://github.com/Ebow09/API_v1_repo/files/9133381/school.zip)

