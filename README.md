# UEH Innovation Platform — Đặc tả và demo

Website tĩnh bằng tiếng Việt phục vụ kiểm duyệt nghiệp vụ và bàn giao Dev.

## Nội dung
- Quản lý hồ sơ startup
- Knowledge Base (không có Thuật ngữ)
- AI Assistant
- AI Screening

Hệ thống đánh giá chưa được đặc tả. AI Assistant và AI Screening chỉ minh họa theo kịch bản; chưa tích hợp mô hình AI.

## Cấu trúc
- index.html: trang chính
- style.css: giao diện
- app.js: demo hồ sơ startup
- specification.js: đặc tả hồ sơ startup
- knowledge-base.js: đặc tả và demo kho tri thức
- ai-assistant.js: đặc tả và demo trợ lý
- ai-screening.js: đặc tả và demo sàng lọc

## Sử dụng
Không cần cài thư viện hoặc build. Phục vụ thư mục bằng một web server tĩnh, ví dụ `python3 -m http.server 8000`, rồi mở http://localhost:8000.

Đặt các file này trong cùng thư mục ở repository. Giữ index.html cùng cấp với các file CSS/JS. Gói ZIP phải được giải nén trước khi đưa nội dung lên repository.

## Dữ liệu
Dữ liệu mẫu và chỉnh sửa demo được lưu bằng localStorage trên từng trình duyệt/origin. Chuyển sang địa chỉ khác sẽ có vùng dữ liệu riêng. Gói mã nguồn không mang theo thay đổi demo đã lưu trong trình duyệt.

## Bàn giao Dev
Phạm vi đã thống nhất và chi tiết còn đề xuất được phân biệt trong từng module. Đọc các quy tắc, ngoại lệ, tiêu chí nghiệm thu và điểm cần chốt trước khi triển khai platform thật. Không lấy bộ tiêu chí hoặc điểm demo làm chuẩn tuyển chọn UII.
