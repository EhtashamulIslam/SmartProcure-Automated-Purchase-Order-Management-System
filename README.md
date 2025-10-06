# SmartProcure: Automated Purchase Order Management System

## 📘 Overview
**SmartProcure** is a Java-based desktop application designed for **Omega Wholesale Sdn Bhd (OWSB)** to automate the management of purchase orders, suppliers, inventory, and financial transactions.  
The system leverages **Object-Oriented Programming (OOP)** principles to create a scalable and modular architecture that enhances operational efficiency, reduces manual errors, and streamlines procurement workflows.

---

## 🧩 Features by Role

### 👨‍💼 **Admin**
- Role-based access management  
- Add/Edit/Delete users  
- Manage authentication through `users.txt`  
- Encapsulated data handling with `User` class and interface implementation  
- GUI: Admin Dashboard, User Registration Form

### 🏷️ **Sales Manager**
- Record daily sales  
- Create and manage purchase requisitions  
- View and filter inventory data  
- Generate sales reports  
- Manage supplier information  

### 🧾 **Purchase Manager**
- Review and approve purchase requisitions  
- Generate and manage purchase orders  
- View suppliers and track item availability  
- Update order statuses  

### 📦 **Inventory Manager**
- Add/Edit/Delete items in inventory  
- Monitor stock levels and reorder points  
- Generate stock and item reports  
- Manage supplier data  

### 💰 **Finance Manager**
- Process supplier payments  
- View and verify purchase orders and requisitions  
- Generate financial reports  

---

## ⚙️ **System Architecture**

### Key Classes
| Class | Description |
|-------|--------------|
| `User` *(abstract)* | Base class for all user roles (Admin, SalesManager, etc.) |
| `Admin` | Extends `User`, implements `IUserManagement` for CRUD operations |
| `LoginForm` | Handles authentication logic and GUI |
| `AdminDashboard` | GUI for user management |
| `Purchase_Order` | Manages purchase order creation and updates |
| `Supplier` | Handles supplier data |
| `Item_SM` | Manages item information, stock, and thresholds |

### Packages
