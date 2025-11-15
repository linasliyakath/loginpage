# 🚀 Node.js Authentication System (Admin & User Dashboard)

This project is a **Node.js + Express + MongoDB** based authentication system that supports both **User** and **Admin** roles.  
It includes features like **registration, login, session management, role-based access control**, and **user account management** (enable/disable by admin).

---

## ⚙️ Features

✅ User Registration (with password hashing using **bcrypt**)  
✅ User Login (with **JWT** and **Sessions**)  
✅ Role-based Access (User/Admin)  
✅ Admin Dashboard to **enable/disable users**  
✅ Session & Cookie Management  
✅ Secure authentication with **bcrypt** 
✅ EJS Templating for frontend pages  

---

## 🧠 Tech Stack

| Component | Technology |
|------------|-------------|
| Backend | Node.js, Express.js |
| Database | MongoDB |
| Templating Engine | EJS |
| Authentication | express-session, bcrypt, jsonwebtoken |
| Cookie Handling | cookie-parser |
```

```
### 5. Access the app
Open your browser and go to:  
👉 **http://localhost:3000**

---

## 👤 User Flow

1. User registers → password is **hashed** and stored.  
2. User logs in → password is **validated using bcrypt**.  
3. Session is generated → stored in **cookies**.  
4. Admin can **view all users** and change their status (active/disabled).  
5. Disabled users cannot log in until reactivated by admin.

---

## 🧹 To Do / Future Improvements
- ✅ Password reset feature  
- ✅ Add pagination in admin dashboard  
- ✅ Use environment variables for secrets  
- ✅ Improve UI with Tailwind or Bootstrap  

---

## 👨‍💻 Author
**Linas**  
📧 Email: [linasliyakath@gmail.com]  
🌐 GitHub: [github.com/yourusername](https://github.com/linas665)

---
