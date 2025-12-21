# Website Nguyen Thanh Gallery

Website tĩnh phong cách gallery hiện đại cho họa sĩ Nguyễn Thành.

## Cách sử dụng

1. **Mở website**: Mở file `index.html` trực tiếp trong trình duyệt web (Chrome, Firefox, Safari, Edge)
2. **Không cần cài đặt**: Website hoạt động ngay mà không cần build tools, npm, hay bất kỳ thứ gì khác
3. **Chỉnh sửa**: Mở các file HTML/CSS bằng text editor yêu thích để chỉnh sửa nội dung

## Cấu trúc file

```
/
├── index.html              # Trang chủ
├── about.html              # Giới thiệu nghệ sĩ
├── artworks.html           # Danh mục tác phẩm
├── exhibitions.html        # Triển lãm & giải thưởng
├── news.html               # Danh sách tin tức
├── contact.html            # Thông tin liên hệ
├── news-*.html             # 5 trang chi tiết tin tức
└── assets/
    ├── css/
    │   └── style.css       # Toàn bộ CSS styling
    └── images/             # Thư mục chứa hình ảnh
        └── README.md       # Danh sách hình ảnh cần có
```

## Thêm hình ảnh

1. Xem file `assets/images/README.md` để biết danh sách hình ảnh cần thiết
2. Thêm các file hình ảnh vào thư mục `assets/images/` với đúng tên file
3. Khuyến nghị:
   - Hero image: độ phân giải cao (>2000px chiều rộng)
   - Artworks/series banners: 1200-1920px
   - Thumbnails: 800-1200px
   - Nén tối ưu để website tải nhanh

## Triển khai lên Internet

Có thể upload toàn bộ thư mục lên:
- **Netlify**: Kéo thả thư mục vào netlify.com (miễn phí)
- **GitHub Pages**: Push code lên GitHub repository
- **Web hosting truyền thống**: Upload qua FTP
- **Vercel, Cloudflare Pages**: Kết nối với Git repository

## Chỉnh sửa nội dung

- **Header/Footer**: Sửa trong mỗi file HTML (phần `<header>` và `<footer>`)
- **Màu sắc**: Sửa CSS variables trong `assets/css/style.css` (dòng 7-17)
- **Spacing**: Điều chỉnh các biến `--spacing-*` trong CSS
- **Typography**: Thay đổi font-family, font-size trong CSS

## Tính năng

✅ Responsive design (tự động điều chỉnh cho mobile/tablet/desktop)  
✅ Phong cách gallery tối giản, thanh lịch  
✅ Không cần JavaScript  
✅ Tối ưu SEO cơ bản  
✅ Tải nhanh, không phụ thuộc  

## Hỗ trợ

Email: nguyentrangartist78@gmail.com

