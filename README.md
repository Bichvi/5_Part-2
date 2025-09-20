# 5_Part-2
# Node.js Authentication & Web Development - Part 2

## 📌 Mô tả
Dự án học tập **Node.js, Express, MongoDB, Mongoose** với session-based authentication, giao diện view bằng **EJS + Bootstrap**. Bao gồm các bài học về xây dựng ứng dụng web với authentication system.

## 📚 Nội dung
### Lesson06 - Authentication System
- **Node.js** với Express framework
- **MongoDB** với Mongoose ODM
- **Session-based Authentication** (đăng ký, đăng nhập, đăng xuất)
- **EJS Templates** với Bootstrap UI
- **MVC Architecture Pattern**

## 🚀 Chức năng
- ✅ Đăng ký tài khoản người dùng
- ✅ Đăng nhập với session + cookie
- ✅ Đăng xuất an toàn
- ✅ Giao diện web responsive (EJS + Bootstrap)
- ✅ Bảo mật với bcrypt password hashing
- ✅ Session management

## ⚙️ Cài đặt và chạy
```bash
# Clone repository
git clone https://github.com/Bichvi/5_Part-2.git
cd 5_Part-2/lesson06

# Cài đặt dependencies
npm install

# Chạy ứng dụng
npm start
```

Ứng dụng sẽ chạy tại: `http://localhost:3000`

## 🛠️ Công nghệ sử dụng
- **Backend**: Node.js, Express.js
- **Database**: MongoDB, Mongoose
- **Authentication**: Express-session, Bcrypt
- **Template Engine**: EJS
- **Frontend**: Bootstrap 5, CSS3, JavaScript
- **Architecture**: MVC Pattern

## 📂 Cấu trúc thư mục
```
lesson06/
├── app.js              # Main application file
├── package.json        # Dependencies and scripts
├── models/
│   └── User.js         # User model (Mongoose)
├── routes/
│   └── auth.js         # Authentication routes
└── views/
    ├── layout.ejs      # Main layout template
    ├── index.ejs       # Home page
    ├── login.ejs       # Login page
    ├── register.ejs    # Registration page
    └── partials/
        ├── header.ejs  # Header component
        └── footer.ejs  # Footer component
```

## 🔧 Environment Variables
Tạo file `.env` trong thư mục `lesson06/`:
```env
MONGODB_URI=mongodb://localhost:27017/nodejs_auth
SESSION_SECRET=your_session_secret_key
PORT=3000
```

## 📝 Ghi chú
- Đảm bảo MongoDB đang chạy trên máy của bạn
- Sử dụng bcrypt để hash password an toàn
- Session được lưu trữ server-side với cookie

## 👨‍💻 Tác giả
**Bichvi** - [GitHub Profile](https://github.com/Bichvi)
