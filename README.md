# FOODIEHUB | MERN Food Delivery App

FoodieHub is a full-stack **food ordering and delivery web application** built using the **MERN stack**. It provides a seamless platform for users to browse food items, add them to cart, place orders, and make payments, while admins can manage food products and orders through a dedicated admin panel.

## Live Demo

- User Panel: [https://foodiehub-food-ordering.vercel.app/]
- Admin Panel: [https://foodiehub-food-ordering-4km1-shreya-gughanes-projects.vercel.app/]

## Features

### User Features
- User Signup / Login
- Browse food items by category
- Add items to cart
- Update cart quantity
- Place food orders
- Stripe payment integration
- Responsive and user-friendly interface

### Admin Features
- Secure admin login
- Add new food items with image upload
- View all food products
- Remove food items
- Manage customer orders

## Tech Stack

### Frontend
- React.js
- Vite
- CSS

### Backend
- Node.js
- Express.js
- MongoDB
- Mongoose
- JWT
- bcrypt
- Multer
- Stripe

### Authentication & Security
- JWT Authentication
- Password hashing using bcrypt
- Role-based admin identification
- Protected backend APIs

## Screenshots
### Home Page
![Home Page](./screenshots/home-page.png)

### Cart Page
![Cart Page](./screenshots/cart-page.png)

### Admin Panel
![Admin Panel](./screenshots/admin-panel.png)

## Environment Variables
PORT=4000
JWT_SECRET=YOUR_SECRET_TEXT
SALT=YOUR_SALT_VALUE
MONGO_URL=YOUR_DATABASE_URL
STRIPE_SECRET_KEY=YOUR_KEY

## Run Locally
Clone the project

```bash
    git clone  https://github.com/shreyagughane/foodiehub-food-ordering
```

Install dependencies (frontend)

```bash
    cd ../frontend
    npm install
```
Install dependencies (admin)

```bash
    cd ../admin
    npm install
```
Install dependencies (backend)

```bash
    cd backend
    npm install
```
