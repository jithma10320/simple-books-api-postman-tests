# Simple Books API - Postman Tests

This repository contains API tests for the [Simple Books API](https://simple-books-api.glitch.me) using Postman.

## 📦 Contents

- `SimpleBooksAPI.postman_collection.json`: The exported Postman collection
- (Optional) `SimpleBooksAPIEnvironment.postman_environment.json`: Environment file used for testing

## 🛠️ Tools Used

- [Postman](https://www.postman.com/)
- Simple Books API

## 🚀 How to Use

1. Open Postman
2. Import the collection (`.json` file)
3. (Optional) Import the environment
4. Run requests or collections using the Collection Runner
5. Check tests in the "Tests" tab of each request

## 🔐 Authentication

- Some endpoints require an access token.
- To generate one, send a POST request to `/api-clients` with your name and email.

