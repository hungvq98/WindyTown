# WindyTown – Cẩm nang nấu ăn

Trang web tĩnh nằm trong `index.html`. Mở file này bằng trình duyệt để xem trước tại máy.

## Cùng cập nhật

1. Tạo nhánh từ `main`.
2. Sửa `index.html`, kiểm tra trên máy và mở pull request.
3. Sau khi gộp vào `main`, Vercel sẽ tự triển khai bản mới nếu dự án đã kết nối với repo GitHub này.

Mỗi commit trực tiếp lên `main` cũng sẽ kích hoạt triển khai lên Vercel.

## Cấu hình Vercel

Kết nối repo `hungvq98/WindyTown` trong phần **Settings → Git** của dự án Vercel. Dùng nhánh Production là `main`, Framework Preset là **Other**, thư mục gốc là `.` và không cần lệnh build. Giữ thư mục `.vercel` ngoài Git vì nó chứa liên kết dự án riêng của từng máy.
