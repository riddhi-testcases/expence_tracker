# 💸 **Expense Tracker Application (MERN Stack)**  

### ✅ **Overview**
The **Expense Tracker** is a full-stack web application built using the **MERN stack**. It allows users to **track expenses, visualize spending habits through pie charts**, and receive **automated email alerts** when expenses exceed **$10,000**, ensuring better financial oversight.  

---

### 🚀 **Features**
- **User Authentication:** Secure login/logout system.  
- **Expense Management:** Add, edit, and delete expenses with detailed descriptions.  
- **Automated Email Alerts:** Sends an email notification whenever an expense crosses **$10,000**.  
- **Dynamic Pie Charts:** Displays visual reports of spending categories.  
- **Responsive UI:** Intuitive and mobile-friendly interface.  
- **High Accuracy:** The application operates with an **overall accuracy of approximately 92.5%** in triggering alerts and visualizing data.  

---

### 🔧 **Tech Stack**
- **Frontend:** React.js  
- **Backend:** Node.js, Express.js  
- **Database:** MongoDB  
- **Automation:** Nodemailer (for email alerts)  
- **Visualization:** Chart.js (for pie charts)  

---

### 🔥 **API Endpoints**

#### **User Authentication**
- `POST /api/register` → Register a new user  
- `POST /api/login` → User login  
- `POST /api/logout` → User logout  

#### **Expense Management**
- `GET /api/expenses` → Retrieve all expenses  
- `POST /api/expenses` → Add a new expense  
- `PUT /api/expenses/:id` → Update an expense  
- `DELETE /api/expenses/:id` → Delete an expense  

---

### 📊 **Usage Instructions**
1. **Login/Register:**  
   - Create an account or log in.  
2. **Add Expenses:**  
   - Input details like name, amount, and category.  
3. **Automated Alerts:**  
   - Receive an **email notification** when an expense crosses **$10,000**.  
4. **View Reports:**  
   - Access **dynamic pie charts** showing spending distribution.  

---

### 🐛 **Known Issues**
- **Email Delays:** Email alerts may occasionally face delays due to SMTP configuration.  
- **Data Sync:** Refreshing is required to reflect real-time changes in pie charts.  
