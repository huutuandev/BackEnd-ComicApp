# 📚 Comic API – Backend cho App Android Đọc Truyện

> 🚀 Backend chính cho ứng dụng đọc truyện Android
> 👑 Leader & Main Backend: Hữu Tuấn

---

## 🌸 Giới thiệu

**Comic API** là hệ thống backend phục vụ cho ứng dụng Android đọc truyện, cung cấp đầy đủ API cho các chức năng:

* 📖 Đọc truyện
* 🎧 Nhạc nền / trải nghiệm
* 🔐 Xác thực người dùng
* 💬 Bình luận & tương tác

Hệ thống được xây dựng theo kiến trúc RESTful, tối ưu cho mobile app.

---

## 🏗️ Kiến trúc dự án

```
com.comicapp.comic_api
├── config          ⚙️ Cấu hình (Security, JWT...)
├── controller      🎮 API Controller
├── service         🧠 Business logic
├── repository      💾 Database layer
├── entity          📦 Model dữ liệu
├── dto             🔄 Data transfer object
├── mapper          🔁 Mapping dữ liệu
├── filter          🛡️ Filter (Auth, JWT)
├── util            🔧 Tiện ích
```

---

## 🧩 Chức năng chính

* 🔐 **Authentication (JWT)**
* 📖 **Quản lý truyện (Story, Chapter)**
* 💬 **Comment & Emotion**
* ❤️ **Favorite truyện**
* 🎧 **Music API (trải nghiệm đọc truyện)**
* 📤 **Upload file (ảnh, nội dung)**

---

## 👑 Team & Phân chia nhiệm vụ

### 🧠 Leader & Backend chính (Bạn)

* Thiết kế kiến trúc hệ thống
* Xây dựng API core (Auth, Story, Chapter)
* Thiết kế database
* Code chính backend
* Review code & định hướng team

---

### 👨‍💻 Backend Support

* Hỗ trợ viết API phụ (Comment, Favorite, Emotion)
* Viết DTO, Mapper
* Test API

---

### 📱 Android Developer

* Xây dựng UI app đọc truyện
* Gọi API từ backend
* Xử lý hiển thị nội dung truyện
* Tối ưu UX đọc truyện

---

### 🎨 UI/UX (nếu có)

* Thiết kế giao diện app
* Tạo trải nghiệm đọc truyện mượt mà

---

## 🔥 API tiêu biểu

### 📖 Story API

* `GET /api/story` – Lấy danh sách truyện
* `GET /api/story/{id}` – Chi tiết truyện

### 📚 Chapter API

* `GET /api/chapter/{storyId}` – Danh sách chapter

### 🔐 Auth API

* `POST /api/auth/login`
* `POST /api/auth/register`

### 🎧 Music API

* `GET /api/music`
* `POST /api/music`

---

## 🚀 Công nghệ sử dụng

* ☕ **Spring Boot**
* 🔐 **Spring Security + JWT**
* 💾 **MySQL / PostgreSQL**
* 🔁 **MapStruct / ModelMapper**

---

## ⚙️ Cài đặt

```bash
git clone https://github.com/your-username/comic-api.git
cd comic-api
./mvnw spring-boot:run
```

---

## 📌 Ghi chú

* Đây là backend phục vụ **app Android đọc truyện**
* Leader chịu trách nhiệm chính về kiến trúc & backend
* Project mang tính teamwork & học tập nâng cao

---

## 🌟 Quote

> “Code không chỉ chạy, mà còn phải đẹp như cách một câu chuyện được kể.”
****
