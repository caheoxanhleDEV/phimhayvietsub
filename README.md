# PhimHayVietSub

Bản PC + PE compact.

## Lưu dữ liệu
Dữ liệu tài khoản, phim, cài đặt, lượt thích, theo dõi, bình luận và lịch sử được lưu theo origin trong trình duyệt. Bản này bổ sung **Sao lưu dữ liệu / Khôi phục** trong Cài đặt để tránh mất dữ liệu khi thay phiên bản website hoặc đổi máy.

### Quy trình cập nhật an toàn
1. Mở website bản đang dùng.
2. Đăng nhập tài khoản OWNER.
3. Vào **Cài đặt → Sao lưu dữ liệu** và tải file `.json`.
4. Thay website bằng ZIP mới.
5. Mở website mới, đăng nhập và chọn **Khôi phục**, rồi chọn file backup.

Lưu ý: video blob trong IndexedDB của trình duyệt không được đóng gói vào file JSON; video cần được tải lên lại/backend nếu muốn đồng bộ giữa nhiều máy.

Website: https://caheoxanhledev.github.io/phimhayvietsub8/
