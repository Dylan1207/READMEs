Frontend README

## Project Title & Overview

**Muscle Cars Web App**  

A React-based frontend that allows users to view, add, and update muscle car records. It connects to a live API hosted on Render and uses Grid.js to present data in table format.
---

## Installation & Setup

**Prerequisites**
- Node.js
- npm

### Setup Instructions
```bash
git clone https://github.com/Dylan1207/muscle-cars-app.git
cd muscle-cars-app
npm install
npm run dev
```

Open your browser and go to:
```
http://localhost:5173
```

---

## Usage Instructions

- Use the navigation bar to view, add, or modify muscle car records.
- View page: Browse data in a searchable table.
- Add page: Fill out form to add a car.
- Modify page: Select a car and update its info.

---

## API Integration
The frontend communicates with the following API:

Base URL:
```
https://muscle-cars-api.onrender.com/api/v1/muscle-cars
```

### Example Endpoint Usage
```javascript
fetch("https://muscle-cars-api.onrender.com/api/v1/muscle-cars")
```

- GET: Fetch all cars
- POST: Add a car
- PUT: Update a car by ID

---

## Contributing Guidelines
- Fork the repository
- Create a new branch
- Submit a pull request with a clear description

---

## License
MIT License
