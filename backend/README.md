Backend README

## Project Title & Overview

**Muscle Cars API**  

An Express-based REST API connected to a PostgreSQL database. It is built for managing muscle car data, including make, model, horsepower, and year. Hosted on Render.
---

## Installation & Setup

### Prerequisites
- Node.js
- PostgreSQL
- npm

### Setup Instructions
```bash
git clone https://github.com/Dylan1207/muscle-cars-api.git
cd muscle-cars-api
npm install
npm start
```

---

## API Documentation

### GET `/api/v1/muscle-cars`
Returns all muscle cars.

### POST `/api/v1/muscle-cars`
Creates a new muscle car.

### PUT `/api/v1/muscle-cars/:id`
Updates a car by ID.

### Example Response
```json
{
  "id": 1,
  "make": "Dodge",
  "model": "Charger",
  "horsepower": 425,
  "year": "1970"
}
```

---

## Database Setup

Using PostgreSQL. Schema should include:
```sql
CREATE TABLE muscle_cars (
  id SERIAL PRIMARY KEY,
  make VARCHAR(50),
  model VARCHAR(50),
  horsepower INTEGER,
  year VARCHAR(4)
);
```

---


## Deployment Guide

This API is deployed using Render.
```bash
git push origin main
```
Render auto-deploys changes on push.

---

## License & Contribution Guidelines
MIT License
