# Locket Gold + Spotify — VINHDAT

- `Locket4conBòVinhdat.conf` và `Locket4conBòVinhdat.sgmodule` đã được kết hợp với ba quy tắc Spotify từ `spotifyPre-iKiS.conf`.
- Các file Locket JS trong `scripts/` được giữ nguyên.
- DNS `LocketGold_VINHDAT.mobileconfig` được giữ nguyên với máy chủ `https://my.ublockdns.com/z451ak95`. DNS hoạt động cho hệ thống và không cấp quyền Premium.
- Các script Spotify **chưa được sao chép vào ZIP** vì chưa tải và kiểm tra được mã nguồn. Cấu hình tham chiếu trực tiếp đến `app2smile/rules` qua `script-path`. Nếu các URL không tồn tại hoặc không tương thích Shadowrocket, tính năng Spotify sẽ không hoạt động.
- Không bật đồng thời file `.conf` độc lập và module `.sgmodule` chứa cùng quy tắc để tránh chạy script trùng.
- Chỉ bật MITM cho các hostname bạn hiểu và tin cậy.
