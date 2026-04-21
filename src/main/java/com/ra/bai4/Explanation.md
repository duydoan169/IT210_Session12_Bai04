Cơ chế quản lý:

Spring Boot sử dụng một cơ chế tập trung để nạp các thuộc tính từ nhiều nguồn khác nhau (file properties, file yaml, biến môi trường, tham số dòng lệnh).

Các giá trị mặc định được định nghĩa sẵn trong mã nguồn của Spring Boot (thông qua các lớp @ConfigurationProperties). Khi ứng dụng khởi động, nó sẽ kiểm tra xem người dùng có định nghĩa lại các giá trị này không. Nếu có, nó sẽ ghi đè (override) lên giá trị mặc định.

Tìm danh sách cấu hình ở đâu?

Trang chủ chính thức: Bạn có thể tìm thấy danh sách đầy đủ tại mục Common Application Properties trong tài liệu của Spring.