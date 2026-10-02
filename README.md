# Lê Hoàng Hiệp — Trang web cá nhân

Trang web tĩnh một trang (HTML/CSS/JS thuần, không cần build).

## Xem thử

Mở trực tiếp `index.html` trong trình duyệt, hoặc chạy:

```bash
python3 -m http.server 8000
# rồi mở http://localhost:8000
```

## Tuỳ chỉnh nội dung

Mọi nội dung nằm trong `index.html`. Những chỗ nên thay bằng thông tin thật:

- **Ảnh đại diện**: đặt ảnh (ví dụ `avatar.jpg`) cạnh `index.html`, rồi thay `<span>LHH</span>` trong khối `.portrait` bằng `<img src="avatar.jpg" alt="Lê Hoàng Hiệp">`.
- **Chức danh & giới thiệu**: phần `hero` và `#gioi-thieu`.
- **Kinh nghiệm**: thay "Tên công ty", "Tên trường đại học" và mốc thời gian trong `#kinh-nghiem`.
- **Dự án**: tên, mô tả và đường dẫn (`href="#"`) trong `#du-an`.
- **Liên hệ**: thay `email@example.com` và các đường dẫn GitHub / LinkedIn / Facebook trong `#lien-he`.

Màu sắc được khai báo dưới dạng biến CSS ở đầu `style.css` (có sẵn chế độ sáng/tối).

## Đăng lên mạng

Có thể bật **GitHub Pages** cho repo này (Settings → Pages → Deploy from a branch → chọn nhánh và thư mục `/root`).
