# Portfolio site (GitHub Pages)

Trang portfolio cá nhân của Lê Minh Hoàng, dựng bằng Jekyll + theme `minima`
(theme có sẵn của GitHub Pages, không cần build ở máy).

## Cấu trúc

- `index.md` — nội dung trang chủ (giới thiệu + danh sách project)
- `_config.yml` — cấu hình site (tiêu đề, theme, email...)
- `.gitignore` — bỏ qua thư mục build

## Cách deploy lên GitHub Pages

1. Tạo repo mới trên GitHub (ví dụ tên `portfolio`).
2. Push toàn bộ thư mục này lên nhánh `main`.
3. Vào **Settings → Pages** của repo:
   - **Source:** Deploy from a branch
   - **Branch:** `main` / `(root)`
   - Save.
4. Chờ 1–2 phút, trang sẽ xuất hiện tại:
   `https://<username>.github.io/portfolio/`

## Chạy thử ở máy (tùy chọn)

Cần cài Ruby + Bundler, sau đó:

```bash
gem install jekyll bundler
jekyll serve
```

Xem tại `http://localhost:4000`.
