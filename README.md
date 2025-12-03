# 🎁 Album - Minh Ánh

> Một tấm thiệp kỹ thuật số tương tác với slideshow ảnh 9:16 dành cho Minh Ánh, được thiết kế với hiệu ứng biển cả pastel và các tính năng UX nâng cao.

## ✨ Tính Năng

### 📸 Slideshow
- **9 Ảnh Interactive** - Carousel dọc 9:16 với chuyển động mịn
- **Điều Hướng Đa Cách** - Nút bấm, phím mũi tên, vuốt, click indicator
- **Autoplay Thông Minh** - Tự động phát, tạm dừng khi hover, có thanh tiến trình

### 🎨 Giao Diện & Hiệu Ứng
- **iOS 16 Design** - Glassmorphism, backdrop blur, spring animations
- **Modal 9:16** - Slideshow hiển thị ở trung tâm như popup card
- **Hiệu Ứng Hạt Cát Bay** - Ánh sáng lấp lánh rơi xuống
- **Confetti Animation** - Hiệu ứng kỷ niệm khi like

### 🎵 Âm Nhạc & Sound
- **Background Music** - Nhạc nền lặp lại, điều chỉnh âm lượng
- **Volume Control** - Slider điều chỉnh 0-100%
- **Mute Button** - Bật/tắt âm nhạc nhanh chóng

### ⚙️ Cài Đặt & Tùy Chỉnh
- **Speed Control** - Slider điều chỉnh tốc độ autoplay (1-10)
- **Dark Mode** - Chế độ tối/sáng, lưu vào localStorage
- **Settings Modal** - Giao diện cài đặt hiện đại

### 📱 Tương Tác & Feedback
- **Image Indicators** - Dot navigation hiển thị vị trí ảnh
- **Progress Bar** - Thanh tiến trình autoplay realtime
- **Toast Notifications** - Thông báo mịn cho các actions
- **Double Tap to Like** - Double tap ảnh để like
- **Pull to Refresh** - Kéo xuống để reset album

### 🎯 Tính Năng Mobile
- **Gesture Controls** - Vuốt, double tap, pull-to-refresh
- **Fullscreen Mode** - Xem toàn màn hình
- **Like & Share** - Yêu thích với confetti, chia sẻ link
- **Responsive Design** - Tối ưu cho mọi kích cỡ màn hình

## 🛠️ Công Nghệ Sử Dụng

- **HTML5** - Semantic structure
- **CSS3** - Animations, gradients, backdrop filters
- **JavaScript (Vanilla)** - No frameworks, pure interactions
- **Tailwind CSS** - Utility-first styling
- **Audio API** - Background music playback

## 📦 Cấu Trúc Project

```
helloCoTo/
├── index.html          # Tệp chính (HTML + CSS + JS)
├── assets/             # Thư mục ảnh
│   ├── image1.jpg
│   ├── image2.jpg
│   ├── ... (9 ảnh tổng cộng)
│   └── nhac.mp3        # File nhạc nền
├── README.md           # Tài liệu này
├── .gitignore          # Ignore files
└── LICENSE             # MIT License
```

## 🚀 Cách Sử Dụng

### Mở Locally
1. Clone repository:
```bash
git clone https://github.com/linhtinh1chut/helloCoTo.git
cd helloCoTo
```

2. Mở `index.html` trong trình duyệt:
```bash
# Windows
start index.html

# macOS
open index.html

# Linux
xdg-open index.html
```

### Hoặc Deploy lên Web
- Upload lên GitHub Pages, Netlify, Vercel, v.v
- File `index.html` là tất cả những gì bạn cần!

## 📸 Hướng Dẫn Sử Dụng

### Điều Hướng Slideshow
- **Nút Mũi Tên** (‹ ›) - Chuyển ảnh trước/sau
- **Phím Mũi Tên** - ← → để chuyển ảnh, Space để play/pause
- **Vuốt Chuột** - Vuốt trái/phải để chuyển ảnh
- **Click Indicator** - Click vào dot để jump đến ảnh

### Các Nút Điều Khiển
- **MUSIC** - Bật/tắt nhạc nền
- **PLAY/PAUSE** - Bật/tắt autoplay tự động
- **FULL** - Toàn màn hình / Thoát
- **LIKE** - Yêu thích (double tap cũng được)
- **SHARE** - Chia sẻ link

### Cài Đặt (⚙️ button)
- **Tốc độ Autoplay** - Slider 1-10
- **Âm lượng Nhạc** - Slider 0-100%
- **Dark Mode** - Toggle bật/tắt

### Mobile Gestures
- **Double Tap** - Like ảnh
- **Pull to Refresh** - Kéo xuống để reset
- **Swipe Left/Right** - Chuyển ảnh

## 🎨 Màu Sắc Sử Dụng

- **Ocean Blue** - `#3a55a0` - Màu chính
- **Coral** - `#f87171ce` - Accent color
- **Sand** - `#F7E7CE` - Secondary color
- **Pastel Gradient** - Teal → Blue → Navy

## 🔧 Tùy Chỉnh

### Thay đổi Tên / Thông Điệp
Sửa trong `index.html`:
```html
<h2>From Cô Tô with love</h2>
<p>_tmanh410_</p>
```

### Thay đổi Ảnh
Đặt 9 ảnh vào thư mục `assets/`:
- `image1.jpg` đến `image9.jpg`

### Thay đổi Nhạc
Thay `assets/nhac.mp3` bằng file nhạc của bạn

### Điều chỉnh Màu
Sửa CSS variables ở đầu style:
```css
:root {
    --color-coral: #f87171ce;
    --color-sand: #F7E7CE;
    --color-ocean-blue: #3a55a0;
}
```

## 📱 Browser Support

- ✅ Chrome 90+
- ✅ Firefox 88+
- ✅ Safari 14+
- ✅ Edge 90+
- ✅ Mobile browsers (iOS Safari, Chrome Android)

**Lưu ý:** Fullscreen API có thể bị hạn chế trên một số trình duyệt.

## 🎯 Performance

- **File Size** - ~35KB (HTML + CSS + JS inline)
- **Load Time** - < 1 giây (không kể ảnh)
- **No Dependencies** - Chỉ dùng vanilla JS + Tailwind CDN
- **Optimized** - Minified CSS/JS, lazy-loading images

## 📄 License

MIT License - Tự do sử dụng, sửa đổi, và phân phối.

## 🤝 Đóng Góp

Nếu có ý tưởng cải tiến, hãy fork repo và submit pull request!

## 💬 Liên Hệ

📧 Email: linhtinh1chut@example.com
💬 Instagram: [@_tmanh410_](https://instagram.com)

---

**Tạo với ❤️ cho Minh Ánh** 🌊✨
