# 🌐 Export Facilitation Centre (EFC)

The **Export Facilitation Centre (EFC)** is a centralized, web-based platform designed to support small-scale Indian exporters, including MSMEs, artisans, and rural entrepreneurs. It streamlines the export process by enabling digital documentation, order management, vendor registration, and real-time logistics tracking through integration with India Post (Dak Ghar Niryat Kendra - DNK).

---

## 🚀 Key Features

### 👤 Admin Panel
- View, manage, approve, or deactivate users and vendors.
- Approve product listings and track inventory.
- Monitor and resolve order-related issues.
- Generate monthly performance reports and analytics.

### 🛍️ Vendor Dashboard
- Register and log in securely.
- Upload and manage product listings.
- Track orders and update delivery status.
- Access monthly sales and earnings reports.

### 🛒 User Interface
- Register, log in, and manage profile.
- Browse products and filter by categories.
- Add items to cart and complete purchases via wallet, UPI, or cards.
- Track placed orders and contact support.

---

## 🏗️ System Architecture

The system consists of four main modules:
- **Admin Panel** – Full control over vendors, products, orders, and reports.
- **Vendor Side** – Product management, order tracking, and document submission.
- **User Side** – Product browsing, order placement, and payment.
- **DNK Panel (Future Scope)** – Integration with India Post for live parcel tracking.

---

## ⚙️ Tech Stack

| Layer       | Technology                      |
|-------------|----------------------------------|
| Frontend    | HTML5, CSS3, JavaScript, Bootstrap 5 |
| Backend     | PHP 8.x with Laravel 9.x (MVC)   |
| Database    | MySQL 8.x                        |
| APIs        | REST APIs (India Post, Localhost)|
| Auth        | Laravel Breeze / Sanctum         |
| Tools       | Git, GitHub, VS Code             |

---

## 📈 Benefits

- Digitized and centralized export process.
- Real-time order tracking and notification system.
- Secure user authentication and role-based access control.
- Transparent wallet-based transactions and logs.
- Scalable architecture built with Laravel MVC.

---

## 🧪 Modules Implemented

- User Management  
- Vendor Document Verification  
- Product Catalog and Search  
- Wallet-Based Payment  
- Order Tracking with Status Updates  
- Admin & Vendor Reporting Dashboard  
- Notifications for Dispatch, Delivery, and Compliance  

---

## 📚 Future Enhancements

- Android/iOS Mobile App  
- Multi-language Support (Hindi, Marathi, Bengali)  
- AI-Based Analytics & Forecasting  
- Bulk Product Upload via CSV/Excel  
- India Post Delivery API for real-time sync  
- Chatbot and Voice Assistant for rural users  

---


## ⚙️ Local Setup & Deployment

> Follow the steps below to run this project locally.

### 🧾 Prerequisites
- PHP 8.x
- Composer
- MySQL 8+
- Node.js (for frontend assets)
- Laravel CLI
- Git

### 📦 Steps to Setup

```bash
# 1. Clone the repository
git clone https://github.com/yourusername/efc-platform.git
cd efc-platform

# 2. Install PHP dependencies
composer install

# 3. Copy .env and configure
cp .env.example .env

# 4. Generate app key
php artisan key:generate

# 5. Configure your DB in .env and run migration
php artisan migrate

# 6. Install frontend dependencies
npm install && npm run dev

# 7. Run Laravel server
php artisan serve

The application will now be available at http://localhost:8000


Future Scope
📱 Android/iOS Mobile App

🌐 Multi-language support

🤖 Chatbot and Voice Assistant

📦 Advanced Analytics & AI-based Forecasting

📁 Bulk CSV Upload for Vendors

🔄 Auto-sync with India Post Delivery API



⭐ Feel free to fork this project or raise issues to collaborate.---

Let me know if you want:
- A `.env.example` file template  
- A `screenshots/` folder structure  
- Deployment guide for **cPanel** or **Heroku**

I'll prepare it for you!


## 📄 License

This project is developed as part of the final year academic submission under the Department of Computer Science & Engineering, PRPCEM, Amravati.

---

## 👨‍💻 Developed By

**Yash Rajesh Dalvi**  
B.E. Computer Science & Engineering  
PRPCEM, Amravati (2024-25)  
Guided by: **Prof. B. V. Kasar**  
