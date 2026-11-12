# VNG Value – bản thử giao diện

Bản bấm thử giao diện và luồng nghiệp vụ của phần mềm quản lý thẩm định giá VNG Value (bản thiết kế mới).

**Mở bản thử:** https://phamlinh278work.github.io/vng-value-prototype/

Đây là bản bấm chuyển màn để góp ý thiết kế, chưa phải phần mềm thật:

- Ô nhập chưa gõ được, bấm Lưu luôn đi theo nhánh thành công.
- Toàn bộ dữ liệu trên màn hình là dữ liệu giả lập.
- Nút nào chưa có màn đích sẽ hiện ghi chú "chưa có trong demo".
- Phóng to để xem chi tiết: đặt chuột vào chỗ muốn xem rồi giữ Ctrl (Mac: Cmd hoặc Ctrl) và lăn chuột, hoặc chụm hai ngón trên touchpad; chỗ đó phóng to tại chỗ. Khi đã phóng to, giữ chuột kéo để di chuyển màn. Nút − / % / + ở góc phải dưới và Ctrl + / − / 0 cũng dùng được; thu nhỏ chỉ về lại cỡ ban đầu.

## Kịch bản thử chuỗi chính

1. **Đăng nhập** → bấm Đăng nhập → Chọn đơn vị → Tiếp tục → **Trang chủ "Việc của tôi"**.
2. **Trang chủ:** hàng "Xem theo vai trò" để đổi giữa 6 vai (kinh doanh, GĐ kinh doanh, chuyên viên, kiểm soát viên, **Trưởng phòng Nghiệp vụ**, Admin). Trang Trưởng phòng Nghiệp vụ có tải việc theo người, hàng chờ ký, hồ sơ có cờ rủi ro, SLA, cơ sở dữ liệu giá.
3. **Hợp đồng:** Thêm hợp đồng (mục đích, cơ sở giá trị, thời điểm thẩm định dự kiến, bên sử dụng kết quả) → Lưu → Duyệt hợp đồng.
4. **Giao việc:** tab Giao việc → Phân công → chọn người lập và thẩm định viên chịu trách nhiệm (bấm ô thẩm định viên để xem danh sách chọn).
5. **Khảo sát:** Lịch hẹn → Mở biên bản khảo sát; trên mobile: Lịch khảo sát → Bắt đầu khảo sát → Ký biên bản → Hoàn tất.
6. **Định giá:** Tài sản thẩm định → tab Tài sản so sánh → Bảng tính so sánh (điều chỉnh từng yếu tố, thống nhất mức giá, phiên bản đã khóa) → Thông báo sơ bộ.
7. **Chứng thư:** Tạo chứng thư → Xác nhận chứng thư (kiểm tra trước khi nộp: Lỗi / Cảnh báo / Ghi chú) → Nộp kiểm soát → Chấm chứng thư (checklist 7 mục).
8. **Ký và phát hành:** chứng thư đã chấm đạt → Ký chứng thư (TĐV và người ký thay mặt doanh nghiệp) → Đã phát hành, đã khóa → nút "…" để Đề nghị đính chính hoặc Đề nghị thu hồi.
9. **Tra cứu QR:** trang tra cứu hiện trạng thái chứng thư, giá trị bị ẩn sau mã xác thực.
10. **Bàn giao hồ sơ:** checklist thành phần hồ sơ, mã lưu trữ, hạn lưu 10 năm.
11. **Cài đặt:** Quy trình hợp đồng (bước bắt buộc bị khóa), Người dùng và phân quyền, Thẩm định viên, Ủy quyền ký.
12. **Báo cáo:** Quản trị, Cơ sở dữ liệu giá, Xuất hồ sơ kiểm tra, Gửi Bộ Tài chính.
13. **Kế toán và Tính năng đề xuất:** các màn gắn nhãn "Đề xuất" là phương án chưa được VNG xác nhận.

Menu bên trái bấm được ở mọi màn; nút cạnh logo thu gọn menu còn cột biểu tượng. Mỗi màn chi tiết có dòng "‹ Danh sách …" ở đầu để quay lại.

## Mobile app

Ở màn đăng nhập web bấm **"Dùng VNG Value trên điện thoại"**, hoặc mở thẳng trên điện thoại: https://phamlinh278work.github.io/vng-value-prototype/#s-1-91136

Thanh dưới có 5 mục: Việc của tôi, Hợp đồng, Quét QR, Thông báo, Tài khoản. Bấm ảnh đại diện ở đầu "Việc của tôi" để chuyển giữa góc nhìn Chuyên viên thẩm định và Giám đốc kinh doanh.

## Chưa có trong bản này

- Nhóm Kế toán và các màn gắn nhãn "Đề xuất" là phương án chưa được VNG xác nhận; số liệu và quy tắc trên đó (ví dụ bậc hoa hồng) chỉ để minh họa.
- Nút "Xuất Excel", "Lưu thay đổi" ở Cài đặt chưa có hiệu lực.
- Bảng thông báo, menu tài khoản, menu thao tác chứng thư hiện giữa màn và chưa đóng khi bấm ra ngoài.
- Bản đồ vị trí tài sản, trợ lý AI. Nút "Xuất ZIP", "Xuất file theo mẫu" ở Báo cáo chỉ minh họa.

## Trong repo

| Đường dẫn | Nội dung |
| --- | --- |
| `index.html` | Bản bấm thử, một file, mở được không cần mạng |
| `docs/design-kit.md` | Tóm tắt design system: màu, chữ, khoảng cách, component |
| `docs/figma-screen-kit.md` | Quy ước và bộ hàm dựng màn hình trong Figma |
| `assets/logo/` | Logo VNG Value |
