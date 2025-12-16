# Bio Webpage - Chú Bé Đần

Phiên bản hiện tại: **0.0.3**

Trang web cá nhân sinh động để giới thiệu thông tin của Chú Bé Đần (Soníc).

![Preview của trang web](assets/avatar.jpg)

## Giới thiệu

Trang web cá nhân này được thiết kế để hiển thị thông tin và sở thích của Chú Bé Đần. Với thiết kế tối giản và hiệu ứng hiện đại, trang web mang đến trải nghiệm thú vị cho người truy cập.

Soníc - một người vừa đẹp trai vừa lạnh lùng đến từ Tây Ninh.

## Tính năng

- **Giao diện người dùng hiện đại** với hiệu ứng đẹp mắt
- **Enter overlay** với hiệu ứng glitch text và zoom-out animation (style guns.lol)
- **Hiệu ứng nội dung** - Các phần tử xuất hiện tuần tự với animation sau khi enter
- **Responsive design** - Tối ưu cho desktop, tablet (768px-1024px) và mobile (≤420px)
- **Dynamic links** - Liên kết được tải từ file JSON
- **Nhạc nền** với autoplay sau khi click enter
- **Touch support** - Hiệu ứng hover giả cho thiết bị cảm ứng
- **Badges** với gradient màu và hiệu ứng tương tác

## Công nghệ sử dụng

- HTML5
- CSS3 (CSS Variables, Flexbox, Media Queries)
- JavaScript (ES6+, Async/Await)
- [Google Fonts](https://fonts.google.com/) - Space Grotesk, Space Mono
- [Anime.js](https://animejs.com/) - Animation library

## Cấu trúc thư mục

```
sonic2109.github.io/
├── index.html          # Trang chính
├── CNAME               # Custom domain
├── README.md           # Documentation
├── assets/
│   ├── avatar.jpg      # Ảnh đại diện
│   └── music/
│       └── tieng-cho-lofi.mp3  # Nhạc nền
└── data/
    └── links.json      # Dữ liệu liên kết mạng xã hội
```

## Cài đặt và Sử dụng

1. Clone repository:
```bash
git clone https://github.com/sonic2109/sonic2109.github.io.git
```

2. Chạy với Live Server (VS Code) hoặc local web server

3. Cá nhân hóa:
   - Sửa `data/links.json` để thay đổi liên kết
   - Thay ảnh `assets/avatar.jpg`
   - Sửa nội dung trong `index.html`
   - Thay nhạc tại `assets/music/`

## Changelog

### v0.0.3
- Thêm enter overlay với hiệu ứng glitch text style guns.lol
- Thêm zoom-out animation và ripple effect khi click enter
- Sửa layout links với flexbox (bỏ negative margin)
- Thêm tablet media query (768px-1024px)
- Xóa code không sử dụng (#clock CSS/JS, SVG sprite div)
- Nội dung animate sau khi overlay đóng

### v0.0.2
- Thêm nhạc nền với overlay
- Cải thiện responsive design

### v0.0.1
- Phiên bản đầu tiên

## Liên hệ

- Facebook: [Nguyễn Minh Tân](https://www.facebook.com/MinhTan2109/)
- Instagram: [minhtan.2109](https://www.instagram.com/minhtan.2109/)
- Discord: [Server](https://discord.gg/JUv2WzWje3)
- Website: [nhimsub.com](https://nhimsub.com/)

## Giấy phép

© 2025 Soníc - Mọi quyền được bảo lưu