# HNG Stage 1 API

A minimal REST API built with Node.js and Express, deployed on Ubuntu 22.04 with Nginx as a reverse proxy.

## How to Run Locally

### Prerequisites
- Node.js LTS
- npm

### Steps
git clone https://github.com/Michaelayz/hng-stage1-api
cd hng-stage1-api
npm install
node index.js

The API will run on http://localhost:5000

## Endpoints

| Endpoint | Method | Response |
|----------|--------|----------|
| `/` | GET | `{"message": "API is running"}` |
| `/health` | GET | `{"message": "healthy"}` |
| `/me` | GET | `{"name": "Michael Ayozie", "email": "michaelayozie5@gmail.com", "github": "https://github.com/Michaelayz"}` |

All endpoints return `Content-Type: application/json` and HTTP status `200`.

## Live URL

https://yzbtboy.duckdns.org
