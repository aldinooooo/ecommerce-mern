# Fullstack E-commerce (MERN)


### 
## **Admin Features:**
1. **Product Management:**
    - Create Products
    - Admin interface for adding, editing, and deleting products.
2. **Dashboard:**
    - Provide a summary of user activities.
    - Manage products.


## **User Features:**
1. **Registration :** 
    - Create accounts 
      
## **General Features:**
1. **Authentication and Authorization:**
    - User login with secure authentication.
    - Role-based access control.

2. **Profile Management:**
    - Update user profiles.
    -  Change passwords securely.
  
3. **Shopping Cart Functionality:**
    - Users can add products to their cart
    - Update quantities, and remove items.
      
4. **Payment Processing:**
    - Integration with Stripe for secure payment transactions.
   
5. **Order Management:**
    - Users and admin can view their order history, cancel orders, and track order fulfillment.
   
6. **Responsive Design:**
    - Mobile-friendly interface for a better user experience on all devices.


## **Technologies Used:**
- **Frontend:**
    - React (Vite)
    - Redux for State Management
    - Tailwind CSS for styling
    - React Router For handling navigation and routing.


- **Backend:**
    - Node.js with Express.js
    
- **Database:**
    - MongoDB for efficient and scalable data storage.

&nbsp;

## SETUP INSTRUCTIONS

# Server Setup

## Environment variables
First, create the environment variables file `.env` in the server folder. The `.env` file contains the following environment variables:

- MONGODB_URI = `your MongoDB URL`
- JWT_SECRET = `any secret key - must be secured`
- PORT = `8800` or any port number
- NODE_ENV = `development`

&nbsp;

## Set Up MongoDB:

1. Setting up MongoDB involves a few steps:
    - Visit MongoDB Atlas Website
        - Go to the MongoDB Atlas website: [https://www.mongodb.com/cloud/atlas](https://www.mongodb.com/cloud/atlas).
    - Create an Account
    - Log in to your MongoDB Atlas account.
    - Create a New Cluster
    - Choose a Cloud Provider and Region
    - Configure Cluster Settings
    - Create Cluster
    - Wait for Cluster to Deploy
    - Create Database User
    - Set Up IP Whitelist
    - Connect to Cluster
    - Configure Your Application
    - Test the Connection

2. Create a new database and configure the `.env` file with the MongoDB connection URL. 

## Steps to run server

1. Open the project in any editor of choice.
2. Navigate into the server directory `cd server`.
3. Run `npm i` or `npm install` to install the packages.
4. Run `npm run dev` to start the server.

If configured correctly, you should see a message indicating that the server is running successfully and `MongoDB connected:`.

&nbsp;

# Client Side Setup

## Steps to run client

1. Navigate into the client directory `cd client`.
2. Run `npm i` or `npm install` to install the packages.
3. Run `npm start` to run the app on `http://localhost:3000`.
4. Open [http://localhost:3000](http://localhost:3000) to view it in your browser.



&nbsp;
