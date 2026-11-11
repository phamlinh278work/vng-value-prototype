# VNG Value – bản thử giao diện

Bản bấm thử giao diện và luồng nghiệp vụ của phần mềm quản lý thẩm định giá VNG Value (bản thiết kế mới).

**Mở bản thử:** https://phamlinh278work.github.io/vng-value-prototype/

Đây là bản bấm chuyển màn để góp ý thiết kế, chưa phải phần mềm thật:

- Ô nhập chưa gõ được, bấm Lưu luôn đi theo nhánh thành công.
- Toàn bộ dữ liệu trên màn hình là dữ liệu giả lập.
- Nút nào chưa có màn đích sẽ hiện ghi chú "chưa có trong demo".
- Xem tốt nhất trên máy tính, cửa sổ rộng từ 1440 px.

## Kịch bản thử chuỗi chính

1. **Đăng nhập** → bấm Đăng nhập → Chọn đơn vị → Tiếp tục → **Trang chủ "Việc của tôi"**.
2. **Trang chủ:** bấm một việc trong danh sách để mở đúng màn xử lý. Bấm nhãn vai trò cạnh lời chào để xem trang chủ của vai trò khác (Giám đốc kinh doanh, Chuyên viên thẩm định, Kiểm soát viên, Admin). Nút "Tùy chỉnh" để bật/tắt các khối.
3. **Hợp đồng:** Thêm hợp đồng → bấm ô Khách hàng để mở hộp chọn → Lưu hợp đồng → Duyệt hợp đồng → xác nhận.
4. **Giao việc:** trên hợp đồng đã duyệt, mở tab Giao việc → Phân công chuyên viên → Phân công.
5. **Định giá:** menu Tài sản thẩm định → Thêm tài sản → tab Tài sản so sánh → Chọn tài sản so sánh → Mở bảng tính so sánh → Xem thông báo sơ bộ → Lưu vào hồ sơ.
6. **Chứng thư:** Tạo chứng thư → Xác nhận chứng thư → Chấm chứng thư → Lưu kết quả chấm → Cập nhật phát hành → Lưu.
7. **Bàn giao hồ sơ:** menu Chứng thư → tab Bàn giao hồ sơ → Bàn giao hồ sơ → Bàn giao → Duyệt bàn giao.
8. **Tra cứu QR:** ở chứng thư đã chấm đạt bấm In chứng thư, rồi bấm vào ô mã QR trên trang xem trước.
9. **Cài đặt:** menu Cài đặt → Quy trình hợp đồng: bước thực hiện, tình trạng hợp đồng, tình trạng chứng thư.

Menu bên trái bấm được ở mọi màn; nút cạnh logo thu gọn menu còn cột biểu tượng. Mỗi màn chi tiết có dòng "‹ Danh sách …" ở đầu để quay lại.

## Mobile app

Ở màn đăng nhập web bấm **"Dùng VNG Value trên điện thoại"**, hoặc mở thẳng trên điện thoại: https://phamlinh278work.github.io/vng-value-prototype/#s-1-91136

Thanh dưới có 5 mục: Việc của tôi, Hợp đồng, Quét QR, Thông báo, Tài khoản. Bấm ảnh đại diện ở đầu "Việc của tôi" để chuyển giữa góc nhìn Chuyên viên thẩm định và Giám đốc kinh doanh.

## Chưa có trong bản này

- Công nợ, quỹ, hoa hồng, đề nghị thanh toán, nhân viên, phân quyền.
- Nút "Lưu thay đổi" ở màn Cài đặt chưa có hiệu lực: bản thử chỉ minh họa giao diện.
- Bản đồ vị trí tài sản, trợ lý AI, ký số.
- Các tình huống lỗi khi lưu và danh sách trống (đã thiết kế, chưa nối vào bản bấm thử).

## Trong repo

| Đường dẫn | Nội dung |
| --- | --- |
| `index.html` | Bản bấm thử, một file, mở được không cần mạng |
| `docs/design-kit.md` | Tóm tắt design system: màu, chữ, khoảng cách, component |
| `docs/figma-screen-kit.md` | Quy ước và bộ hàm dựng màn hình trong Figma |
| `assets/logo/` | Logo VNG Value |
