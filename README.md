# website-tu-van-suc-khoe.
# CN-DX23TT9-PHANTHANHDAT-eshop-SUCKHOEwordpress
# Đồ án: Xây dựng website tư vấn và theo dõi sức khỏe cá nhân
**Sinh viên thực hiện:** Phan Thành Đạt
**Giảng viên hướng dẫn:** ThS. Nguyễn Hoàng Duy Thiện

## 1. Tóm tắt dự án
Xây dựng website tư vấn và theo dõi sức khỏe cá nhân 

## 2. Hướng dẫn cài đặt (Setup)
1. Cài đặt XAMPP (PHP, MySQL).
2. Cài đặt XAMPP:

# Tải XAMPP bản dành cho Windows tại trang chủ apachefriends.org.
# Mở file vừa tải để cài đặt (cứ nhấn Next liên tục đến khi hoàn tất).
# Khởi động hệ thống:
# Mở phần mềm XAMPP Control Panel lên.
# Nhấn nút Start ở dòng Apache và MySQL. (Chờ hai dòng này sáng màu xanh lá là thành công).
# Tạo Database:
# Mở trình duyệt web, gõ địa chỉ: localhost/phpmyadmin/.
# Nhấn vào tab Cơ sở dữ liệu (Databases).
# Ô "Tên cơ sở dữ liệu", gõ: docau_db.
# Ô bên cạnh chọn utf8mb4_unicode_ci rồi nhấn Tạo (Create).

## 3. Tải và cấu hình lõi WordPress.
# Chuẩn bị mã nguồn:
# Vào wordpress.org/download/, tải file .zip mới nhất về.
# Giải nén file đó ra, bạn sẽ được một thư mục tên là wordpress.
# Chép thư mục wordpress này vào đường dẫn C:\xampp\htdocs\.
# Đổi tên thư mục wordpress thành suckhoe.

# Khai báo Website:
# Mở trình duyệt, gõ địa chỉ: localhost/suckhoe.
# Chọn ngôn ngữ Tiếng Việt -> Nhấn Tiếp tục -> Nhấn Thực hiện ngay.
# Tên Database: gõ suckhoe_db.
# Tên người dùng: gõ root.
# Mật khẩu: (Xóa trắng, không gõ gì vào đây).
# Nhấn Gửi -> Bắt đầu cài đặt.

# Tạo tài khoản Quản trị Admin:
# Điền Tên website (VD: Suckhoe).
# Tự tạo một Tên đăng nhập và Mật khẩu (Nhớ kỹ để sau này đăng nhập quản lý web). Nhấn Cài đặt WordPress.

# Cài plugin Bán hàng (WooCommerce):
# Đăng nhập vào quản trị web bằng tài khoản vừa tạo.
# Nhìn menu bên trái, chọn Plugin -> Cài mới.
# Gõ WooCommerce vào ô tìm kiếm. Nhấn Cài đặt ngay rồi nhấn Kích hoạt.

3. Import file cơ sở dữ liệu từ thư mục `setup/suckhoe_db.sql` vào phpMyAdmin.
4. Chép mã nguồn giao diện vào thư mục `wp-content/themes/` và kích hoạt.
