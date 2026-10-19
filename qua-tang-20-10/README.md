# Website quà tặng 20/10 💗

Website tĩnh dùng HTML, CSS và JavaScript thuần. Không cần cài Node.js hay backend.

## Chạy local

1. Giải nén thư mục.
2. Mở `index.html` bằng Chrome/Edge.
3. Bấm **Bật nhạc** để bật nhạc nền tự tạo bằng Web Audio API (trình duyệt yêu cầu thao tác người dùng).
4. Phần tạo QR cần Internet để tải thư viện QRCode.js từ CDN.

Bạn cũng có thể chạy bằng VS Code + extension Live Server để có trải nghiệm gần giống môi trường deploy hơn.

## Cá nhân hóa lời nhắn

Mở `index.html` bằng VS Code, tìm phần `<article class="letter">` và sửa lời chúc thành lời nhắn của bạn. Bạn có thể thay câu “Chị à” hoặc chữ ký cuối thư cho đúng cách xưng hô của hai người.

Có thể sửa tiêu đề, các thẻ chúc mừng, nội dung “phiếu nhận một buổi đi chơi vui vẻ” ngay trong file HTML.

## Deploy lên GitHub Pages

1. Đăng nhập GitHub và tạo repository mới, ví dụ `qua-tang-20-10`.
2. Đặt repository ở chế độ **Public** để GitHub Pages miễn phí có thể xuất bản dễ dàng.
3. Tải `index.html` lên thư mục gốc của repository (nút **Add file → Upload files**), rồi **Commit changes**.
4. Vào **Settings → Pages**.
5. Trong phần **Build and deployment**, chọn **Deploy from a branch**.
6. Chọn branch `main`, folder `/(root)`, rồi bấm **Save**.
7. Đợi GitHub build xong. URL thường có dạng:
   `https://TEN-USER.github.io/qua-tang-20-10/`
   Nếu repository của bạn có tên khác, URL sẽ thay đổi tương ứng.
8. Mở URL đó trên điện thoại để kiểm tra giao diện, thư, nút bật/tắt nhạc và các nút tương tác.

> Nếu tài khoản/repository có cấu hình khác, hãy dùng chính URL được hiển thị ở mục **Settings → Pages** thay vì đoán URL.

## Tạo QR trỏ tới website

1. Mở website đã deploy bằng URL `https://...`.
2. Kéo xuống phần **Tạo QR để gửi tặng chị**.
3. URL sẽ được điền sẵn theo địa chỉ trang đang mở; kiểm tra lại URL.
4. Bấm **Tạo mã QR**.
5. Bấm **Tải QR PNG** để lưu hình.
6. Dùng điện thoại quét QR từ màn hình khác hoặc bản in thử để chắc chắn URL mở được.

Bạn cũng có thể dán URL công khai vào ô URL rồi tạo QR trên máy local. Không tạo QR từ `localhost` hoặc `file:///...` vì chị sẽ không truy cập được.

## Lưu ý

- Website không có backend và không thu thập dữ liệu.
- Nhạc nền được tạo bằng Web Audio API, không tải nhạc có bản quyền từ bên ngoài. Âm thanh là giai điệu điện tử đơn giản.
- Google Fonts và QRCode.js được tải từ CDN nên cần Internet để hiển thị font và tạo QR.
- Nếu muốn trang riêng tư, lưu ý rằng GitHub Pages công khai sẽ cho người có URL truy cập. Đừng đưa thông tin cá nhân nhạy cảm vào thư.
