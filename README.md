# 💧 Water Subscription Platform

A full-stack web application designed to manage monthly water purifier subscriptions with real-time device integration. Built with Node.js and React, the platform supports secure online payments via Razorpay and GSM-based device status control.

## 🚀 Features

- 🔐 User Registration & Login
- 💳 Razorpay Payment Gateway Integration
- 📦 Subscription Management Dashboard
- 🔄 Real-time Status Sync via GSM (Arduino/IoT)
- 📊 Basic Admin Overview for User Plans
- 📁 Responsive UI (Bootstrap + Custom Styling)

## 🛠️ Tech Stack

| Layer          | Technology            |
|----------------|------------------------|
| Frontend       | React, Bootstrap       |
| Backend        | Node.js, Express.js    |
| Database       | MongoDB (via Mongoose) |
| Payments       | Razorpay API           |
| IoT/Devices    | GSM Module + Arduino   |
| Deployment     | (Optional: Render/Vercel/Heroku) |

## 🧩 Folder Structure

payments2/
├── public/
├── src/
│ ├── components/
│ ├── pages/
├── server/
│ ├── controllers/
│ ├── routes/
│ ├── models/
├── README.md
├── package.json

📡 Device Integration
The platform integrates with Arduino (Uno/Nano) + GSM Module. Device status (ON/OFF) is controlled based on active subscription status pulled from the backend.

🔐 Razorpay Integration
Payments are handled securely using Razorpay Orders API. Once the payment is confirmed, the subscription is activated and reflected on the dashboard and device.

🧠 Future Enhancements
Digital Ad Board Integration for Smart Displays

SMS Alerts for Recharge Reminders

Admin Panel with Analytics and Control

Auto-renew Subscription Options

📜 License
This project is licensed under the MIT License.
