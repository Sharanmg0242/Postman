# Postman Collection for EJS Project

This repository contains a Postman collection for testing the APIs used in the EJS-based project. The collection includes various requests for different endpoints, enabling easy testing and validation of your application's backend.

## Table of Contents
- [Getting Started](#getting-started)
- [Environment Setup](#environment-setup)
- [Using the Collection](#using-the-collection)
- [Endpoints Overview](#endpoints-overview)
- [Contributing](#contributing)
- [License](#license)

## Getting Started

To use this Postman collection, you'll need to have Postman installed on your machine. You can download it from the [Postman website](https://www.postman.com/downloads/).

## Environment Setup

This collection is designed to work with environment variables, making it easier to switch between different environments like development, staging, and production.

### Step 1: Import Environment

1. Download the `postman_environment.json` file from this repository.
2. In Postman, go to the "Environments" tab and click on "Import".
3. Select the `postman_environment.json` file and import it.

### Step 2: Set Up Environment Variables

After importing the environment, you need to configure the variables:

- **`base_url`**: The base URL of your API (e.g., `http://localhost:3000`).
- **`api_key`**: If your API requires authentication, add your API key here.
- **`auth_token`**: Token used for authenticating requests (optional, if applicable).

## Using the Collection

### Step 1: Import the Collection

1. Download the `postman_collection.json` file from this repository.
2. In Postman, go to the "Collections" tab and click on "Import".
3. Select the `postman_collection.json` file and import it.

### Step 2: Running the Requests

1. Select the appropriate environment from the top-right corner in Postman.
2. Choose any request from the collection and click "Send" to execute it.

### Step 3: Running the Collection as a Test Suite

You can run all requests in the collection as a test suite:

1. Click on the "Runner" button (at the top-left of Postman).
2. Select the collection and the environment.
3. Click "Start Test" to run all the requests.

## Endpoints Overview

Here's a brief overview of the key endpoints included in this collection:

- **GET /api/v1/resource**: Fetches all resources.
- **POST /api/v1/resource**: Creates a new resource.
- **GET /api/v1/resource/:id**: Fetches a specific resource by ID.
- **PUT /api/v1/resource/:id**: Updates a specific resource by ID.
- **DELETE /api/v1/resource/:id**: Deletes a specific resource by ID.

Each request in the collection has detailed descriptions and pre-filled data for easy testing.


