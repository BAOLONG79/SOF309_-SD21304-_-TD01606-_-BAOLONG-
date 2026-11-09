# Kế hoạch Kiểm thử - Coffee Shop Management System

## 1. Mục tiêu kiểm thử
- Đảm bảo hệ thống Web Quản lý Quán Cà Phê hoạt động ổn định trên môi trường Localhost (`http://localhost:8080`).
- Xác thực các luồng nghiệp vụ cốt lõi: Đăng nhập, Thêm/Xóa thực đơn, tính tiền POS và áp dụng mã giảm giá không bị lỗi.

## 2. Phạm vi kiểm thử (Scope)
- **Kiểm thử giao diện & chức năng (Functional Testing):** Kiểm tra các form nhập liệu, nút bấm, bảng dữ liệu.
- **Kiểm thử tự động (Automation/CI):** Kiểm thử thông qua GitHub Actions khi đẩy code lên repository.

## 3. Môi trường kiểm thử
- **Trình duyệt:** Google Chrome, Microsoft Edge.
- **Công cụ:** Java JDK 17/21, Maven, Spring Boot, Eclipse IDE[cite: 2].