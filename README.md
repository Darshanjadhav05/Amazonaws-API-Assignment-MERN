# Product Dashboard Application

## Overview
A web application built using the MERN stack (MongoDB, Express, React, Node.js) to manage and visualize product transactions, statistics, and sales data through various charts.

## Features
- **Transactions Table**: View and search through product transactions with pagination.
- **Statistics**: Display total sales, sold items, and unsold items for a selected month.
- **Bar Chart**: Visualize the number of items in defined price ranges for a selected month.
- **Category Pie Chart**: Show the distribution of products across different categories for a selected month.

## Tech Stack
- **Frontend**: React, React Router, Axios, Recharts
- **Backend**: Node.js, Express.js, Mongoose
- **Database**: MongoDB

## Installation

### Prerequisites
- Node.js
- MongoDB

### Setup

1. **Clone the repository**:
   - git clone <repository-url>
   - cd <repository-folder>

2. **Install dependencies: For the server:**
   - cd server
   - npm install

3. **For the client:**
    - cd client
    - npm install

4. **Set up environment variables: Create a .env file in the server directory and add the following:**
     - PORT=5000
     - MONGO_URI=<your-mongodb-uri>
     - THIRD_PARTY_API_URL=https://s3.amazonaws.com/roxiler.com/product_transaction.json

5.**Run the application: Start the MongoDB service, then run:**
    - cd server
    - npm start

6.**In another terminal, run the client:**
    - cd client
    - npm start




