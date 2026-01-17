# 🎡 Vòng Quay May Mắn - Vercel Deployment

Ứng dụng Vòng Quay May Mắn - Hỗ trợ lên đến 400 người chơi.

## 📁 Cấu trúc thư mục

```
VongQuayMayMan_Vercel/
├── index.html          # File chính
├── background.jpg      # Ảnh nền
├── ipc-logo.png        # Logo trung tâm
├── pointer-arrow.png   # Mũi tên chỉ
├── vinh-danh.png       # Ảnh bảng vinh danh
├── xlsx.full.min.js    # Thư viện đọc Excel
├── vercel.json         # Cấu hình Vercel
└── README.md           # Hướng dẫn
```

## 🚀 Cách Deploy lên Vercel

### Cách 1: Qua Vercel CLI

1. **Cài đặt Vercel CLI:**

   ```bash
   npm install -g vercel
   ```

2. **Đăng nhập Vercel:**

   ```bash
   vercel login
   ```

3. **Deploy:**

   ```bash
   cd VongQuayMayMan_Vercel
   vercel
   ```

4. **Deploy Production:**
   ```bash
   vercel --prod
   ```

### Cách 2: Qua Vercel Dashboard

1. Truy cập [vercel.com](https://vercel.com)
2. Đăng nhập tài khoản
3. Click **"New Project"**
4. Chọn **"Import from Git"** hoặc **"Upload"**
5. Upload thư mục `VongQuayMayMan_Vercel`
6. Click **"Deploy"**

### Cách 3: Qua GitHub

1. Tạo repository mới trên GitHub
2. Push thư mục `VongQuayMayMan_Vercel` lên
3. Vào Vercel → Import từ GitHub
4. Chọn repository và Deploy

## ⚙️ Tính năng

- 🎡 Vòng quay may mắn với hiệu ứng đẹp
- 📊 Import danh sách từ file Excel
- 🏆 Bảng vinh danh người thắng cuộc
- ⚙️ Tùy chỉnh giao diện (nền, logo, tên)
- 💾 Lưu cài đặt vào trình duyệt
- 📱 Hỗ trợ chế độ toàn màn hình

## 🎨 Tùy chỉnh

- Bấm nút **"⚙️ Cài đặt"** để thay đổi:
  - Tên chủ đề
  - Ảnh nền
  - Logo trung tâm
  - Kích thước logo

## 📝 License

© 2024 IPC E&C. All rights reserved.
