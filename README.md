# Item Management REST API

A simple Spring Boot backend REST API to manage items.  
Users can add new items and retrieve items by ID using in-memory storage.

## Features
- Add a new item
- Get item by ID
- Input validation
- In-memory data storage

## Technologies Used
- Java
- Spring Boot
- Maven
- REST API

## API Endpoints

### Add Item
POST /api/items

Example body:
{
  "name": "Laptop",
  "description": "Gaming laptop",
  "price": 80000
}

### Get Item
GET /api/items/{id}

## Run Project
```bash
mvn spring-boot:run
