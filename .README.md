# E-Store Project

## Introduction

Welcome to the E-Store project! This is a comprehensive e-commerce platform built with modern technologies to provide a seamless shopping experience. Whether you're a developer looking to understand the inner workings of an e-commerce site or a business owner wanting to launch your online store, this project has you covered. Dive in to explore the features and get started with your own e-commerce journey.

## Features

- 📦 MongoDB & Redis Integration
- 💳 Stripe Payment Setup
- 🔐 Robust Authentication System
- 🔑 JWT with Refresh/Access Tokens
- 📝 User Signup & Login
- 🛒 E-Commerce Core
- 📦 Product & Category Management
- 🛍️ Shopping Cart Functionality
- 💰 Checkout with Stripe
- 🏷️ Coupon Code System
- 👑 Admin Dashboard
- 📊 Sales Analytics
- 🎨 Design with Tailwind
- 🛒 Cart & Checkout Process
- 🔒 Security
- 🛡️ Data Protection
- 🚀 Caching with Redis

## Setup `.env` File

Create a `.env` file in the root directory of your project and add the following environment variables:

```env
PORT=5000
MONGO_URI=your_mongo_uri

UPSTASH_REDIS_URL=your_redis_url

ACCESS_TOKEN_SECRET=your_access_token_secret
REFRESH_TOKEN_SECRET=your_refresh_token_secret

CLOUDINARY_CLOUD_NAME=your_cloud_name
CLOUDINARY_API_KEY=your_api_key
CLOUDINARY_API_SECRET=your_api_secret

STRIPE_SECRET_KEY=your_stripe_secret_key
CLIENT_URL=http://localhost:5173
NODE_ENV=development
```

## Setup and Run the App

### Prerequisites

Make sure you have the following installed on your machine:

- **Node.js** (v14 or higher)
- **npm** (v6 or higher)

### Installation

1. **Clone the repository:**

   ```sh
   git clone https://github.com/yourusername/estore.git
   cd estore
   ```

2. **Install dependencies:**

   ```sh
   npm install
   ```

3. **Set up the environment variables:**

   ```sh
   cp .env.example .env
   ```

   Edit the `.env` file with your configuration.

### Running the App

1. **Build the app:**

   ```sh
   npm run build
   ```

2. **Start the app:**

   ```sh
   npm run start
   ```

3. **Open your browser and navigate to:**

   ```
   http://localhost:5000
   ```

You should now see the E-Store application running locally.

---

Feel free to explore the app and customize it to suit your needs. If you encounter any issues or have questions, please open an issue on the [GitHub repository](https://github.com/yourusername/estore).

Happy coding!
