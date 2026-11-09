# Bộ Kịch bản Kiểm thử Chi tiết (TEST_CASES.md)

| STT | Chức năng | Mô tả Test Case | Dữ liệu đầu vào | Kết quả mong đợi |
| :--- | :--- | :--- | :--- | :--- |
| **TC01** | Đăng nhập | Đăng nhập với tài khoản hợp lệ | Username: `admin`, Password: `123` | Đăng nhập thành công, chuyển hướng vào trang chính. |
| **TC02** | Đăng nhập | Đăng nhập với tài khoản sai | Username: `wrong`, Password: `wrong` | Hiển thị thông báo lỗi, từ chối đăng nhập. |
| **TC03** | Quản lý Menu | Thêm món mới hợp lệ | Tên: `Cà phê sữa`, Giá: `25000` | Món mới xuất hiện trong danh sách thực đơn. |
| **TC04** | Quản lý Menu | Thêm món với giá âm/bằng 0 | Tên: `Trà đá`, Giá: `-5000` | Hệ thống báo lỗi dữ liệu không hợp lệ. |
| **TC05** | Bán hàng (POS) | Áp dụng mã giảm giá hợp lệ | Nhập mã voucher: `SOF309` | Tổng tiền được giảm chính xác 20%. |