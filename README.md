# VNG Value – bản thử giao diện

Bản bấm thử giao diện và luồng nghiệp vụ của phần mềm quản lý thẩm định giá VNG Value (bản thiết kế mới).

**Mở bản thử:** https://phamlinh278work.github.io/vng-value-prototype/

**Bản thử giao diện mới (2 màn: danh sách và chi tiết hợp đồng):** https://phamlinh278work.github.io/vng-value-prototype/ban-moi/

Đây là bản bấm chuyển màn để góp ý thiết kế, chưa phải phần mềm thật:

- Ô nhập chưa gõ được, bấm Lưu luôn đi theo nhánh thành công.
- Toàn bộ dữ liệu trên màn hình là dữ liệu giả lập.
- Nút nào chưa có màn đích sẽ hiện ghi chú "chưa có trong demo".
- Xem tốt nhất trên máy tính, cửa sổ rộng từ 1440 px.

## Kịch bản thử chuỗi chính

1. **Đăng nhập** → bấm Đăng nhập → Chọn đơn vị → Tiếp tục.
2. **Hợp đồng:** Thêm hợp đồng → bấm ô Khách hàng để mở hộp chọn → Lưu hợp đồng → Duyệt hợp đồng → xác nhận.
3. **Giao việc:** trên hợp đồng đã duyệt, mở tab Giao việc → Phân công chuyên viên → Phân công.
4. **Định giá:** menu Tài sản thẩm định → Thêm tài sản → tab Tài sản so sánh → Chọn tài sản so sánh → Mở bảng tính so sánh → Xem thông báo sơ bộ → Lưu vào hồ sơ.
5. **Chứng thư:** Tạo chứng thư → Xác nhận chứng thư → Chấm chứng thư → Lưu kết quả chấm → Cập nhật phát hành → Lưu.
6. **Bàn giao hồ sơ:** menu Chứng thư → tab Bàn giao hồ sơ → Bàn giao hồ sơ → Bàn giao → Duyệt bàn giao.
7. **Tra cứu QR:** ở chứng thư đã chấm đạt bấm In chứng thư, rồi bấm vào ô mã QR trên trang xem trước.

Menu bên trái bấm được ở mọi màn: Hợp đồng, Lịch hẹn, Khách hàng, Đối tác, Tài sản thẩm định, Tài sản so sánh, Mẫu định giá, Yếu tố so sánh, Chứng thư, Biểu mẫu in, Báo cáo.

## Chưa có trong bản này

- Công nợ, quỹ, hoa hồng, đề nghị thanh toán, nhân viên, phân quyền.
- Bản đồ vị trí tài sản, trợ lý AI, ký số.
- Các tình huống lỗi khi lưu và danh sách trống (đã thiết kế, chưa nối vào bản bấm thử).

## Trong repo

| Đường dẫn | Nội dung |
| --- | --- |
| `index.html` | Bản bấm thử, một file, mở được không cần mạng |
| `docs/design-kit.md` | Tóm tắt design system: màu, chữ, khoảng cách, component |
| `docs/figma-screen-kit.md` | Quy ước và bộ hàm dựng màn hình trong Figma |
| `assets/logo/` | Logo VNG Value |
