GYMSYS – BẢN TÍCH HỢP DỮ LIỆU GIẢ LẬP

Các file trong thư mục:
1. index.html: trang mặc định để GitHub Pages mở dashboard.
2. gymsys_customer_retention.html: dashboard theo dõi tín hiệu rủi ro hội viên.
3. gymsys_customer_data.html: trang xem dữ liệu theo chi nhánh và sheet.
4. gymsys_data.json: dữ liệu hội viên tổng hợp + các sheet nhỏ.
5. gymsys_checkins.json: 87.863 lượt check-in, tải riêng khi mở sheet Check-in.

Cách chạy:
- Đặt cả 4 file cùng một thư mục.
- Mở thư mục bằng VS Code.
- Dùng extension Live Server, mở gymsys_customer_retention.html.
- Trang dữ liệu truy cập qua liên kết "Dữ liệu đầu vào".
- Có thể tải toàn bộ thư mục lên cùng một GitHub Pages repository.

Lưu ý:
- Dữ liệu được tổng hợp từ 3 file Excel giả lập, mốc snapshot 07/11/2026.
- Số điện thoại và ngày sinh đã được loại khỏi dữ liệu web demo.
- Chỉ số rủi ro là điểm heuristic minh họa từ quy tắc, không phải xác suất churn do ML huấn luyện.
- Doanh thu lịch sử không phải CLV, lợi nhuận hoặc doanh thu kế toán đã kiểm chứng.
- Vì website dùng fetch JSON, không nên mở HTML bằng cách double-click file://; hãy dùng Live Server hoặc GitHub Pages.
