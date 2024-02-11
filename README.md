# SmartHomes Online Retailer

SmartHomes Online Retailer is a React-based web application that allows customers to place orders online from the SmartHomes website. The application includes features such as product browsing, order placement, customer accounts, and more.

## Features

- **Product Categories:**
  - Smart Doorbells
  - Smart Doorlocks
  - Smart Speakers
  - Smart Lightings
  - Smart Thermostats

- **Order Options:**
  - Store Pickup
  - Home Delivery

- **User Roles:**
  - StoreManager
  - Customers
  - Salesmen

- **Product Details:**
  - Name
  - Price
  - Description
  - Accessories

- **Order Management:**
  - Place, check, and cancel orders
  - Choose delivery or in-store pickup
  - Pay using credit card
  - Apply discounts and rebates

- **User Authentication:**
  - Create customer accounts
  - Login with account credentials
  - Secure storage in MySQL database

- **Product Reviews:**
  - Submit and view product reviews
  - Reviews stored in MongoDB

- **Search Auto-Completion:**
  - Auto-complete feature for product search
  - Products stored in MySQL database
  - Auto-complete code in `AjaxUtility.js`

## Setup

1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/SmartHomes.git
   cd SmartHomes

2. Install dependencies:
    npm install

3. Start the development server:
     npm start

4. Access the application:
     Open your web browser and go to http://localhost:3000

## Database Initialization

1. Initialize MySQL database:

  - Create tables for Stores, Products, Customers, and Transactions.
  - Insert store locations, customers, transactions, and product reviews.

2. Set up MongoDB database:

  - Create a collection for product reviews.
  
3. Populate data for testing:

  - Add at least 10 store locations with addresses for in-store pickup.
  - Add at least 20 customers with addresses.
  - Add at least 20 transactions.
  - Add at least 20 product reviews.
