# SUNNY SPEAK 5 ☀️

Website luyện nói tiếng Anh lớp 5 — Ms Tran Ngoc Diep, Le Kim Lang Primary School.

## Chạy thử
Mở `index.html` để xem giao diện. Để sử dụng micro, xuất bản trên HTTPS (GitHub Pages) và dùng Chrome/Edge hỗ trợ Web Speech API.

## Đăng lên GitHub Pages
1. Tạo repository mới (ví dụ `sunny-speak-5`) trên GitHub.
2. Tải lên ba file `index.html`, `style.css`, `app.js` ở thư mục gốc.
3. Vào Settings → Pages → Build and deployment → Deploy from a branch → `main` / `(root)` → Save.
4. Chờ triển khai, mở đường dẫn Pages được GitHub cung cấp.

## Giới hạn cần biết
- Bộ câu hiện là nội dung **minh họa tự biên soạn** theo các chủ đề. Chưa phải dữ liệu đầy đủ, xác minh từng câu theo sách Global Success 5. Một số tên Unit cần đối chiếu với mục lục chính thức.
- Nhận diện giọng nói sử dụng Web Speech API (phụ thuộc trình duyệt và kết nối). Điểm hiển thị là độ tương đồng từ ngữ, **không phải đánh giá phát âm chuyên dụng bằng AI**.
- Chưa có tài khoản, cơ sở dữ liệu trực tuyến, giáo viên xem kết quả tập trung hoặc AI hội thoại thật.
- Tiến độ được lưu bằng localStorage trên thiết bị hiện tại; có thể xuất CSV.
- Nội dung, tên Unit và câu hỏi chỉnh trong `app.js`, biến `units` và `phrases`.
