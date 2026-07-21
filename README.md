# EZape

A fully functional online store featuring product listings, user authentication, and integrated payments.

## Overview

EZape is an e-commerce platform that allows users to browse and search products, manage a shopping cart, and complete secure checkout via Stripe. Admins can manage inventory through a dedicated admin panel.

## Tech Stack

- **Frontend:** React.js / Next.js
- **Backend:** Node.js
- **Database:** MongoDB / MySQL
- **Payments:** Razorpay API

## Features

- 🔍 Product search and filters
- 🛒 Shopping cart and checkout
- 🔐 User authentication (sign up, login, sessions)
- 📦 Admin panel for inventory management
- 💳 Secure payment processing via Razorpay

## Getting Started

### Prerequisites

- Node.js (v18 or higher recommended)
- npm or yarn
- MongoDB or MySQL instance (local or hosted)
- A Stripe account with API keys

### Installation

1. Clone the repository
```bash
   git clone https://github.com/your-username/ezape.git
   cd ezape
```

2. Install dependencies
```bash
   npm install
```

3. Configure environment variables

   Create a `.env` file in the root directory:
```env
   # Database
   DATABASE_URL=your_database_connection_string

   # Authentication
   JWT_SECRET=your_jwt_secret

   # razorpay
   RAZORPAY_PUBLIC_KEY=your_stripe_public_key
   RAZORPAY_SECRET_KEY=your_stripe_secret_key

   # App
   NEXT_PUBLIC_APP_URL=http://localhost:3000
```

4. Run the development server
```bash
   npm run dev
```

5. Open [http://localhost:3000](http://localhost:3000) in your browser

## Project Structure
