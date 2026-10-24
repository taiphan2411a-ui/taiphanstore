# TechZone - WEB2053 ASM FINAL (JavaScript nâng cao)

## Chạy trên máy tính
1. Cài Node.js LTS.
2. Giải nén project và mở Terminal tại thư mục `TechZone_JS_ASM`.
3. Chạy `npm install`.
4. Chạy `npm run dev` để mở website tại http://localhost:5173
   - Vite frontend
   - JSON Server API tại http://localhost:3000
5. Tài khoản admin demo: `admin` / `TechZone@123`

## Tính năng bám đề ASM
- 5 danh mục, 20 sản phẩm laptop có ảnh minh họa.
- Trang chủ, tìm kiếm, lọc danh mục, trang chi tiết, giỏ hàng.
- Admin: CRUD sản phẩm/danh mục/bài viết, cấu hình SEO sản phẩm/bài viết/hệ thống.
- Cấu hình liên kết Facebook, Facebook Pixel, GA4, Search Console.
- 3 bài viết blog có SEO và backlink website/Fanpage.
- Đơn hàng demo lưu vào db.json.
- Responsive cho desktop/mobile.

## Lưu ý
- Dữ liệu mẫu dùng JSON Server, phù hợp bài tập/demo; không dùng làm hệ thống thương mại thật.
- Ảnh sản phẩm lấy từ Unsplash qua Internet, cần có mạng khi xem.
- Mã GA4, Search Console, Pixel phải thay bằng mã thật của bạn. Website chưa tự tạo tài khoản Google/Facebook, chưa tự đăng bài Fanpage/Blogger hay gửi email thật.
- Trước khi đưa lên hosting, kiểm tra gói hosting có chạy Node.js/API không. Hosting tĩnh thông thường không tự chạy JSON Server.
- Không dùng tài khoản/mật khẩu demo trên website công khai; cần bổ sung xác thực an toàn nếu triển khai thật.
