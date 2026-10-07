# Quy trình chỉnh sửa sau này

## 1. Sửa nội dung giáo dục

Ưu tiên chỉnh qua module Kho giáo dục khi production CMS được triển khai.

Có thể thay đổi:
- Tên module/bài học
- Nội dung
- Video
- Tài liệu
- Câu hỏi
- Bài tập
- Hướng dẫn KVT

Không cần sửa workflow.

## 2. Sửa giao diện

Trong V1 hiện tại, giao diện nằm trong `index.html`.

Quy trình:
1. Tạo branch mới.
2. Sửa `index.html`.
3. Chạy test thủ công theo `docs/TESTING.md`.
4. Commit với thông điệp rõ ràng.
5. Push branch.
6. Mở Pull Request.
7. Review.
8. Merge vào `main`.
9. GitHub Actions tự deploy GitHub Pages.

## 3. Khi chuyển sang production

Tách frontend thành component/module và chuyển dữ liệu khỏi localStorage sang PostgreSQL + API. Không thay đổi business workflow chỉ vì thay đổi công nghệ.