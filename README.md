# VICTORIA Bar & Lounge — Static Responsive Website

Bộ source static gồm:

- `index.html` — one-page landing page, SEO meta, JSON-LD LocalBusiness, Google Maps embed.
- `style.css` — responsive UI, dark premium lounge style, mobile CTA cố định.
- `script.js` — menu mobile, trạng thái mở cửa theo giờ Việt Nam, đổi ngôn ngữ VI/EN/JP, form tạo tin nhắn đặt bàn.
- `assets/logo.svg`, `assets/og-card.svg` — logo/OG image tạm thời.

## Cách chạy local

Mở trực tiếp `index.html` trong trình duyệt, hoặc chạy:

```bash
python -m http.server 8080
```

Sau đó mở `http://localhost:8080`.

## Deploy nhanh

Có thể upload nguyên thư mục này lên:

- Netlify
- Vercel static
- GitHub Pages
- Cloudflare Pages
- hosting cPanel/Nginx bình thường

## Thông tin đã dùng

Thông tin công khai tìm được:

- Tên: VICTORIA Bar & Lounge
- Địa chỉ: 5 Ng. 81 P. Linh Lang, Giảng Võ/Cống Vị, Hà Nội
- Điện thoại: 098 289 0703
- Giờ mở cửa: 19:00–02:00
- Không ghi nhận ngày nghỉ cố định
- Instagram công khai: `@msvictoria_2025`
- Một số nguồn mô tả theo nhóm karaoke/bar/lounge và slogan social: “Cocktails / Good Music / Good Vibes”

## Việc nên thay trước khi dùng quảng cáo thật

1. Thay 4 moodboard block trong phần `#gallery` bằng ảnh thật của quán.
2. Nếu có menu/giá thật, thêm một section `Menu` để tăng conversion.
3. Nếu có link Google Business Profile chính xác, thay link Google Maps query bằng link chính thức.
4. Nếu quán dùng Zalo/Facebook Page/booking form riêng, thêm link chính thức vào CTA.
5. Kiểm tra lại địa chỉ theo Google Maps vì nguồn công khai có chỗ ghi `Cống Vị`, có chỗ ghi `Giảng Võ`.

## Visual assets added

The `assets/` folder now includes generated placeholder SVG visuals and icons for a luxury bar/lounge style:

- `hero-lounge.svg`
- `gallery-champagne.svg`
- `gallery-cocktail.svg`
- `gallery-lounge.svg`
- `gallery-night.svg`
- `icon-cocktail.svg`, `icon-mic.svg`, `icon-sparkle.svg`, `icon-map.svg`, `icon-phone.svg`, `icon-clock.svg`, `icon-instagram.svg`
- `pattern-stars.svg`

These are fake/local illustration assets, not real venue photos. Replace them later with real photos if you want higher advertising trust.


## Copy update

Đã làm lại văn phong tiêu đề và nội dung theo hướng luxury lounge: sang hơn, thật hơn, cuốn hút hơn; bỏ các câu mang tính ghi chú kỹ thuật khỏi phần hiển thị chính.
