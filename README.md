# FCJ Book Shop Lab (Fixed Node.js Dependency Version)

Đây là phiên bản đã được sửa lỗi liên quan đến version của các dependency Node.js trong dự án **FCJ Book Shop Lab**.

---
## Cấu hình ban đầu

Trước khi chạy ứng dụng, bạn cần tạo file cấu hình:

1. Truy cập vào thư mục `src/`
2. Tạo một file mới tên là `config.js` dựa trên file mẫu `config-ex.js`
3. Cập nhật các giá trị cấu hình trong `config.js` theo nhu cầu của bạn.

---
##  Khởi chạy ứng dụng

Project này được khởi tạo bằng [Create React App](https://github.com/facebook/create-react-app).

Trong thư mục project, bạn có thể chạy:

### `npm install`

Cài đặt các dependencies cần thiết.

### `npm start`

Chạy ứng dụng ở chế độ development.  
Mở [http://localhost:3000](http://localhost:3000) để xem trên trình duyệt.  
Trang sẽ tự động reload khi bạn chỉnh sửa mã nguồn.  
Bạn cũng sẽ thấy lỗi lint nếu có trong console.

### `npm test`

Chạy các test ở chế độ interactive.  
Xem thêm tại [Running Tests](https://facebook.github.io/create-react-app/docs/running-tests)

### `npm run build`

Build project cho môi trường production.  
Các file được build sẽ nằm trong thư mục `build/` và được tối ưu hóa để có hiệu suất tốt nhất.

---

##  Ghi chú

- Hãy chắc chắn rằng bạn đang dùng đúng phiên bản Node.js được chỉ định trong file `.nvmrc` (nếu có), hoặc theo yêu cầu của các dependency.
- Nếu gặp lỗi khi `npm install`, thử xóa `node_modules` và `package-lock.json` rồi cài lại.

##  Cấu trúc chính
```
FCJ-Book-Shop-Lab/
├── src/
│ ├── config-ex.js # File cấu hình mẫu
│ ├── config.js # File bạn cần tạo
│ └── ... # Các thành phần React khác
├── public/
├── package.json
└── README.md
```
##  Liên hệ
Mọi thắc mắc hoặc đóng góp vui lòng tạo issue hoặc liên hệ với nhóm phát triển.