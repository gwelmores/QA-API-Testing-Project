# QA API Testing Project

This project demonstrates API testing using Postman and Newman CLI.

## Tools Used
- Postman
- Newman
- JavaScript (Postman Tests)

## Features Tested
- GET Users
- POST Create User
- PUT Update User
- DELETE User
- Authentication

## How to Run

```bash
newman run API Testing.postman_collection.json -e QA Environment.postman_environment.json -r cli,html