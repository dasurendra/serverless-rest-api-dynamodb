# Serverless Products API

This is a simple Serverless API for managing products using AWS DynamoDB. It provides CRUD operations for products.

## Setup

1. Clone the repository.
2. Install dependencies: `npm install`
3. Deploy the Serverless stack: `serverless deploy`
4. Use the provided API endpoints to manage products.

## Endpoints

- `POST /product`: Create a new product
- `GET /product/{id}`: Get a product by ID
- `PUT /product/{id}`: Update a product by ID
- `DELETE /product/{id}`: Delete a product by ID
- `GET /products`: List all products
