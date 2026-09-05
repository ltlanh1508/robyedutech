# ROBY Education & Technology — Website

Website tĩnh, responsive, chạy trực tiếp trên **GitHub Pages**.

## Cấu trúc

```text
robyedutech-website/
├── index.html
├── CNAME
├── README.md
└── assets/
    ├── style.css
    ├── script.js
    └── favicon.svg
```

## 1. Đưa website lên GitHub

1. Đăng nhập GitHub.
2. Tạo repository mới, ví dụ: `robyedutech`.
3. Upload toàn bộ file trong thư mục này lên repository.
4. Vào **Settings → Pages**.
5. Ở mục **Build and deployment**:
   - Source: `Deploy from a branch`
   - Branch: `main`
   - Folder: `/ (root)`
6. Bấm **Save**.

Sau vài phút, GitHub Pages sẽ tạo website dạng:

`https://TEN-TAI-KHOAN.github.io/robyedutech/`

## 2. Kết nối tên miền robyedutech.info.vn

File `CNAME` đã được tạo sẵn với nội dung:

`robyedutech.info.vn`

Trong GitHub:
1. Vào **Settings → Pages**
2. Custom domain: nhập `robyedutech.info.vn`
3. Bấm Save.
4. Khi DNS hoạt động, bật **Enforce HTTPS**.

### DNS cần cấu hình ở nơi mua tên miền

Với subdomain `robyedutech.info.vn`, thông thường bạn tạo:

- Type: `CNAME`
- Host/Name: `robyedutech`
- Value/Target: `TEN-TAI-KHOAN-GITHUB.github.io`

> Thay `TEN-TAI-KHOAN-GITHUB` bằng username GitHub của bạn.

Nếu nhà cung cấp tên miền yêu cầu dấu chấm ở cuối target, có thể dùng:

`TEN-TAI-KHOAN-GITHUB.github.io.`

## 3. Chỉnh nội dung

- Nội dung chính: `index.html`
- Màu sắc/giao diện: `assets/style.css`
- Menu mobile và năm footer: `assets/script.js`

## 4. Thông tin đang dùng trên website

- Thương hiệu: ROBY Education & Technology
- Website: robyedutech.info.vn
- Hotline/Zalo: 0797 039 979
- Nhóm khóa học:
  - AI • Robotics • AIoT
  - STEAM & Sáng tạo
  - Tin học & Lập trình
  - Rèn chữ
  - Kỹ năng tiền tiểu học
  - Hỗ trợ học tập

## Ghi chú

Website này không cần hosting riêng nếu dùng GitHub Pages. Bạn chỉ cần:
- Tài khoản GitHub
- Repository chứa website
- Tên miền đã mua
- Cấu hình DNS đúng
