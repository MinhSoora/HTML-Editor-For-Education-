# HTML-Editor-For-Education-
# 📝 Trình Soạn Thảo HTML - VS Code Style

> Một trình soạn thảo HTML nhẹ, mạnh mẽ với giao diện giống VS Code, hoàn toàn bằng tiếng Việt

![Version](https://img.shields.io/badge/version-1.0.0-blue.svg)
![License](https://img.shields.io/badge/license-MIT-green.svg)
![Size](https://img.shields.io/badge/size-lightweight-orange.svg)

## ✨ Tính Năng Nổi Bật

### 🎯 Giao Diện Chuyên Nghiệp
- **Thiết kế giống VS Code** - Giao diện tối màu, thân thiện với mắt
- **Bố cục 2 cột** - Code bên trái, xem trước bên phải
- **Thanh trạng thái** - Hiển thị số ký tự và trạng thái lỗi
- **100% tiếng Việt** - Tất cả nội dung đều bằng tiếng Việt

### 💡 Gợi Ý Thẻ HTML Thông Minh
- Tự động gợi ý khi gõ `<`
- Hỗ trợ hơn 40 thẻ HTML phổ biến
- Điều hướng bằng phím mũi tên và Enter
- Đóng gợi ý bằng phím Esc

### 📁 Quản Lý Nhiều File
- Tạo file mới không giới hạn
- Chuyển đổi giữa các file bằng tabs
- Xóa file (luôn giữ ít nhất 1 file)
- Sidebar hiển thị danh sách file

### 🖼️ Quản Lý Hình Ảnh
- Upload nhiều ảnh cùng lúc
- Thư viện ảnh dạng lưới
- Click vào ảnh để chèn vào code
- Xóa ảnh không cần dùng

### ⚡ Xem Trước Trực Tiếp
- Cập nhật theo thời gian thực
- Không cần refresh thủ công
- Hiển thị chính xác HTML

### 🔍 Kiểm Tra Lỗi Tự Động
- Phát hiện thẻ chưa đóng
- Kiểm tra thẻ đóng không khớp
- Gợi ý thêm thuộc tính `alt` cho `<img>`
- Hiển thị lỗi rõ ràng, dễ hiểu

### 💾 Lưu Và Mở Dự Án
- Lưu toàn bộ dự án vào file `.minhsoora`
- Bao gồm tất cả file code và hình ảnh
- Mở lại dự án đầy đủ khi cần

## 🚀 Cách Sử Dụng

### Bắt Đầu Nhanh
1. Mở file HTML trong trình duyệt
2. Bắt đầu viết code trong ô editor
3. Xem kết quả ngay lập tức ở bên phải

### Sử Dụng Gợi Ý Thẻ
```
1. Gõ dấu < trong editor
2. Bắt đầu gõ tên thẻ (ví dụ: div)
3. Dùng ↑↓ để chọn thẻ
4. Nhấn Enter để chèn thẻ
```

### Làm Việc Với Nhiều File
- **Tạo file mới:** Click "**+ File Mới**"
- **Chuyển file:** Click vào tab hoặc tên file ở sidebar
- **Đóng file:** Click dấu **×** trên tab (giữ ít nhất 1 file)

### Upload Và Sử Dụng Hình Ảnh
1. Click "**📷 Tải Ảnh**"
2. Chọn một hoặc nhiều ảnh
3. Ảnh xuất hiện trong thư viện
4. Click vào ảnh để chèn vào code
5. Hover vào ảnh và click **×** để xóa

### Lưu Và Mở Dự Án
**Lưu dự án:**
1. Click "**💾 Lưu Dự Án**"
2. File `project.minhsoora` sẽ được tải về
3. Lưu file này để mở lại sau

**Mở dự án:**
1. Click "**📂 Mở Dự Án**"
2. Chọn file `.minhsoora` đã lưu
3. Tất cả file và ảnh sẽ được khôi phục

## 📋 Ví Dụ Sử Dụng

### Tạo Trang Web Đơn Giản
```html
<!DOCTYPE html>
<html>
<head>
    <title>Trang Web Của Tôi</title>
</head>
<body>
    <h1>Chào Mừng!</h1>
    <p>Đây là trang web đầu tiên của tôi.</p>
</body>
</html>
```

### Chèn Hình Ảnh
1. Upload ảnh vào thư viện
2. Click vào ảnh
3. Code tự động được chèn:
```html
<img src="data:image/..." alt="Hình ảnh" style="max-width: 100%; height: auto;">
```

## 🎯 Các Phím Tắt

| Phím | Chức Năng |
|------|-----------|
| `<` | Mở gợi ý thẻ HTML |
| `↑` `↓` | Di chuyển trong danh sách gợi ý |
| `Enter` | Chọn thẻ từ gợi ý |
| `Esc` | Đóng gợi ý |

## ⚠️ Lưu Ý

### Lỗi Thường Gặp
- **Thẻ chưa đóng:** Mỗi thẻ mở `<div>` phải có thẻ đóng `</div>`
- **Thẻ đóng sai thứ tự:** `<div><p></div></p>` ❌ → `<div><p></p></div>` ✅
- **Thiếu thuộc tính alt:** Nên thêm `alt` cho thẻ `<img>`

### Thẻ Tự Đóng
Các thẻ sau không cần thẻ đóng:
- `<img>`, `<br>`, `<hr>`, `<input>`, `<meta>`, `<link>`

## 🛠️ Công Nghệ Sử Dụng

- **HTML5** - Cấu trúc trang
- **CSS3** - Giao diện đẹp mắt
- **Vanilla JavaScript** - Không cần thư viện ngoài
- **FileReader API** - Xử lý file và ảnh
- **Blob API** - Lưu dự án

## 📦 Kích Thước

- **Tổng dung lượng:** < 20KB
- **Không cần cài đặt**
- **Không cần internet** (chạy offline)
- **Không cần server**

## 🌟 Ưu Điểm

✅ **Nhẹ** - Chỉ 1 file HTML duy nhất  
✅ **Nhanh** - Không lag, mượt mà  
✅ **Dễ dùng** - Giao diện trực quan  
✅ **Offline** - Hoạt động không cần mạng  
✅ **Tiếng Việt** - 100% nội dung tiếng Việt  
✅ **Miễn phí** - Sử dụng hoàn toàn miễn phí  

## 🎓 Phù Hợp Cho

- 🎨 Học viên mới học HTML
- 👨‍💻 Developer cần test nhanh
- 📚 Giáo viên dạy HTML
- 🚀 Người cần tạo prototype nhanh
- 💼 Làm landing page đơn giản

## 📝 Định Dạng File `.minhsoora`

File `.minhsoora` là file JSON chứa:
```json
{
  "files": [
    {
      "id": 1,
      "name": "index.html",
      "content": "..."
    }
  ],
  "images": [
    {
      "id": 123456,
      "name": "photo.jpg",
      "data": "data:image/jpeg;base64,..."
    }
  ]
}
```

## 🤝 Đóng Góp

Nếu bạn có ý tưởng cải thiện, hãy:
1. Fork dự án
2. Tạo branch mới
3. Commit thay đổi
4. Tạo Pull Request

## 📄 Giấy Phép

MIT License - Sử dụng tự do cho mọi mục đích

## 🙏 Cảm Ơn

Cảm ơn bạn đã sử dụng **Trình Soạn Thảo HTML**!

---

**Made with ❤️ in Vietnam 🇻🇳**

💡 **Tips:** Nhấn `Ctrl + S` trong trình duyệt để lưu file HTML này vào máy và sử dụng bất cứ lúc nào!
