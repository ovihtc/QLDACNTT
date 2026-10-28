# Demo quy trình quản lý công việc – Nhóm 11

Đây là tình huống minh họa được tạo riêng để trình diễn quy trình. Không phải minh chứng tiến độ hoặc đóng góp thực tế của các thành viên. Không thay đổi ứng dụng trong G11.rar.

## Công việc minh họa

- Mã: DEMO-01 (mã nội bộ minh họa, không phải ID ClickUp).
- Tên: Bổ sung tiêu chí kiểm tra ngày hợp đồng.
- Người thao tác: tài khoản đang thực hiện demo; không gán đóng góp cho thành viên khác.
- File bàn giao: `demo/DEMO-01-hop-dong.md`.
- Nhánh: `demo/clickup-github`.
- Nghiệm thu: mô tả trường dữ liệu, tình huống ngày hợp lệ và ngày kết thúc trước ngày bắt đầu.

## Mở khi trình bày

1. Mở nhánh demo để xem task và sản phẩm bàn giao.
2. Mở Commits: commit đầu tạo task, commit tiếp theo bổ sung tiêu chí kiểm tra.
3. Mở Compare với main để xem thay đổi. Compare chưa phải Pull Request đã tạo hoặc đã merge.
4. Nếu cần PR, mở https://github.com/ovihtc/QLDACNTT/compare/main...demo/clickup-github?expand=1 rồi chọn Create pull request bằng tài khoản có quyền. Đặt tiêu đề `[DEMO] DEMO-01 – Bổ sung tiêu chí kiểm tra hợp đồng` và ghi rõ dữ liệu minh họa trong mô tả. Chưa cần merge.
5. Trên ClickUp, tạo task thật có tiêu đề `[DEMO] Kiểm tra ngày hợp đồng`, giao cho tài khoản tham gia demo, đặt hạn và dán đường dẫn nhánh/PR vào mô tả. ID task thật do ClickUp cấp; không dùng DEMO-01 để khẳng định tích hợp tự động.
6. Thành viên comment: “Đã bổ sung tiêu chí ngày hợp đồng. Nhờ kiểm tra”, kèm link commit/PR. Chuyển task sang Chờ kiểm tra.
7. Người kiểm tra mở thay đổi, đối chiếu 3 tiêu chí rồi comment kết quả thật và chuyển Hoàn thành nếu đạt.
8. Bật email cho comment/nhắc tên trong cài đặt thông báo ClickUp, dùng tài khoản thứ hai nhắc tên người nhận và kiểm tra hộp thư thực tế.

## Nói rõ khi cô hỏi

“Đây là tình huống demo quy trình. GitHub đã ghi nhận thay đổi thật trên nhánh riêng. Nhóm dùng link để đối chiếu công việc với sản phẩm. Tích hợp tự động, đổi trạng thái theo PR và email chỉ được khẳng định sau khi nhóm cấu hình và kiểm tra thực tế.”

Hiện bộ demo không cấu hình tích hợp ClickUp, không tạo thông báo email, không tạo Issue/PR qua API và không xác nhận chức năng hợp đồng trong ứng dụng đã chạy đúng. File tiêu chí là đặc tả minh họa, chưa phải kiểm thử ứng dụng.
