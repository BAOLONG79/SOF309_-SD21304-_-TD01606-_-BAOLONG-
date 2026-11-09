# ĐẶC TẢ NGHIỆP VỤ WEB QUẢN LÝ CÀ PHÊ (SPECIFICATIONS)

## 1. THÔNG TIN DỰ ÁN
* **Tên đề tài:** Hệ Thống Quản Lý Quán Cà Phê (Coffee Management System)
* **Công nghệ:** Java 17/21, Spring Boot, Maven, HTML/CSS/JS
* **URL chạy local:** `http://localhost:8080`

## 2. QUY TẮC NGHIỆP VỤ (BUSINESS RULES)
* **Chức năng Đăng nhập:** Kiểm tra đúng tài khoản/mật khẩu -> chuyển hướng về trang chủ quản lý; sai -> báo lỗi.
* **Chức năng Quản lý Thực đơn (CRUD):** 
  * Thêm món mới: Tên sản phẩm (bắt buộc, không trùng), Giá bán (> 0).
  * Xóa / Sửa: Cập nhật dữ liệu trực tiếp trên giao diện và danh sách thực đơn.
* **Chức năng Bán hàng (POS) & Giảm giá:**
  * Thêm món vào giỏ hàng và tính tổng tiền tự động.
  * Hỗ trợ nhập mã giảm giá (Voucher `SOF309` giảm 20% tổng hóa đơn).