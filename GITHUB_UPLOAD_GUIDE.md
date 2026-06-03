# Hướng dẫn Upload index.html lên GitHub → Cloudflare tự deploy

## Cách 1 — Qua GitHub Web (đơn giản nhất)

1. Mở: https://github.com/SGMIA26/sandboxstartup-news
2. Tìm file `index.html` trong danh sách
3. Nhấn vào file → nhấn icon ✏️ (Edit this file)
4. Nhấn **Ctrl+A** để chọn hết → **Delete** để xóa
5. Paste nội dung file `index.html` mới vào
6. Scroll xuống → nhấn **"Commit changes"**
7. Cloudflare tự động deploy trong 1-2 phút

## Cách 2 — Drag & Drop (nếu Cách 1 lag)

1. Mở: https://github.com/SGMIA26/sandboxstartup-news
2. Nhấn **"Add file"** → **"Upload files"**
3. Kéo file `index.html` mới vào
4. Nhấn **"Commit changes"**
5. GitHub tự replace file cũ

## Kiểm tra Cloudflare deploy

Sau khi commit:
1. Vào: https://dash.cloudflare.com/bec4ac6e50afa24388861ee2a2940c1c/workers/services/view/sandboxstartup-news/production
2. Xem tab "Deployments" → deploy mới xuất hiện
3. Mở sandboxstartup.vn → Ctrl+Shift+R (hard refresh)
