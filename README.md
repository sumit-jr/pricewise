# 💰 Pricewise – Amazon Price Tracker

A **full-stack web application** built with **Next.js, TailwindCSS, MongoDB, and Node.js**, that tracks product prices on Amazon and notifies users of price drops.  
The app scrapes product details, stores them in MongoDB, and uses scheduled cron jobs + email notifications to keep users updated.  

---

## 🚀 Features

- 🔍 **Amazon Product Scraping** – Fetches product details (title, image, price, etc.).  
- 💾 **MongoDB Database** – Stores product information and user subscriptions.  
- ⏰ **Cron Jobs** – Automated background tasks for checking price changes.  
- 📧 **Email Notifications** – Alerts users when product prices drop.  
- 🎨 **TailwindCSS Styling** – Responsive, modern UI design.  
- ⚡ **Next.js (App Router)** – Fast, server-rendered React application.  

---

## 📂 Project Structure

```text
├── app/                  # Next.js App Router pages
├── components/           # UI Components
├── lib/                  # Database and scraping utilities
├── public/               # Static assets
├── types/                # TypeScript type definitions
├── .env                  # Environment variables
├── next.config.js        # Next.js configuration
├── package.json          # Dependencies
├── tailwind.config.ts    # TailwindCSS configuration
├── tsconfig.json         # TypeScript configuration
└── README.md             # Documentation
```
## ⚡ Installation

Follow these steps to install and run the project locally:

### Clone the repository
```bash
git clone https://github.com/sumit-jr/pricewise.git
cd pricewise
```

## ⚡ Installation Steps

1. **Ensure you have Node.js installed**  
   If not, download it from the [Node.js official site](https://nodejs.org/en/download/).

2. **Install dependencies**
   ```bash
   npm install
   ```

## 🖋 Install Required Fonts
The project uses **Inter** and **Space Grotesk** fonts, available on [Google Fonts](https://fonts.google.com/).

---

## ⚙️ Set Up Environment Variables
Create a `.env` file in the root directory and add your MongoDB connection string:

```env
MONGODB_URI=your_mongodb_uri
```

## ⚡ Start the Server
```bash
npm run start
```

## 🛠 Tech Stack

- **Frontend:** Next.js, React, TailwindCSS  
- **Backend:** Node.js, MongoDB  
- **Deployment:** Vercel / Netlify (optional)  
- **Other Tools:** Cron Jobs, EmailJS (or Nodemailer)  

---

## 📜 License

This project is licensed under the **MIT License**.
