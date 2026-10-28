# DEMO-01 – Bổ sung tiêu chí kiểm tra ngày hợp đồng

> Tình huống minh họa, không phải báo cáo tiến độ dự án thực tế.

## Yêu cầu

Biểu mẫu hợp đồng cần có mã nhân viên, loại hợp đồng, ngày bắt đầu và ngày kết thúc.

## Tiêu chí bàn giao tài liệu

- [x] Có danh sách trường dữ liệu cần nhập.
- [x] Có ví dụ khoảng ngày hợp lệ.
- [x] Có ví dụ ngày kết thúc trước ngày bắt đầu và cách xử lý mong muốn.

Các ô trên chỉ thể hiện độ đầy đủ của tài liệu demo, không phải kết quả chạy phần mềm.

## Ví dụ cần kiểm tra khi triển khai ứng dụng

| Trường hợp | Ngày bắt đầu | Ngày kết thúc | Kết quả mong muốn |
|---|---|---|---|
| Khoảng ngày hợp lệ | 2026-11-01 | 2027-10-31 | Cho phép lưu khi các trường khác hợp lệ |
| Ngày kết thúc trước ngày bắt đầu | 2026-11-01 | 2026-10-31 | Từ chối lưu, báo lỗi tại trường ngày kết thúc |

## Bàn giao để review

Tài liệu demo đã bổ sung hai tình huống. Người trình bày mở phần diff của commit để chỉ ra các dòng vừa thay đổi. Người kiểm tra xác nhận trên task ClickUp thật sau khi đọc tài liệu; bộ demo không tự tạo kết quả nghiệm thu.
