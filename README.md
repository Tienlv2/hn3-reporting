# HN3 BI & AI Reporting – bản xem trực tiếp

Trang web: https://tienlv2.github.io/hn3-reporting/ (cần mật khẩu truy cập).

- `index.html` – toàn bộ hệ thống + dữ liệu, **đã mã hóa AES-256-GCM**; chỉ giải mã được trong trình duyệt khi nhập đúng mật khẩu.
- `source.tar.gz.enc` – bản sao lưu mã nguồn, mã hóa AES-256. Giải nén:
  `openssl enc -d -aes-256-cbc -pbkdf2 -iter 250000 -in source.tar.gz.enc | tar xz`

Không có dữ liệu nội bộ dạng đọc được trong repo này.
