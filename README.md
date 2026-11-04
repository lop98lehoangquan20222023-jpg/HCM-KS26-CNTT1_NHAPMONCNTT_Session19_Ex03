# Phần 1:Báo cáo phân tích:
- Input(dấu hiệu):
1. Các tài khoản cá nhân liên tục gửi cảnh báo đăng nhập bất thường.
2. Nhận được cảnh báo bảo mật,phiên đăng nhập lạ hoặc yêu cầu mã xác thực OTP không rõ nguồn gốc.
- Process:
1. Ngắt kết nối wifi ngay lập tức để ngăn mã độc tiếp tục xâm nhập vào máy.
2. Dùng thiết bị chưa bị mã độc xâm nhập thu hồi các quyền và đăng xuất ra khỏi các thiết bị khác.
3. Thay đổi mật khẩu các tài khoản sau khi thu hồi quyền.
4. Làm sạch và cài lại hệ điều hành:quét các mã độc bằng các phần mềm diệt viruss sau đó tiến hành cài lại hệ điều hành nếu các phần cứng quan trọng hay các phần mềm gặp tổn hại.
- Output:
1. Ngắt toàn bộ kết nối với mã độc với tài khoản cá nhân.
2. Thay đổi các mật khẩu cá nhân quan trọng.
3. Máy tính được làm sạch có thể sử dụng lại được bình thường.
# Phần 2:Hướng dẫn triển khai nhanh
## 1.Thay đổi mật khẩu bằng thiết bị khác:
1. Đăng nhập vào tài khoản cần thay đổi mật khẩu:
2. Tiến hành đổi mật khẩu.
3. Sau khi thay đổi mật khẩu chọn vào đăng xuất khỏi các thiết bị khác.
## 2. Cách thu hồi token trên Github
1. Thu hồi Personal Access Tokens: Vào Settings -> Developer settings -> Personal access tokens -> Chọn token cũ và bấm Delete/Revoke.
2. Thu hồi OAuth Apps: Vào Settings -> Applications -> Authorized OAuth Apps -> Chọn ứng dụng lạ và bấm Revoke access.