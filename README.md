# 🧪 E-commerce API Automation Suite (Postman + Newman)

This project automates key E-commerce API operations using **Postman** and runs them through **Newman (CLI)**.

## 🔧 Tech Stack

- Postman
- Newman
- JavaScript (optional for tests)
- JSON

## 📦 APIs Covered

✅ GET `/products` – Fetch all products  
✅ POST `/products` – Create new product  
✅ GET `/products/1` – Fetch single product  
✅ PUT `/products/7` – Update product  
✅ DELETE `/products/6` – Delete product  

## 🚀 How to Run

1. Install Newman globally (if not already):
npm install -g newman

Run the collection:
newman run ecommerce-tests.json

📄 Sample Output
All requests return 200 OK and run successfully.

👩‍💻 Author
KavyaSri Singam
📧 kadambari1102000@gmail.com
💼 QA Automation Engineer