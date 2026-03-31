+++
title = "Simple Python Flask API"
summary = "A simple api allowing a user to login and save preferences. Uses JWT authentication and PostgreSQL db."
tags = ["Python", "Flask", "Django", "In Progress", "API", "Swagger", "Auth", "PostgreSQL", "Database"]
weight = 1 
+++

## Github  
https://github.com/TaylorKNoah/simple-python-backend-api

## Status
**In Progress**  
Activley building.

## Overview
A lightweight Python API using Flask, JWT authentication, and PostgreSQL. Handles account creation, login/logout, and full preference CRUD with Alembic‑based migrations.  

Swagger will be used to generate an API UI easily interacted with. The project will be hosted on Render once an initial api is functional and swagger is implemented.  

## Recent Progress
- PostgreSQL db configured and Users table created.
- App created and basic project layout intialized.

## Next Steps
- Next I will build out three endpoints: CreateAccout, Login, and Logout.
- Login will administer a JWT token. To be used with further endpoints.

## Tech Stack
| Use | Tech |  
|-----|------|
| Language | Python | 
| Web Framework | Flask |
| .env file & config | python-dotenv |
| Authentication | Flask‑JWT‑Extended |
| Testing | pytest |
| Database  (DB) | PostgreSQL |
| DB Migrations | Alembic + Flask Migrate |
| DB ORM | SQL Alchemy |
| Serialization & Validation | Marshmellow |
| API UI & Documentation |  Swagger|
| Hosting | Render |