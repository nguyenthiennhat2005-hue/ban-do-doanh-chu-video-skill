# Bản Đồ Doanh Chủ — bộ skill video và kịch bản

**Một file ZIP tổng hợp**, cập nhật **25/11/2026**, dành cho Bản Đồ Doanh Chủ / Bản Đồ Doanh Nghiệp.

[**Tải toàn bộ gói ZIP**](https://github.com/nguyenthiennhat2005-hue/ban-do-doanh-chu-video-skill/releases/latest/download/ban-do-doanh-chu-video-skill-2026-11-25.zip) · [Trang phát hành](https://github.com/nguyenthiennhat2005-hue/ban-do-doanh-chu-video-skill/releases/latest)

Giải nén rồi mở `ban-do-doanh-chu-video/SKILL.md` để sử dụng. Gói có **131 tệp**, khoảng **32.9 MiB**, gồm:

- Skill tổng hợp và **4 skill nguồn** đã nạp: viết Reels kinh doanh, sub/chuyển cảnh của kênh, SeeTheLight dựng video và SeeTheLight kịch bản–Vbee.
- **42 kịch bản**, các bản hook/thân bài lịch sử và quy trình kể chuyện tập trung 15–18 giây đầu.
- Nội dung liên quan từ hai chat: **55 lượt** của “kịch bản bản đồ doanh chủ” và **63 lượt** của “Phân tích video Bản đồ doanh chủ”; có bản Markdown và JSON, chỉ gồm tin nhắn người dùng/câu trả lời cuối.
- Khung xanh, logo tròn đã chốt, SVG chỉnh sửa; các khung AIM được lưu riêng.
- Quy tắc ảnh thật, hook không lặp ảnh body, ảnh ngang 16:9 sát mép, sub karaoke tách khỏi ảnh, pan/zoom mượt và chuyển cảnh đa dạng.
- Hai track nhạc AIM, cách đo/cân nhạc **rõ như video 19**, một dòng nguồn tin cố định và nguồn riêng cho từng ảnh.
- **Dự án bài 28 hoàn chỉnh**: ảnh, giọng Vbee, nhạc, mốc từ, SRT, renderer, mã kiểm và MP4 mẫu đã dựng lại.

## Bắt đầu

1. Tải ZIP, giải nén và đọc `SKILL.md`.
2. Để dựng lại bài mẫu, dùng môi trường Python có các gói trong `requirements-verified.txt`, rồi chạy từ thư mục gốc gói:

```sh
python3 examples/bai-28/du-an/render.py
python3 examples/bai-28/du-an/verify.py
```

3. Khi làm tập mới, dùng đúng kịch bản/MP3 mới nhất và kiểm lại nguồn. Dữ liệu 01–42 là bản lưu theo thời điểm đã làm, không phải tin luôn mới.

`MANIFEST.json` trong ZIP lưu danh mục/SHA-256 từng tệp. [SHA256SUMS.txt](SHA256SUMS.txt) dùng kiểm tệp ZIP tải về. Gói không chứa cookies, khóa API, mật khẩu hoặc mô hình AI; đường dẫn máy cá nhân đã thay bằng biến. Các tài nguyên bên thứ ba giữ thông tin nguồn và giấy phép đi kèm trong `THIRD-PARTY.md`.

Bản dựng mẫu đã qua kiểm cấu trúc, render, giải mã toàn bộ MP4 và cân bằng âm thanh so với video 19. Báo cáo trong dự án ghi rõ chưa nghe kiểm thủ công hoặc kiểm phát lại thời gian thực.
