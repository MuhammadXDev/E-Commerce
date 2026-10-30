# Aura E-Commerce Marketplace - Production Ready Platform

Aura is a modern, scalable, and premium full-stack e-commerce marketplace built with the latest technologies. It supports customers, sellers, and administrators with a high-end UI/UX.

## 🚀 Tech Stack

### Frontend
- **Framework**: Next.js 14 (App Router)
- **Styling**: Tailwind CSS (Premium Glassmorphism Design)
- **Animations**: Framer Motion
- **Icons**: Lucide React
- **State Management**: Redux Toolkit (Prepared)
- **Authentication**: NextAuth.js (JWT Strategy)

### Backend
- **Framework**: Next.js API Routes (Serverless ready)
- **Database**: MongoDB (via Mongoose)
- **Security**: Bcrypt.js (Password hashing), JWT (Auth sessions)
- **Payment**: Stripe Integration (Structure Ready)

---

## 🏗️ Folder Structure

```text
/app
  /api          # RESTful API Endpoints (Auth, Products, Orders)
  /admin        # Admin Dashboard Pages
  /shop         # Product Listing & Navigation
  /cart         # Shopping Cart Experience
  /register     # User Registration
  /login        # Authentication UI
  layout.tsx    # Root layout with SEO & Global Components
  page.tsx      # Premium Landing Page
/components
  /layout       # Shared Layout (Header, Footer)
  /home         # Home Page specific sections
  /product      # Reusable Product components
  /admin        # Admin Dashboard components
/lib
  db.ts         # MongoDB connection utility
/models
  User.ts       # Mongoose User Schema (RBAC)
  Product.ts    # Mongoose Product Schema (Reviews & Search)
  Order.ts      # Mongoose Order Schema (Payment & Shipping)
/public         # Static assets & images
```

---

## 🛠️ Setup Instructions

### 1. Prerequisites
- Node.js (v18 or higher)
- MongoDB Database (Atlas or Local)
- Stripe Account (for payments)

### 2. Environment Variables
Create a `.env.local` file in the root directory:
```env
MONGODB_URI=your_mongodb_connection_string
NEXTAUTH_SECRET=your_random_secret_string
NEXTAUTH_URL=http://localhost:3000

# Optional integrations
STRIPE_SECRET_KEY=your_stripe_secret
CLOUDINARY_URL=your_cloudinary_url
```

### 3. Installation
```bash
npm install
```

### 4. Running the Application
```bash
npm run dev
```
Open [http://localhost:3000](http://localhost:3000) to view the application.

---

## 🛡️ Security & Performance
- **Password Protection**: Multi-round Bcrypt hashing.
- **RBAC**: Middleware-based role validation for Admin and Seller routes.
- **SEO**: Dynamic metadata and semantic HTML5 for search engine visibility.
- **Optimized Assets**: Image optimization and code splitting via Next.js.
- **Input Validation**: Mongoose schema-level validation and API-level checks.

## 📈 Marketplace Features
- **Dynamic Search**: Real-time product filtering and search indexing.
- **Seller System**: Dedicated structure for seller product management.
- **Admin Insights**: Analytics dashboard with revenue tracking and order management.
- **Responsive Design**: Fully mobile-optimized fluid layouts.
# E-Commerce
