# Project Setup & Run Guide

## How to Run This Project


---

## Prerequisites

- [Node.js](https://nodejs.org/en/download/) (Install if not already installed)
- MongoDB Atlas Account
- Cloudinary Account (For file storage)
- Stripe (Optional, for payments)
- Razorpay (Optional, for payments)

---

## Backend Setup

1. Open the project folder in VS Code.

2. Open the integrated terminal:

   - Right-click on the `backend` folder and select **"Open in Integrated Terminal"**.

3. Install dependencies:

   ```sh
   npm install

-4.Setup Cloudinary for file storage:
-Create an account on Cloudinary
-Go to Dashboard and copy:
-Cloud Name
-API Key
-Secret Key
-Paste them into the backend/.env file.
-5. Setup MongoDB Atlas:
-Sign up on MongoDB Atlas
-Create a new project and database (Select M0 & Your Region)
-Setup a Username & Password (Avoid @ in the password)
-Whitelist IP 0.0.0.0/0
-Click Connect > Compass Option > Copy Connection String
-Paste it in the backend/.env file (Replace <password> with your set password)
-6. (Optional) Setup Stripe:
-Create an account on Stripe
-Copy Secret Key and paste it in backend/.env
-7. (Optional) Setup Razorpay:
-Create an account on Razorpay
-Copy Key ID and Secret Key, then paste them into backend/.env

-8. Run the backend:

   ```sh
   npm run server

## Frontend Setup

-Open the project folder in VS Code.
-Open the integrated terminal:
-Right-click on the frontend folder and select "Open in Integrated Terminal".
   ```sh
   npm install
   ```sh
   npm run dev

## Admin Panel Setup
-Open the project folder in VS Code.
-Open the integrated terminal:
-Right-click on the admin folder and select "Open in Integrated Terminal".
   ```sh
   npm install
   ```sh
   npm run dev






