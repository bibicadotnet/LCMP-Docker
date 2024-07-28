# LCMP-Docker


## Cài đặt
Trỏ DNS A về IP của VPS (domain.com và www.domain.com )

<a href="https://images.bibica.net/2024/07/2024-07-28-18-43-58.jpg"><img class="aligncenter size-full wp-image-27379" src="https://images.bibica.net/2024/07/2024-07-28-18-43-58.jpg" alt="2024 07 28 18 43 58" width="883" height="214" /></a>

Tiếp theo chạy:
```
git clone https://github.com/bibicadotnet/LCMP-Docker
cd ./LCMP-Docker
```
Thay đổi domain của bạn bên trong `.env` 

<a href="https://bibica.net/wp-content/uploads/2024/07/2024-07-28-18-48-43.jpg"><img class="aligncenter size-full wp-image-27381" src="https://bibica.net/wp-content/uploads/2024/07/2024-07-28-18-48-43.jpg" alt="2024 07 28 18 48 43" width="419" height="314" /></a>

Sau đó chạy
```
docker-compose up -d
```
Hiệu năng tổng thể khá tương đồng với bản [LCMP-Minimal](https://github.com/bibicadotnet/LCMP-Minimal), cũng không có gì ngạc nhiên, vì chúng gần như dùng cùng 1 cấu hình
