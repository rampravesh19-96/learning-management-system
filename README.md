# How to Setup & Run this Project

## 🔗 Important Links

- [Install Node.js](https://nodejs.org/en/download/) (Ignore if already installed)
- [MongoDB Atlas](https://www.mongodb.com/cloud/atlas/register)
- [Cloudinary](https://cloudinary.com/users/register_free)
- [Clerk](https://clerk.com/)
- [Stripe](https://dashboard.stripe.com/login)
- [Vercel](https://vercel.com/)

---

## 🛠️ Setup Instructions

### ⚙️ Server Setup (Run First)

1. Open the project folder in **VS Code**.
2. Setup MongoDB & obtain your `MongoURI` from [MongoDB Atlas](https://www.mongodb.com/cloud/atlas/register).
3. Setup your image storage on [Cloudinary](https://cloudinary.com/users/register_free).
4. Setup user authentication with [Clerk](https://clerk.com/) and configure **Clerk Webhooks**.
5. Setup payments with [Stripe](https://dashboard.stripe.com/login).
6. Push the project to GitHub and deploy the backend to [Vercel](https://vercel.com/) to get your backend URL.
7. Add the backend URL to **Clerk Webhooks** and **Stripe Webhook** configurations.

> ⚠️ Make sure the backend is deployed and running **before running the client**.

---

### 💻 Client Setup

1. Open the client folder in your terminal.
2. Install dependencies using the following command:
   ```bash
   npm install
