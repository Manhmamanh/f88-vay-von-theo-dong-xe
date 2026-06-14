# F88 — Vay vốn theo dòng xe

Trang giới thiệu sản phẩm vay cầm cố ô tô / xe máy của F88, kèm trang quản trị dữ liệu.

## Nội dung
- **`index.html`** — Trang web khách xem (chọn hãng, lọc, xem hạn mức, đăng ký vay).
- **`admin.html`** — Trang quản trị: thêm/sửa/xóa hãng & xe, đổi logo, ảnh, hạn mức. Xuất ra `f88-xe-data.json`.
- **`f88-xe-assets/`** — Logo các hãng (`logos/`) và ảnh xe (`cars/`).
- **`f88-xe-data.json`** — (tùy chọn) dữ liệu do trang admin xuất ra; nếu có, `index.html` sẽ ưu tiên dùng file này.

## Cách cập nhật nội dung
1. Mở `admin.html`, chỉnh sửa (mọi thay đổi tự lưu trong trình duyệt để xem thử).
2. Bấm **"Tải file dữ liệu (.json)"** → được file `f88-xe-data.json`.
3. Đưa file `f88-xe-data.json` lên repo này (cùng cấp với `index.html`) → khách sẽ thấy nội dung mới.

## Truy cập
Trang web: `https://<tài-khoản>.github.io/<tên-repo>/`
Trang quản trị: `https://<tài-khoản>.github.io/<tên-repo>/admin.html`
