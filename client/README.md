
# Fchain Converter Starter Project

## Overview
This is a full-stack web app for converting Fchain to USD, ETH, and BTC in real time using the CoinGecko API.

## Stack
- Frontend: React + Tailwind CSS
- Backend: Node.js + Express
- Auth: JWT
- DB: MongoDB

## Setup Instructions

### 1. Clone Repo & Install Dependencies
```
cd client
npm install

cd ../server
npm install
```

### 2. Set Up Environment Variables
Create a `.env` file in `/server`:
```
MONGO_URI=your_mongodb_connection_string
JWT_SECRET=your_secret_key
```

### 3. Run the App
```
# In one terminal
cd server
npm start

# In another terminal
cd client
npm start
```

Visit http://localhost:3000 to use the app.
