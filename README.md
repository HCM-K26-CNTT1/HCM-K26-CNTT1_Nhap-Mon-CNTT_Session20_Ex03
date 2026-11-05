# Bài 3: Quản lý rủi ro khi mất thiết bị xác thực

## 1. Phân tích quy trình IPO

**Input (Đầu vào):**

- Backup Codes đã tạo và lưu trữ an toàn từ trước.
- Tài khoản AWS và thông tin đăng nhập hợp lệ.

**Process (Xử lý):**

1. Sử dụng thiết bị khác để truy cập trang đăng nhập AWS.
2. Nhập tài khoản và mật khẩu.
3. Chọn phương thức xác thực bằng Backup Codes.
4. Nhập một mã dự phòng chưa sử dụng.
5. Sau khi đăng nhập thành công, thu hồi thiết bị xác thực cũ.
6. Cài đặt Google Authenticator trên điện thoại mới và liên kết lại tài khoản.
7. Tạo bộ Backup Codes mới và lưu trữ an toàn.

**Output (Đầu ra):**

- Khôi phục quyền truy cập AWS.
- Mã dự phòng cũ được thu hồi hoặc không thể sử dụng lại.
- Thiết bị xác thực mới được thiết lập.
- Tài khoản được bảo vệ an toàn.

## 2. Tại sao không lưu Backup Codes dưới dạng ảnh trong điện thoại?

- Nếu mất điện thoại, kẻ nhặt được có thể truy cập thư viện ảnh và lấy mã dự phòng.
- Backup Codes có thể bị đồng bộ lên dịch vụ lưu trữ đám mây không an toàn.
- Người khác có thể xem hoặc sao chép mã nếu điện thoại không được bảo vệ tốt.

## 3. Biện pháp bảo vệ

- In Backup Codes ra giấy và cất ở nơi an toàn.
- Lưu trong Password Manager có mã hóa.
- Không gửi mã qua tin nhắn hoặc email.
- Không sử dụng lại Backup Codes đã dùng.
- Thu hồi phiên đăng nhập và thiết bị bị mất khi có nguy cơ bị truy cập trái phép.

## 4. Kết luận

Backup Codes giúp khôi phục quyền truy cập khi mất thiết bị xác thực. Cần lưu mã dự phòng ở nơi an toàn, không lưu dưới dạng ảnh trong điện thoại và tạo bộ mã mới sau khi khôi phục tài khoản để giảm nguy cơ bị chiếm đoạt.


Sử dụng chung mật khẩu cho nhiều tài khoản có thể gây ra hiệu ứng Domino khi một website bị rò rỉ dữ liệu. Vì vậy, cần sử dụng mật khẩu mạnh, riêng biệt cho từng tài khoản và quản lý bằng Password Manager có mã hóa AES-256 như Bitwarden. Đồng thời, nên bật xác thực hai yếu tố (2FA) để tăng cường bảo mật.
