# 🌱 GreenLoop - Sustainable Products E-Commerce Website

**GreenLoop** is a full-stack e-commerce platform for selling sustainable and eco-friendly products.  
It includes product browsing by categories, a shopping cart with quantity management, a checkout page, and a blog with articles on sustainable living. **Visite GreenLoop** :https://aakash5275.github.io/GreenLoop/

---

## ✨ Features
- **Product Catalog** – 20+ products with images, categories, and pricing.
- **Categories** – Products are grouped by type for easy browsing.
- **Shopping Cart** – Add/remove items, update quantities, view totals.
- **Checkout** – Order form with Razorpay payment gateway integration.
- **Blog** – Sustainability-related articles with images and styled content.
- **Authentication** – Login and Signup pages (auth.js for logic).
- **Responsive Design** – Works on desktop and mobile devices.

---

## 🛠️ Tech Stack
**Frontend:** HTML5, CSS3, JavaScript (Vanilla)  
**Backend:** Node.js, Express.js *(if running backend features)*  
**Database:** MongoDB *(optional for storing users/orders)*  
**Payment Gateway:** Razorpay (test mode)  
**Other:** LocalStorage for cart persistence

---

## 📂 Project Structure
```
├── about.html         # About the website
├── blog.html          # Blog page with sustainability articles
├── cart.html          # Shopping cart with quantity controls
├── checkout.html      # Checkout form with Razorpay integration
├── script.js          # Main frontend JavaScript logic
├── auth.js            # Login/Signup form handling
├── images/            # Product and blog images
├── styles/            # CSS files (if separated)
└── README.md          # Project documentation
```

---

## ⚙️ Installation & Setup

### 1️⃣ Clone the Repository
```bash
git clone https://github.com/your-username/greenloop.git
cd greenloop
```

### 2️⃣ (Optional) Backend Setup
If you want backend features like saving orders/users:
```bash
cd server
npm install
```
Create a `.env` file inside `server/`:
```
MONGO_URI=your_mongodb_connection
JWT_SECRET=your_secret
RAZORPAY_KEY_ID=your_key_id
RAZORPAY_KEY_SECRET=your_key_secret
```
Run backend:
```bash
node index.js
```

### 3️⃣ Run the Frontend
Simply open `index.html` in your browser  
*(Or use a local server like Live Server in VSCode)*

---

## 🛒 Usage
1. Browse products by category in the **Shop** section.
2. Add products to the cart.
3. Adjust quantities or remove products from the cart.
4. Click **Proceed to Checkout** and complete payment with Razorpay.
5. Read sustainability tips in the **Blog** section.

---

## 📸 Screenshots
> *(Replace `images/screenshots/` with your actual screenshot paths)*

**Homepage**
![Homepage](images/screenshots/homepage.png)

**Product Catalog**
![Products](images/screenshots/products.png)

**Cart**
![Cart](images/screenshots/cart.png)

**Checkout**
![Checkout](images/screenshots/checkout.png)

---

## 📌 Roadmap
- Add user profile & order history.
- Implement admin panel for product management.
- Enhance payment gateway features.
- Deploy on Vercel/Render.

---

## 🤝 Contributing
Contributions, issues, and feature requests are welcome!  
Feel free to fork the repository and submit a Pull Request.

---



---

**💚 Live sustainably, shop responsibly – GreenLoop**

