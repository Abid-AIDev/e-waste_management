# 🚀 QR & E-Waste Management System  

Welcome to the **QR & E-Waste Management System**, an integrated platform designed for **QR code-based tracking** and **efficient e-waste repair management**. This repository contains **three main components**, each serving a unique purpose.  

---

## 📂 Project Structure  

### 1️⃣ **QR MVP** 🏷️  
- A **Node.js** application that allows users to **generate QR codes** and **store details in a CSV file**.  
- Users can also **scan QR codes** to retrieve and display stored data.  
- Helps in tracking assets and managing inventory efficiently.  

### 2️⃣ **WMS 4 - E-Waste Generator Dashboard** 🔧  
- A **React-based dashboard** for entities generating **e-waste**.  
- Enables businesses to **track repair shops**, **request repairs**, and manage e-waste disposal.  
- Includes a **login system**  
  - **Username**: `abid`  
  - **Password**: `abid`  
- After login, it **redirects to the Centre Dashboard** for further processing.  

### 3️⃣ **Centre - Repair Center Dashboard** 🏭  
- A **React-based dashboard** used by **repair centers** to **manage repair requests, sales, and inventory**.  
- Helps track **incoming e-waste**, accept/decline repair requests, and optimize workflow.  
- **Login Credentials:**  
  - **Username**: `abin`  
  - **Password**: `abin`  

### 4️⃣ **Machine Learning Module (PY Folder in WMS 4)** 🤖  
- A **Flask-based web app** that performs **Linear Regression, Decision Tree, and Random Forest analysis**.  
- Trained on **CSV data** to generate predictive graphs.  
- Run using:  
  ```bash
  cd PY
  python app.py
  ```  

---

## 🚀 Getting Started  

### **1️⃣ Running the QR MVP (QR Code Generator & Scanner)**  
```bash
cd QR MVP
npm install
node server.js  # Start the Node.js server
```

### **2️⃣ Running the WMS 4 & Centre Dashboards**  
Install dependencies and start the servers:  
```bash
cd WMS 4
npm install
npm run dev  # Starts WMS 4 Dashboard

cd ../Centre
npm install
npm run dev  # Starts Centre Dashboard
```

### **3️⃣ Running the Machine Learning Flask App**  
```bash
cd WMS 4/PY
python app.py  # Starts the ML web server
```

---

## 🎯 Key Features  

✅ **QR MVP**: Generate & scan QR codes with CSV data storage.  
✅ **WMS 4 Dashboard**: Track e-waste, request repairs, and manage waste.  
✅ **Centre Dashboard**: Manage repair requests and sales analytics.  
✅ **Flask ML App**: Perform predictive analytics using machine learning models.  

---

Happy Coding! 😊🎯  
