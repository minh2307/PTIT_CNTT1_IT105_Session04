| **Thành phần**    | **Modifier** | **Giải thích**                                                                                                                                        |
| ----------------- | ------------ | ----------------------------------------------------------------------------------------------------------------------------------------------------- |
| username       | private    | Thông tin định danh người dùng, không nên cho truy cập trực tiếp từ bên ngoài để tránh bị sửa đổi trái phép. Có thể truy cập thông qua getter/setter. |
| password       | private    | Dữ liệu nhạy cảm nhất, bắt buộc phải ẩn hoàn toàn, chỉ cho phép truy cập nội bộ hoặc qua phương thức bảo mật (vd: mã hóa, so sánh hash).              |
| lastLoginTime  | private    | Dữ liệu trạng thái, không nên cho chỉnh sửa trực tiếp từ bên ngoài; chỉ được cập nhật khi người dùng đăng nhập thành công.                            |
| login()      | public     | Hành vi chính của lớp, được gọi từ bên ngoài (ví dụ: giao diện đăng nhập). Cần khả năng truy cập công khai.                                           |
| resetPassword() | public     | Cho phép người dùng hoặc hệ thống gọi đến để đặt lại mật khẩu, nên công khai để có thể truy cập từ bên ngoài lớp.                                     |
