# Nhật ký AI · Thiết kế kiểm thử hệ thống Coffee Shop

SOF309 · Lệ Trung Bảo Long · TD01606 · 11/9/2026

## Ngữ cảnh
Đưa đặc tả hệ thống Quản lý Cà phê vào ngữ cảnh của AI. Đối chiếu với LoginController, RegisterController, ProductController, bộ lọc bảo mật và biểu mẫu JSP.

## Prompt sử dụng
Bạn là QA Lead. Dưới đây là đặc tả nghiệp vụ dự án Web của tôi: 
# ĐẶC TẢ NGHIỆP VỤ - COFFEE SHOP MANAGEMENT SYSTEM

## 1. URL CÁC MÀN HÌNH CHÍNH
- Màn hình Đăng nhập: `/login`
- Màn hình Đăng ký: `/register`
- Màn hình Quản lý Sản phẩm / Menu: `/products`

## 2. RÀNG BUỘC VALIDATION DỮ LIỆU
- **Tài khoản / Mật khẩu:** Độ dài từ 5 đến 20 ký tự, không chứa ký tự đặc biệt hoặc khoảng trắng ở tài khoản.
- **Giá sản phẩm:** Giá bán phải lớn hơn 0 (`> 0`), bắt buộc nhập dạng số.
- **Mã giảm giá (Voucher):** Nhập đúng mã `SOF309` để áp dụng giảm 20%.

Hãy áp dụng kỹ thuật Phân vùng tương đương và Phân tích giá trị biên để thiết kế Test Plan và Bộ Test Case chi tiết cho Controller và UI.

## Đối chiếu đầu ra
* Đã ghi kế hoạch và ca kiểm thử theo route thật của dự án (`/login`, `/register`, `/products`).
* Bổ sung biên mật khẩu (5-20 ký tự), kiểm tra khoảng trắng và giá sản phẩm > 0.
* Dùng thao tác kiểm tra mã giảm giá và phân quyền quản lý sản phẩm.