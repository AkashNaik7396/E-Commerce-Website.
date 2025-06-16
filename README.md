E-Commerce Website

📌 Project Description
This is a full-stack E-Commerce web application designed for showcasing and selling products online. The platform allows users to browse items, add them to the cart, place orders, and make payments (demo). Admin users can manage products, categories, and orders.

🌐 Features
🧑‍💼 User Side:

🛍️ View product listings by category
🔍 Search and filter products
🛒 Add to cart and wishlist
📦 Checkout and place orders
👤 Login/Signup functionality
📄 Order history and tracking
🛠️ Admin Side:

📤 Add/edit/delete products
📚 Manage categories and inventory
📦 View and update orders
📊 Dashboard with statistics
💻 Tech Stack
Frontend	Backend	Database	Others
HTML, CSS, JavaScript	Node.js / Express	MongoDB / MySQL	Git, GitHub, Postman
React.js (optional)	REST APIs	Firebase (optional)	Razorpay/Stripe (for payments)
📁 Project Structure
ecommerce-website/
├── client/             # Frontend code
│   ├── public/
│   └── src/
├── server/             # Backend code (Express)
│   ├── controllers/
│   ├── routes/
│   ├── models/
│   └── app.js
├── README.md
├── package.json
└── .gitignore
🧪 Installation & Setup
git clone https://github.com/akashnaik7396/ecommer<img width="1120" alt="Screenshot 2025-06-16 at 10 55 08 PM" src="https://github.com/user-attachments/assets/4492c036-8244-4d40-bd12-c6f4cca3bd2a" />
ce-website.git
cd ecommerce-website

# For frontend
cd client
npm install
npm start<img width="1257" alt="Screenshot 2025-06-16 at 10 54 56 PM" src="https://github.com/user-attachments/assets/b0490399-56e2-4b38-81a0-e5969f0669b3" />


# For backend
cd server
npm install
npm run dev


🔐 Authentication
JWT-based authentication for logi<img width="1120" alt="Screenshot 2025-06-16 at 10 55 08 PM" src="https://github.com/user-attachments/assets/2ce7f3f1-1017-4408-9144-0a20857653ba" />
<img width="1230" alt="Screenshot 2025-06-16 at 10 55 19 PM" src="https://github.com/user-attachments/assets/bb04e4a3-b27e-40af-81d4-de1535b6adf6" />
<img width="1280" alt="Screenshot 2025-06-16 at 10 55 29 PM" src="https://github.com/user-attachments/assets/8c8d6244-67a9-430b-9500-8b809d469767" />
n/signup
Admin and user roles are handled separately


💳 Payment Integration
Razorpay / Stripe integration for test payments
Checkout page with summary and payment modal


