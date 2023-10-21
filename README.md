
## Yêu cầu

Để bắt đầu sử dụng dự án, bạn cần cài đặt Node.js trên máy tính của mình. Nếu bạn chưa cài đặt Node.js, bạn có thể tải file .msi đính kèm trong source code

## Cài đặt

1. Clone dự án từ GitHub:
```bash
git clone https://github.com/DuyThanh1211/socialnetwork-website.git
Di chuyển vào tổng thư mục dự án bấm: --> npm install -g concurrently sau khi chạy xong bấm tiếp lệnh npm install concurrently --save-dev
Cài đặt các dependencies cho client bằng cách:
cd ../client
---> npm install -g concurrently sau khi chạy xong bấm tiếp lệnh npm install concurrently --save-dev
Khởi động server và client:
Trong thư mục gốc của dự án: đầu tiên dùng lệnh set NODE_OPTIONS=--openssl-legacy-provider sau khi enter chạy lệnh
---> npm run dev
Dự án sẽ được khởi chạy cùng lúc cả server và client.

Sử dụng
Trình duyệt của bạn sẽ tự động mở tại địa chỉ http://localhost:5000.
Đăng nhập hoặc đăng ký tài khoản để bắt đầu sử dụng dịch vụ.
