# API demo
## Description
An API desgined in LUMEN to perform CRUD operation on a database with a Swagger files to test the API
Unit tests are included.

It uses an Auth0 token for authentication

This could be extended (based on your business strategy) to:
- allow the scanning, uploading and attaching other documents like proof od ID's or ceetificates 
- include other tables like a user table 
- allow permissions could be added for users of the system in the auth0 account
- include blank fields (maybe 3) for future expansion 
- to search by additional fields like firstname, surname etc

## Installation Requirements
- PHP 8.0 
- Lumen 9.0
- MySQL
- Xampp
- Composer 2.0

After configuration, clone this project to your htdocs folder

To test the API in Swagger, 
- start your local server 
- type http://localhost:8000/api/documentation   in your browser address bar

### Database
Database file attached
[school.zip](https://github.com/Ebow09/API_v1_repo/files/9133381/school.zip)

## License

The Lumen framework is open-sourced software licensed under the [MIT license](https://opensource.org/licenses/MIT).
