# Cách cài đặt client

Chuyên mục này là nơi hướng dẫn chi tiết cách cài các loại client khác nhau như Forge, Fabric, MCP (Version), Injection, ....

Trước khi cài client, cần xác định rõ client đó thuộc loại nào, và chạy trên phiên bản nào (Một số người cài client 1.12.2 vô 1.8.9 và ngược lại). Có thể check loại client tại: [https://github.com/MinusMC/jar-client-checker](https://minusmc.github.io/jar-client-checker/)

## Forge
Client: LiquidBounce Legacy (1.8.9), LiquidBounce 1.12.2 (client này đã bị xoá bởi CCBlueX), MinusBounce, FDPClient, NightX, ...

Các bước cài:
- Bước 1: Đảm bảo bạn đã cài Forge đúng phiên bản (hoặc ForgeOptifine với TLauncher, Legacy Launcher) trong Launcher và đã chạy ít nhất 1 lần.
- Bước 2: Đảm bảo bạn đã tải client từ nguồn chính thống và đã giải nén nếu là file zip, rar, 7z, ...
- Bước 3: Mở thư mục `.minecraft`
	+ Đối với TLauncher, Legacy Launcher, SkLauncher, ấn vào biểu tượng thư mục.
	+ Đối với các launcher khác, bấm tổ hợp phím Windows + R, nhập `%appdata%`, sau đó chọn vào folder `.minecraft`.
- Bước 4: Chọn vào thư mục mods (Bạn có thể tạo thư mục mods nếu không thấy).
- Bước 5: Sao chép và dán file bạn đã tải vào thư mục.
- Bước 6: Khởi động trò chơi.

## Fabric
Client: LiquidBounce Nextgen, ThunderHack Recode, ...

Các bước cài:
- Bước 1: Đảm bảo bạn đã cài Fabric đúng phiên bản trong Launcher và đã chạy ít nhất 1 lần.
- Bước 2: Đảm bảo bạn đã tải client từ nguồn chính thống và đã giải nén nếu là file zip, rar, 7z, ...
- Bước 3: Mở thư mục `.minecraft`
	+ Đối với TLauncher, Legacy Launcher, SkLauncher, ấn vào biểu tượng thư mục.
	+ Đối với các launcher khác, bấm tổ hợp phím Windows + R, nhập `%appdata%`, sau đó chọn vào folder `.minecraft`.
- Bước 4: Chọn vào thư mục mods (Bạn có thể tạo thư mục mods nếu không thấy).
- Bước 5: Sao chép và dán file bạn đã tải vào thư mục.
- Bước 6: Khởi động trò chơi.

Lưu ý quan trọng: Một số client có sử dụng ngôn ngữ Kotlin như LiquidBounce, bạn phải cài thêm `Fabric Language Kotlin` cùng với client.


## MCP (Version)

Client: Rise, Gothaj, Augustus b2.6, ...
Client MCP là client chứa 2 file (1 file jar và 1 file json).

Các bước cài:
- Bước 1: Đảm bảo bạn đã tải client từ nguồn chính thống và đã giải nén nếu là file zip, rar, 7z, ...
- Bước 2: Mở thư mục `.minecraft`
	+ Đối với TLauncher, Legacy Launcher, SkLauncher, ấn vào biểu tượng thư mục.
	+ Đối với các launcher khác, bấm tổ hợp phím Windows + R, nhập `%appdata%`, sau đó chọn vào folder `.minecraft`.
- Bước 3: Mở thư mục `versions`
- Bước 4: Tạo thư mục với tên là tên client (hoặc là tên file jar bạn vừa giải nén). 
- Bước 5: Sao chép và dán file jar và file json bạn đã tải về vào thư mục bạn vừa tạo
- Bước 6: Khởi động lại launcher, chọn client bạn vừa cài và khởi động.

## Lưu ý (phải đọc)

- Không thể cài client MCP dưới dạng Forge (Một số người nhầm tưởng có file jar là Forge nên đâm đầu cài client Forge).
- Đối với Forge, bạn có thể cài Optifine (nếu bạn chạy ForgeOptifine thì không cần thiết).
- Đối với Fabric, rất khuyến khích cài các mod tối ưu hoá (Sodium, Lithium, ...)
- Trong trường hợp xảy ra lỗi (đối với Forge và Fabric), hãy thử gỡ các mod bạn đã cài trên máy.
