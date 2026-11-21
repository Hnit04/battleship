# Battleship Online

Game hải chiến 2 người chơi (1 file `index.html`).

- Xếp tàu bằng kéo thả, chạm để xoay ngang/dọc
- Hiệu ứng nổ khi bắn trúng, gợn sóng khi trượt
- Chơi online qua mã phòng 4 ký tự

Lưu ý: phần online dùng database của claude.ai Artifacts (`claude.use("db")`),
nên chỉ hoạt động khi chạy trên claude.ai. Để chạy ở nơi khác (GitHub Pages, Vercel...)
cần thay phần `db`/`user` bằng backend riêng (Firebase, Supabase, WebSocket...).
