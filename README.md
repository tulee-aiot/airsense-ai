# AirSense AI

Website giới thiệu dự án khởi nghiệp sinh viên **AirSense AI** — hệ thống giám sát và dự đoán chất lượng không khí trong nhà bằng IoT và Trí tuệ nhân tạo.

**🔗 Xem trực tiếp:** _sẽ cập nhật link sau khi bật GitHub Pages (xem hướng dẫn bên dưới)_

## Về dự án

AirSense AI theo dõi 6 chỉ số môi trường (CO₂, bụi mịn PM2.5, khí CO, VOC, nhiệt độ, độ ẩm) theo thời gian thực qua mạng cảm biến ESP32, xử lý và dự đoán bằng AI chạy trên Raspberry Pi, đồng bộ dữ liệu và cảnh báo qua Firebase tới ứng dụng Android và web.

Dự án khởi nghiệp sinh viên 2026 — Trường Đại học Sư phạm Kỹ thuật Hưng Yên, Khoa Kinh tế.

## Nội dung repo

Repo này chỉ chứa **website giới thiệu + dashboard demo** (`index.html`) — một trang tĩnh, không cần build, không phụ thuộc gì ngoài Google Fonts.

```
index.html   → toàn bộ trang web (HTML/CSS/JS gộp trong 1 file)
```

Dữ liệu hiển thị trên khu vực Dashboard hiện là **dữ liệu minh họa** (sinh ngẫu nhiên bằng JavaScript), dùng để demo giao diện khi chưa có thiết bị phần cứng thật. Bản kết nối dữ liệu thật qua Firebase Realtime Database sẽ làm ở giai đoạn sau.

## Chạy thử ở máy local

Chỉ cần mở trực tiếp file `index.html` bằng trình duyệt, không cần cài đặt gì.

## Deploy

- **GitHub Pages** (bản giới thiệu tĩnh — dùng cho repo này): xem hướng dẫn bật Pages trong phần Settings của repo.
- **Firebase Hosting** (bản dashboard, sẽ nối dữ liệu thật từ Raspberry Pi qua Firebase): xem `HUONG_DAN_DEPLOY.txt`.

## Nhóm dự án

| Vai trò | Họ và tên |
|---|---|
| Trưởng nhóm | Trần Thị Mỹ Tâm |
| Thành viên | Nguyễn Thị Hiên |
| Thành viên | Nguyễn Bá Hiếu |
| Thành viên | Nguyễn Thị Hải An |
| Giảng viên hướng dẫn | TS. Đỗ Thị Thảnh |
