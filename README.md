# 🚀 ImageIn AI

**ImageIn AI** is an **AI-powered image editing tool** that enables users to **restore, edit, and modify logos** with advanced AI-driven features. It’s designed to help designers, businesses, and developers quickly enhance branding elements.

This project integrates **Next.js** for the frontend, **Clerk** for authentication (with webhook support), **Cloudinary AI** for image processing, **MongoDB** for database storage, **Stripe** for handling payments and **Tailwind CSS** for styling.

---

## ✨ Features

### 🔹 **AI-Powered Image Enhancements**

- **Logo Image Restore** – Revive and enhance low-resolution or damaged logos.
- **Logo Generative Fill** – Expand and complete logos using AI.
- **Logo Object Remove** – Remove unwanted elements from logos seamlessly.
- **Logo Object Recolor** – Modify logo colors dynamically with AI.
- **Logo Background Remove** – Extract logos from backgrounds automatically.

### 🔹 **User & Payment Features**

- **Clerk Authentication** – Secure login & sign-up for users.
- **Stripe Payments** – Users can buy credits for AI image processing.

### 🔹 **Backend & Data Handling**

- **MongoDB** – Stores user data, processed images, and purchase history.
- **Cloudinary AI** – Handles AI-based image transformations & storage.

---

## 🚀 Installation & Setup

### **1. Clone the Repository**

```sh
git clone https://github.com/yourusername/imagein-ai.git
cd imagein-ai
```

### **2. Install Dependencies**

```sh
npm install
```

### **3. Set Up Environment Variables**

Create a `.env.local` file and add the following:

```env
NEXT_PUBLIC_CLERK_PUBLISHABLE_KEY=your_clerk_publishable_key
CLERK_SECRET_KEY=your_clerk_secret_key
NEXT_PUBLIC_CLOUDINARY_CLOUD_NAME=your_cloudinary_cloud_name
NEXT_PUBLIC_STRIPE_PUBLIC_KEY=your_stripe_public_key
STRIPE_SECRET_KEY=your_stripe_secret_key
MONGODB_URI=your_mongodb_connection_uri
```

### **4. Run the Development Server**

```sh
npm run dev
```

Your app will be available at **`http://localhost:3000`**.

---

## 🙌 Acknowledgments

This project was inspired by **JavaScript Mastery**, which influenced its architecture and development.

Special thanks to **Clerk, Cloudinary, Stripe, and MongoDB** for their powerful integrations.
