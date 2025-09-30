# Simple Node.js Express REST API

This project is a minimal REST API built with Node.js and Express for testing purposes.

## Features
- GET /api/hello: Returns a greeting message
- POST /api/echo: Echoes back the posted JSON

## Setup Instructions

1. Install dependencies:
   ```bash
   npm install
   ```
2. Start the server:
   ```bash
   node index.js
   ```

## Endpoints
- `GET /api/hello` → `{ "message": "Hello, world!" }`
- `POST /api/echo` → Returns the posted JSON body
