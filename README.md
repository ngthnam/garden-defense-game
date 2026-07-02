# Garden Defense Mini 🌱🧟

Một mini game web lấy cảm hứng từ gameplay thủ thành khu vườn, viết bằng **HTML/CSS/JavaScript thuần**.

> Lưu ý: Đây là game demo tự viết, không sử dụng tên thương mại, hình ảnh hay asset chính thức của bất kỳ game nào.

## Tính năng

- Giao diện khu vườn đẹp hơn với nền trời, mây, hiệu ứng nắng, card cây và animation.
- Grid 5 hàng x 9 cột.
- 3 loại cây:
  - 🌿 Pea Ranger: bắn zombie.
  - 🌻 Sun Bloom: tạo năng lượng mặt trời.
  - 🪵 Wood Guardian: chặn zombie.
- Zombie sinh theo wave và nhanh dần.
- Có điểm, máu nhà, năng lượng và best score lưu bằng `localStorage`.
- Có nút **Hack Mode / ∞ Energy** để trồng cây mà không bị trừ năng lượng.
- Có thể chạy trực tiếp bằng GitHub Pages.

## Cách chơi

1. Bấm **Bắt đầu chơi**.
2. Chọn cây trong shop.
3. Click vào ô đất để trồng cây.
4. Thu năng lượng mặt trời để trồng thêm cây.
5. Bật **Hack Mode / ∞ Energy** nếu muốn chơi thoải mái hơn.
6. Có thể bấm phím **H** để bật/tắt nhanh chế độ năng lượng ∞.
7. Ngăn zombie đi hết khu vườn.

## Chạy local

Mở file `index.html` trên trình duyệt.

## Bật GitHub Pages

1. Vào **Settings** của repository.
2. Chọn **Pages**.
3. Source: **Deploy from a branch**.
4. Branch: `main`.
5. Folder: `/root`.
6. Bấm **Save**.

Sau khi GitHub Pages build xong, game sẽ chạy tại:

```text
https://ngthnam.github.io/garden-defense-game/
```

## Gợi ý nâng cấp tiếp

- Thêm hình ảnh sprite PNG/SVG riêng cho cây và zombie.
- Thêm âm thanh bắn đạn, thu nắng, zombie bị hạ.
- Thêm level/wave boss.
- Thêm màn hình chọn độ khó.
- Tối ưu điều khiển trên mobile.
