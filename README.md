# 📞 Contact Management API  

A **RESTful API** built using **Node.js, Express.js, and MongoDB** that allows users to register, log in, and manage their personal contacts securely.  
This project was developed during my internship at **Main Flow Services and Technology**.  

---

## 🚀 Features  
- 🔐 **User Authentication & Authorization** (JWT-based)  
- 🔑 **Password Encryption** using bcrypt.js  
- 📒 **CRUD Operations** for Contacts (Create, Read, Update, Delete)  
- 🛡 **Protected Routes** with Middleware Authentication  
- 🗄 **MongoDB Integration** with Mongoose Models  
- ⚙️ **Environment Variable Setup** with dotenv  

---

## 🛠 Tech Stack  
- **Backend:** Node.js, Express.js  
- **Database:** MongoDB (Mongoose ODM)  
- **Authentication:** JWT (JSON Web Token), bcrypt.js  
- **Other Tools:** dotenv, body-parser  

---

## 📂 Project Structure  
```
CONTACT_API/
│── Controllers/ # Business logic for Users & Contacts
│ ├── contact.js
│ ├── user.js
│
│── Middlewares/ # Authentication middleware
│ ├── Auth.js
│
│── Models/ # Database models
│ ├── Contact.js
│ ├── User.js
│
│── Routes/ # API routes
│ ├── contact.js
│ ├── user.js
│
│── server.js # Entry point of the application
│── package.json # Dependencies
│── .env # Environment variables

```


---

## ⚡ API Endpoints  

### 👤 User Routes (`/api/user`)
- `POST /register` → Register new user  
- `POST /login` → User login & get JWT token  

### 📒 Contact Routes (`/api/contact`)
- `GET /` → Get all contacts (Protected)  
- `POST /` → Create a new contact (Protected)  
- `PUT /:id` → Update a contact by ID (Protected)  
- `DELETE /:id` → Delete a contact by ID (Protected)  

---

## 🔑 Authentication  
- The API uses **JWT Tokens** for authentication.  
- Send token in the request header:  

#📌 Future Improvements

Add pagination for contacts

Implement role-based access (admin, user)

Add profile management for users

## ✍ Author  
Developed by **Rishii Jadhav**  
💼 During Internship at *Main Flow Services and Technology*  

🌐 Connect with me:  
- [LinkedIn](http://www.linkedin.com/in/rushikeshjadhav2004)  
- [Instagram](https://www.instagram.com/thvrishiii7?igsh=MTVkczFzY20wY2xyZA==)  
