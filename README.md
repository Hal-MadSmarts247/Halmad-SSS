# Hal-Mad Smart Synergy - Modern eCommerce Platform

A high-end, responsive minimalist eCommerce platform built with React, Tailwind CSS, and Google Gemini AI.

## 🚀 Core Features

- **Personalized Shopping with AI**: Integrated Google Gemini 2.5 Flash for expert product recommendations and personal shopping advice.
- **Dynamic Catalogue**: Full product management (CRUD) within the Admin Dashboard.
- **End-to-End Checkout**: A seamless multi-step checkout experience including simulated secure payment processing.
- **Robust State Management**: Global context for handling User Auth, Cart logic, Wishlist, and Order histories with localStorage persistence.
- **Admin Command Center**: Dedicated portal for inventory monitoring and order fulfillment management.
- **User Dashboard**: Personalized profile for users to track order statuses (Pending, Shipped, Delivered) and manage their account.

## 🛠️ Technical Stack

- **Framework**: React 18+
- **Styling**: Tailwind CSS (Minimalist utility-first design)
- **Icons**: Lucide React
- **Routing**: React Router 7+
- **AI Engine**: Google GenAI SDK (Gemini API)
- **Persistence**: Browser LocalStorage (Simulated database)

## 📁 Project Structure

- `/components`: Reusable UI elements (Navbar, Footer, Product Cards).
- `/pages`: Core views (Home, Shop, Admin, Auth, Profile, Cart, Checkout).
- `/context`: Global state management for data synchronization.
- `/services`: Third-party API integrations (Gemini AI).
- `/types`: Comprehensive TypeScript interfaces for domain models.

## 🔧 Installation & Setup

1. Ensure the `process.env.API_KEY` is configured for Gemini AI features.
2. The application uses ESM imports; no additional build step is required for browser-based modules.
3. Access the Admin Dashboard via `/admin` (Default mock credentials: any email containing 'admin').

## 🎨 Design Philosophy

Hal-Mad Smart Synergy is designed around the concept of "Digital Zen." We use ample negative space, monochromatic palettes with functional color accents, and smooth transitions to ensure the user's focus remains entirely on the high-quality product imagery.