# MongoDB CRUD Operations with Node.js

## Project Overview

This project demonstrates how to connect a Node.js application to a MongoDB database using the MongoDB Node.js Driver. It performs basic CRUD (Create, Read, Update, Delete) operations on a collection.

## Features

- Connect to MongoDB
- Create a database and collection
- Insert one document
- Insert multiple documents
- Read all documents
- Find a specific document
- Update a document
- Delete a document
- Close the database connection

## Technologies Used

- Node.js
- MongoDB
- MongoDB Node.js Driver
- JavaScript

## Prerequisites

- Node.js installed
- MongoDB installed and running
- VS Code or any code editor

## Installation

1. Clone the repository.

```bash
git clone <repository-url>
```

2. Navigate to the project folder.

```bash
cd mongodb-project
```

3. Install dependencies.

```bash
npm install mongodb
```

## Running the Project

Start the application using:

```bash
node app.js
```

## CRUD Operations

### Create
- Insert one document
- Insert multiple documents

### Read
- Display all documents
- Find a document using a filter

### Update
- Modify an existing document

### Delete
- Remove a document from the collection

## Project Structure

```
mongodb-project/
│
├── app.js
├── package.json
├── package-lock.json
├── README.md
```

## Sample Collection

```json
{
  "name": "John",
  "age": 22,
  "city": "Bangalore"
}
```

## Learning Outcomes

- Understanding MongoDB database connectivity
- Performing CRUD operations
- Using asynchronous JavaScript with async/await
- Working with MongoDB collections and documents

## Author

Gnaneshwari C S
