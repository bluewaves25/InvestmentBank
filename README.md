# Summit Investment Bank Project

This folder contains the complete system for Summit Investment Bank. It is divided into two main parts: the **Client** side for customers and the **Admin** side for the bank staff.

---

## 1. Client Project (`/client`)
This is the main website that customers use.
*   **Backend**: The brain of the app. It handles security and saves data like user profiles and bank accounts.
*   **Frontend**: The actual website. This is where customers log in, see their balance, and send money.

**How to run it:**
1. Open the `client/backend` folder and start it using `npm start`.
2. Open the `client/frontend` folder and start it using `npm run dev`.

---

## 2. Admin Project (`/admin`)
This is the private dashboard used by the bank team to manage everything.
*   **Backend**: Handles special admin tasks, such as approving new users or managing wallets.
*   **Frontend**: The control panel for the staff. This is where they view all customers and manage the bank's settings.

**How to run it:**
1. Open the `admin/backend` folder and start it using `npm start`.
2. Open the `admin/frontend` folder and start it using `npm run dev`.

---

## Simple Setup Guide
- **Passwords & Settings**: Each part has a `.env` file where secret settings (like the database link) are stored.
- **Tools Needed**: You need to have **Node.js** installed on your computer to run these apps.
