# Store Rating Management Application

## 🚀 Overview
A web application that enables users to submit and manage ratings for stores registered on the platform. It features role-based access for different types of users.

## 🛠️ Technology Stack

- **Backend**: ExpressJs / Loopback / NestJs (Choose one)
- **Database**: PostgreSQL / MySQL
- **Frontend**: ReactJs

## 🎯 Functional Requirements

### 🌟 User Roles

- **System Administrator**
- **Normal User**
- **Store Owner**

---

## 🔐 Single Authentication System
- A unified login and registration system for all users.

## 🔑 User Roles & Functionalities

### **System Administrator**
- Add new stores, normal users, and admin users.
- Dashboard displaying:
  - Total number of users
  - Total number of stores
  - Total number of submitted ratings
- Manage users (create, list, filter, view details).
- Manage stores (list with details).
- Logout functionality.

### **Normal User**
- Signup and login functionality.
- View and search store listings by name or address.
- Submit and modify store ratings (1-5).
- Update their password after login.
- Logout functionality.

### **Store Owner**
- Login and update their password.
- Dashboard to view:
  - List of users who rated their store.
  - Average rating of their store.
- Logout functionality.

## ✔️ Form Validations
- **Name**: Min 20 characters, Max 60 characters
- **Address**: Max 400 characters
- **Password**: 8-16 characters, at least one uppercase letter, one special character
- **Email**: Standard email format validation

## 🔍 Additional Features
- Sorting (ascending/descending) in tables by fields like Name, Email, etc.
- Clean and best-practice-oriented database schema.

## 🚀 Getting Started

### **1. Backend Setup**

Navigate to your backend directory:

```sh
cd server
npm install
```

Configure your database connection in `.env` file:

```env
DATABASE_URL=postgresql://username:password@localhost:5432/your-database-name
```

Then start backend:

```sh
npm run dev
```

Backend runs at `http://localhost:3000`

```
admin@example.com
Admin123!
```

## ⚠️ **Important**
- Ensure PostgreSQL/MySQL is running.
- Create your database clearly and set connection URL in your backend `.env` clearly.

Example `.env`:
```env
DATABASE_URL=postgresql://postgres:yourpassword@localhost:5432/your-database-name
```

---



## 📬 Contributing

Feel free to contribute or raise issues through pull requests.

## 📝 License

Specify clearly here if needed (MIT, etc.)

---

Made with ❤️ by [Manish](https://github.com/manish-87)
```

![Screenshot 2025-03-15 073346](https://github.com/user-attachments/assets/87efea3c-c57a-4802-9cc1-091f15d60d8f)

![Screenshot 2025-03-15 073332](https://github.com/user-attachments/assets/b84cd6ce-ece8-4751-90a9-d39e74038974)

![Screenshot 2025-03-15 073355](https://github.com/user-attachments/assets/3b5d07aa-1b48-4325-82cf-3b42487e0fa3)

![Screenshot 2025-03-15 073407](https://github.com/user-attachments/assets/577dfb02-5db9-4109-b168-c5e0a43692a3)

![Screenshot 2025-03-15 073416](https://github.com/user-attachments/assets/0a97bd6f-b8b8-485f-a549-fb961f73e85d)

![Screenshot 2025-03-15 073446](https://github.com/user-attachments/assets/494f03aa-f3f5-472c-9a2c-5c2020abbc07)

![Screenshot 2025-03-15 073630](https://github.com/user-attachments/assets/8c4793ef-e10f-4484-bb80-12845946bc07)

![Screenshot 2025-03-15 073644](https://github.com/user-attachments/assets/a48d5d20-c371-47dd-ae3d-4f00acc6ae50)

![Screenshot 2025-03-15 073654](https://github.com/user-attachments/assets/9d67b348-5ec3-4947-9ce9-303d8b27dd2f)

![Screenshot 2025-03-15 073704](https://github.com/user-attachments/assets/1dfaba5c-cede-4caf-9988-322f8d4cc6f8)

![Screenshot 2025-03-15 073711](https://github.com/user-attachments/assets/66656633-6b8e-4ea3-96a2-ab94a22edc04)
