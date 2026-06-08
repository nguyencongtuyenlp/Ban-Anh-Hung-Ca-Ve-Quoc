# Bản Anh Hùng Ca Vệ Quốc

Trang web sách minh họa tương tác tái hiện hành trình kháng chiến chống Mỹ cứu nước (1954–1975).
Sản phẩm sáng tạo của **TeamaiAI1810-ADS**.

🔗 **Xem trực tuyến:** https://nguyencongtuyenlp.github.io/Ban-Anh-Hung-Ca-Ve-Quoc/

## Tính năng
- **Sách lật** nhúng từ Heyzine — đọc trọn cuốn sách ngay trên trang, lật như sách thật.
- **Thư viện trang** — nhấn vào từng trang để phóng to xem cận cảnh.
- **Nhạc nền** (`nhac-nen.mp3`) với nút bật/tắt.
- Hiệu ứng: chữ vàng lấp lánh, bụi vàng bay, bìa nghiêng 3D, đếm số liệu, thanh tiến độ đọc…

## Cấu trúc
| File | Mô tả |
|------|------|
| `index.html` | Trang web hoàn chỉnh, **đã nhúng sẵn toàn bộ hình ảnh** — mở trực tiếp là chạy. |
| `index.template.html` | Bản nguồn có placeholder `__COVER__`, `__P01__`..`__P12__`, `__FLAGS__`. |
| `b64/` | Dữ liệu ảnh base64 dùng để dựng lại `index.html`. |
| `assets/` | Ảnh JPG gốc của bìa và 12 trang. |
| `nhac-nen.mp3` | Nhạc nền. |

> Trang cần kết nối Internet để hiển thị sách lật Heyzine và phông chữ Google.

© 2026 TeamaiAI1810-ADS. All rights reserved.
