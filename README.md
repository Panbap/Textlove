# Textlove

Trang web hiệu ứng chữ “love” từ Panbap — một công cụ thú vị để thể hiện tình cảm theo phong cách lập trình.

## Demo trực tiếp tại:

https://panbap.github.io/Textlove/input

## 🎯 Giới thiệu
Textlove giúp bạn tạo ra dãy chữ động  mang đến cảm giác ấn tượng, độc đáo – thích hợp dùng cho:

Slide tỏ tình, lời chúc

Landing page cảm xúc, hoặc trang sự kiện

Trải nghiệm coding vui vẻ!

## 🏗 Cấu trúc dự án
bash
Copy
Edit
```text
├── index.html         # Trang chính 
├── input.html         # Trang nhập lời nhắn
└── assets/            # Tài nguyên (fonts, ảnh ...)
    └── style.css      # Thiết kế style
    └── script.js      # Logic + hiệu ứng
```
## 🚀 Cách sử dụng
```text
Clone hoặc tải repo về:
bash
Copy
Edit
git clone https://github.com/Panbap/Textlove.git
cd Textlove
Xem thử:
```
Mở index.html trực tiếp trên trình duyệt;

## 🧩 Tùy chỉnh nhanh
Mở js/script.js, tìm mảng MESSAGES:
```text
js
Copy
Edit
const MESSAGES = [
  { delay: 0, text: "LOVE" },
  { delay: 1000, text: "YOU" },
  { delay: 2000, text: "TRUE" }
];
delay (ms): thời gian sau khi click đến khi hiệu ứng bắt đầu cho dòng đó.
```
text: nội dung muốn hiển thị.

## 🎨 Điều chỉnh style
Trong css/style.css, bạn có thể:

Thay font, màu sắc, kích thước chữ

Sửa timing animation, ghost/blink/glitch

Thay nền, thêm shadow hoặc filter

## 🛠 Cách hoạt động
JavaScript:

Dựa trên mảng MESSAGES, hàm animate() lần lượt xử lý từng message.

Mỗi ký tự hiển thị với xác suất chọn từ tập ký tự đặc biệt.

CSS đảm nhiệm hiệu ứng mờ – làm nổi bật bước nhảy chữ.

CSS: sử dụng @keyframes, opacity, text-shadow để tạo hiệu ứng 

## ✨ Gợi ý nâng cao
Điều chỉnh tốc độ: thay đổi SCRAMBLE_SPEED, duration.

Sinh tự động: kích hoạt theo onload, scroll hoặc hover thay vì click.

Message động: lấy nội dung từ form, JSON API để nội dung linh hoạt.

## 📄 Giấy phép
Dự án dùng MIT License (xem file LICENSE).
Bạn có thể sử dụng, chỉnh sửa, và phân phối lại thoải mái.

## 📣 Góp ý & Đóng góp
Bạn thấy Textlove hữu ích? Rất vui nếu bạn:

🌟 Star repo để ủng hộ

🛠 Fork và tùy biến rồi gửi Pull Request

🐛 Báo lỗi hoặc đề xuất tính năng qua Issues

> 👏 Kết
Cảm ơn bạn đã quan tâm tới Textlove! Chúc bạn tạo ra những đoạn text động đẹp, giàu cảm hứng – và đừng ngại chia sẻ thành quả với Panbap nhé!
