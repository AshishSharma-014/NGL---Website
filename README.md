# 🛋️ The Smart Catalog (Digital Showroom)

A modern, lightweight, and responsive **Digital Catalog Website** designed to help local furniture retailers digitize their inventory. This project bridges the gap between physical retail and digital browsing, allowing customers to view products, check sizes, and filter by price from the comfort of their homes.

## 🚀 Project Overview

* **Goal:** Replace the need for physical store visits for browsing.
* **Architecture:** Built entirely with **Vanilla JavaScript** to prioritize speed and performance on slow networks.
* **Data Management:** Uses the **LocalStorage API** to act as a client-side database, allowing a fully functional Admin Panel without a backend server (MVP Phase).

## ✨ Key Features

### 🛒 Customer Facing
* **Dynamic Product Grid:** Real-time filtering by **Category** (Bed, Sofa, etc.), **Price Range**, and **Size** without page reloads.
* **Smart Search:** DOM manipulation ensures instant results.
* **Gallery Modal:** A custom popup ("Hidden Frame" architecture) allowing users to view product thumbnails and details without leaving the page.
* **Responsive Design:** Optimized for Mobile, Tablets, and 4K Smartboards.
* **Direct Inquiry:** Integrated Contact Form (via Web3Forms) and WhatsApp ordering.

### 🔐 Admin Dashboard
* **Secure Login:** Password-protected dashboard for the business owner.
* **Inventory Management:** Add, Edit, and Delete products instantly.
* **Live Updates:** Changes made in the Admin Panel reflect immediately on the main website using LocalStorage.
* **Dashboard Stats:** Visual counters for total inventory and categories.

## 🛠️ Tech Stack

* **Frontend:** HTML5, CSS3 (Grid & Flexbox)
* **Logic:** Vanilla JavaScript (ES6+)
* **Storage:** Browser LocalStorage API
* **Animations:** AOS (Animate On Scroll) Library
* **Icons:** FontAwesome

## 📸 How to Use

1.  **Clone the repository:**
    ```bash
    git clone [https://github.com/AshishSharma-014/NGL---Website.git)
    ```
2.  **Open the Website:**
    * Open `index.html` to view the Customer Catalog.
3.  **Access Admin Panel:**
    * Open `admin.html`.
    * **Username:** `admin`
    * **Password:** `admin`
4.  **Add Products:**
    * Go to "Add Product" in the dashboard, fill in details, and see them appear live on `products.html`.

## 🔮 Future Roadmap

* [ ] **React Migration:** Converting the codebase to React.js/Next.js for scalability.
* [ ] **Cloud Database:** Moving from LocalStorage to **Firebase** for global data syncing.
* [ ] **AI Features:** Implementing an AI recommendation engine for related products.
* [ ] **Payments:** Integrating Razorpay/Stripe for full e-commerce checkout.

## 👨‍💻 Author

**[Ashish Kumar Sharma]**
* [https://www.linkedin.com/in/ashishkrsharma001/]
---
*Note: This project is an MVP (Minimum Viable Product) demonstrating advanced DOM manipulation and state management using Vanilla JS.*
