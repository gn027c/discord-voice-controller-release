# Discord Voice Controller

Discord Voice Controller là công cụ chuyên dụng để quản lý và điều khiển nhiều tài khoản Discord (Self-bot) tham gia các kênh thoại cùng một lúc. Công cụ được thiết kế với giao diện trực quan, tối ưu cho việc điều phối số lượng lớn tài khoản một cách nhanh chóng và ổn định.

## Tính năng chính

### 1. Quản lý tài khoản (Token)

- Hỗ trợ thêm hàng loạt Token Discord cùng lúc.
- Tự động lưu và tải lại danh sách Token từ tệp cấu hình.
- Hiển thị trạng thái trực tuyến, avatar và tên người dùng của từng tài khoản ngay trên giao diện.

### 2. Điều khiển Voice tập trung

- Tham gia/Rời kênh (Join/Leave): Điều khiển toàn bộ hoặc một nhóm tài khoản đã chọn tham gia hoặc rời khỏi kênh thoại chỉ với một lần nhấn.
- Trạng thái âm thanh: Hỗ trợ đầy đủ các tính năng Tắt tiếng (Mute) và Điếc (Deafen).
- Hiệu ứng hình ảnh nâng cao: Hỗ trợ bật Camera (Video) và Phát trực tiếp (Stream) đồng loạt cho các tài khoản.
- Cơ chế ổn định: Tự động cập nhật lại trạng thái Voice khi có người dùng mới tham gia kênh để đảm bảo luồng Stream/Camera luôn hiển thị ổn định.

### 3. Xoay vòng trạng thái kênh thoại (Status Rotation)

- Tính năng đặt trạng thái văn bản (Voice Status) cho kênh thoại.
- Cơ chế tự động xoay vòng: Thay đổi liên tục các dòng trạng thái theo danh sách đã thiết lập với thời gian chờ tùy chỉnh, giúp kênh thoại trở nên sinh động hơn.

### 4. Quản lý Hồ sơ và Server

- Đổi Nickname đồng loạt: Thay đổi tên hiển thị trong server mục tiêu của tất cả tài khoản đang kết nối.
- Thay đổi Profile: Hỗ trợ đổi tên hiển thị chính của tài khoản.
- Tham gia Server: Tự động tham gia server mới thông qua đường dẫn mời (Invite link).

### 5. Tối ưu hóa trải nghiệm người dùng

- Chạy ngầm: Hỗ trợ thu nhỏ xuống khay hệ thống (System Tray) để ứng dụng luôn hoạt động mà không chiếm dụng không gian màn hình.
- Nhật ký hoạt động: Hệ thống ghi log chi tiết giúp theo dõi quá trình kết nối và phản hồi từ Discord API của từng Token theo thời gian thực.
- Giao diện hiện đại: Sử dụng ngôn ngữ thiết kế Dark Mode, hỗ trợ tốt trên môi trường Windows.

## Hướng dẫn sử dụng

1. Khởi động ứng dụng thông qua file thực thi (.exe).
2. Kích hoạt bản quyền (HWID):
   - Trong lần chạy đầu tiên, ứng dụng sẽ hiển thị mã Hardware ID (HWID) duy nhất của máy tính.
   - Nhấn nút "Copy HWID" và gửi mã này cho Admin để được cấp quyền truy cập.
   - Sau khi nhận được thông báo kích hoạt, bạn hãy khởi động lại ứng dụng.
3. Nhập Token: Sử dụng chức năng "Add" để dán danh sách Token (mỗi dòng một Token).
4. Nhập ID kênh thoại: Lấy ID kênh thoại Discord và dán vào ô "Channel ID".
5. Điều khiển: Sử dụng bảng điều khiển bên phải để thực hiện các lệnh cho nhóm tài khoản đã chọn.

## Cấu trúc thư mục và Lưu ý

- File thực thi (.exe): File chính để khởi động ứng dụng.
- settings.json: Tệp lưu trữ cấu hình bao gồm danh sách Token và các cài đặt cuối cùng. Tuyệt đối không chia sẻ tệp này cho người lạ để bảo vệ tài khoản.
- assets/: Thư mục chứa các tài nguyên giao diện như biểu tượng và hình ảnh.

## Lưu ý quan trọng

- Bản quyền được cấp dựa trên mã HWID của thiết bị. Việc thay đổi các linh kiện phần cứng quan trọng có thể dẫn đến thay đổi HWID và yêu cầu kích hoạt lại.
- Người dùng chịu trách nhiệm hoàn toàn về việc sử dụng các tài khoản (Token) trên ứng dụng, vui lòng tuân thủ các điều khoản dịch vụ của Discord.

---

Phát triển bởi gn027c.
