# Game Store Project (Legacy)

![Status](https://img.shields.io/badge/Status-Legacy-orange)
![Maintained](https://img.shields.io/badge/Maintained%3F-No-red)

---

## 🇻🇳 Tiếng Việt

⚠️ **Thông báo quan trọng**: Repo này chứa mã nguồn cũ (Java/NetBeans). Hiện tại dự án đang được tái cấu trúc và chuyển đổi hoàn toàn sang hệ thống **C# .NET Monolith** để tối ưu hiệu năng và khả năng bảo trì.

### 📁 Cấu trúc hiện tại
* `/web`: Frontend (HTML, CSS, Bootstrap).
* `/src`: Backend (Java).

### 🚀 Hướng dẫn khởi chạy
1. **Database**: Sử dụng **Microsoft SQL Server**. Thực thi file `GameStoreDatabase.sql` để khởi tạo cấu trúc và dữ liệu.
2. **Backend**: Mở thư mục `/src` bằng **NetBeans IDE**. Cấu hình lại chuỗi kết nối và nhấn `Run`.
3. **Frontend**: Truy cập thư mục `/web`, chạy lệnh:
   ```bash
   npm install
   npm run dev

## 🇺🇸 English
⚠️ **Important Notice**: This repository contains legacy source code (Java/NetBeans). The project is currently being refactored and fully migrated to a **C# .NET Monolith** system for better performance and maintainability.

### 📁 Project Structure
* `/web`: Frontend (HTML, CSS, Bootstrap).
* `/src`: Backend (Java).

### 🚀 Getting Started
1. **Database**: Use **Microsoft SQL Server**. Execute the GameStoreDatabase.sql file to initialize the schema and sample data.
2. **Backend**: Open the /src directory with **NetBeans IDE**. Update the connection string and click Run.
3. **Frontend**: Navigate to the /web directory and run:
   ```bash
   npm install
   npm run dev
