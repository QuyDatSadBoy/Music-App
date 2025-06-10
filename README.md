# 🎵 Music App

Ứng dụng nghe nhạc được xây dựng với Node.js, Express và TypeScript.

## 📋 Mục lục

- [Tính năng](#-tính-năng)
- [Công nghệ sử dụng](#-công-nghệ-sử-dụng)
- [Yêu cầu hệ thống](#-yêu-cầu-hệ-thống)
- [Cài đặt](#-cài-đặt)
- [Sử dụng](#-sử-dụng)
- [Cấu trúc dự án](#-cấu-trúc-dự-án)
- [API Documentation](#-api-documentation)
- [Contributing](#-contributing)
- [License](#-license)
- [Liên hệ](#-liên-hệ)

## ✨ Tính năng

- 🎶 Phát nhạc online
- 📱 Giao diện responsive
- 🔍 Tìm kiếm bài hát
- 📝 Quản lý playlist
- 👤 Hệ thống người dùng
- ⭐ Yêu thích bài hát
- 🎯 Gợi ý nhạc thông minh

## 🛠 Công nghệ sử dụng

- **Backend Framework:** Express.js
- **Language:** TypeScript
- **Runtime:** Node.js
- **Development Tools:** 
  - Nodemon (auto-reload)
  - ts-node (TypeScript execution)

## 📋 Yêu cầu hệ thống

- Node.js >= 16.x
- npm >= 8.x hoặc yarn >= 1.22.x
- TypeScript >= 5.x

## 🚀 Cài đặt

### 1. Clone repository

```bash
git clone https://github.com/QuyDatSadBoy/Music-App.git
cd Music-App
```

### 2. Cài đặt dependencies

```bash
npm install
```

hoặc

```bash
yarn install
```

### 3. Cấu hình môi trường

Tạo file `.env` trong thư mục gốc:

```env
PORT=3000
NODE_ENV=development
# Thêm các biến môi trường khác nếu cần
```

## 🎯 Sử dụng

### Development Mode

```bash
npm start
```

Ứng dụng sẽ chạy tại `http://localhost:3000`

### Production Mode

```bash
npm run build
npm run prod
```

## 📁 Cấu trúc dự án

```
Music-App/
├── src/
│   ├── controllers/     # API controllers
│   ├── models/          # Database models
│   ├── routes/          # API routes
│   ├── middleware/      # Custom middleware
│   ├── services/        # Business logic
│   └── utils/           # Utility functions
├── public/              # Static files
├── tests/               # Test files
├── index.ts             # Entry point
├── package.json
└── README.md
```

## 📚 API Documentation

### Endpoints chính:

- `GET /api/songs` - Lấy danh sách bài hát
- `POST /api/songs` - Thêm bài hát mới
- `GET /api/songs/:id` - Lấy thông tin bài hát
- `PUT /api/songs/:id` - Cập nhật bài hát
- `DELETE /api/songs/:id` - Xóa bài hát

### Authentication:
- `POST /api/auth/login` - Đăng nhập
- `POST /api/auth/register` - Đăng ký
- `POST /api/auth/logout` - Đăng xuất

### User Management:
- `GET /api/users/profile` - Lấy thông tin profile
- `PUT /api/users/profile` - Cập nhật profile
- `GET /api/users/playlists` - Lấy danh sách playlist

## 🤝 Contributing

1. Fork repository
2. Tạo feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to branch (`git push origin feature/AmazingFeature`)
5. Tạo Pull Request

### Guidelines:

- Tuân thủ coding style hiện tại
- Viết tests cho features mới
- Cập nhật documentation khi cần thiết
- Sử dụng conventional commits

## 📝 License

Distributed under the ISC License. See `LICENSE` for more information.

## 👥 Team

- **Quy Dat** - [@QuyDatSadBoy](https://github.com/QuyDatSadBoy) - Developer

## 📞 Liên hệ

- GitHub: [@QuyDatSadBoy](https://github.com/QuyDatSadBoy)
- Project Link: [https://github.com/QuyDatSadBoy/Music-App](https://github.com/QuyDatSadBoy/Music-App)

## 🙏 Acknowledgments

- Cảm ơn các contributors đã đóng góp
- Inspired by các ứng dụng nhạc phổ biến
- Built with ❤️ và ☕

---

⭐ **Nếu bạn thấy project này hữu ích, hãy để lại một star nhé!** ⭐
