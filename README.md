# TechBazar eCommerce Platform

> eCommerce platform built with the MERN stack & Redux.

Check live demo at: https://techbazar.onrender.com

> Log In Credentials
```
email: jayesh@example.com
password: 123456

Fake payment method 'Paypal' is available.
Just click on paypal button on order screen.
```
## Screenshots
### 1.
![Screenchot](https://github.com/ShivaMaurya06/techbazar/blob/main/uploads/app_pic1.png)
### 2.
![screenshot](https://github.com/ShivaMaurya06/techbazar/blob/main/uploads/app_pic2.png)
### 3.
![screenshot](https://github.com/ShivaMaurya06/techbazar/blob/main/uploads/app_pic3.png)

## Features

- Full featured shopping cart
- Product reviews and ratings
- Top products carousel
- Product pagination
- Product search feature
- User profile with orders
- Admin product management
- Admin user management
- Admin Order details page
- Mark orders as delivered option
- Checkout process (shipping, payment method, etc)
- PayPal / credit card integration
- Database seeder (products & users)

## Usage

### Env Variables

Create a .env file in then root and add the following

```
NODE_ENV = development
PORT = 5000
MONGO_URI = your mongodb uri
JWT_SECRET = 'abc123'
PAYPAL_CLIENT_ID = your paypal client id
```

### Install Dependencies (frontend & backend)

```
npm install
cd frontend
npm install
```

### Run

```
# Run frontend (:3000) & backend (:5000)
npm run dev

# Run backend only
npm run server
```

## Build & Deploy

```
# Create frontend prod build
cd frontend
npm run build
```
### Seed Database

You can use the following commands to seed the database with some sample users and products as well as destroy all data

```
# Import data
npm run data:import

# Destroy data
npm run data:destroy
```

```
Sample User Logins

admin@example.com (Admin)
123456

jayesh@example.com (Customer)
123456

janki@example.com (Customer)
123456
```


