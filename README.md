# Garden Defense Mini 🌱🧟

Một mini game web lấy cảm hứng từ gameplay thủ thành khu vườn, viết bằng **HTML/CSS/JavaScript thuần**.

> Lưu ý: Đây là game demo tự viết, không sử dụng tên thương mại, hình ảnh hay asset chính thức của bất kỳ game nào.

## Tính năng

- Grid 5 hàng x 9 cột
- 3 loại cây:
  - 🌿 Pea Plant: bắn zombie
  - 🌻 Sun Bloom: tạo năng lượng mặt trời
  - 🪵 Wood Wall: chặn zombie
- Zombie sinh theo wave
- Có điểm, máu nhà, năng lượng
- Có thể chạy trực tiếp bằng GitHub Pages

## Cách chơi

1. Bấm **Bắt đầu chơi**.
2. Chọn cây trong shop.
3. Click vào ô đất để trồng cây.
4. Thu năng lượng mặt trời để trồng thêm cây.
5. Ngăn zombie đi hết khu vườn.

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

## Gợi ý nâng cấp

- Thêm nhiều loại zombie
- Thêm âm thanh
- Thêm level/wave boss
- Lưu high score bằng `localStorage`
- Tối ưu điều khiển trên mobile
