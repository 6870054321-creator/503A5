# 503A5 — VacQ REST API (Hospitals)

Assignment 5 — REST API for the `hospitals` resource, built with Express + Mongoose.

## Setup

```bash
npm install
```

Create `config/config.env` (see `config/config.env.example`):

```
PORT=5000
NODE_ENV=development
MONGO_URI=<your MongoDB Atlas connection string>
```

## Run

```bash
npm run dev     # nodemon, development
npm start       # production
```

Server listens on **http://localhost:5000**

## Endpoints

| Method | Route | Description | Success |
|---|---|---|---|
| GET | `/api/v1/hospitals` | Get all hospitals | 200 |
| GET | `/api/v1/hospitals/:id` | Get one hospital | 200 |
| POST | `/api/v1/hospitals` | Create a hospital | 201 |
| PUT | `/api/v1/hospitals/:id` | Update a hospital | 200 |
| DELETE | `/api/v1/hospitals/:id` | Delete a hospital | 200 |

## Testing

Import `__tests__/PM.json` into Postman and run the `VacQ_assignment5` collection.
