# Smart-Aquarium
Dự án **_Hồ Cá Thông Minh_** cung cấp giải pháp chăm sóc cá từ xa cho những người thường xuyên đi du lịch hay công tác xa nhà nhiều ngày.
Các thiết bị của hồ cá có thể được điều khiển từ xa thông qua kết nối mạng Internet ngay cả khi thiết bị điều khiển không nằm cùng một mạng.
Thiết bị điều khiển hồ cá là thiết bị có thể kết nối mạng Internet như Laptop, PC, SmartPhone .

## Languages & Request Software
+ Languages: `C++` `CSS` `HTML` `Batch File`
+ Request Software: [`Ngrok`](https://ngrok.com/) [`Arduino IDE`](https://www.arduino.cc/en/software)

## Features
**_Các tính năng của hồ cá:_**
  + Đổ thức ăn cho cá
  + Bật tắt đèn Led RGB
  + Quan sát hồ cá thông qua camera

**_Cách sử dụng:_**
Để có thể nạp code và điều khiển hồ cá từ xa ta làm các bước sau:
- `Bước 1:` Tiến hành nạp code ESP32 Camera, sau khi nạp xong sẽ xuất hiện 1
địa chỉ IP.

![image](https://user-images.githubusercontent.com/95084615/179446492-46d62f5b-e805-4c54-804c-2acf67303471.png)
- `Bước 2:` Sao chép địa chỉ IP bỏ vào file ESP32-CAM.bat rồi nhấn Enter.

![image](https://user-images.githubusercontent.com/95084615/179447446-b88bbd0b-aa13-423e-976e-648d95ab5a8f.png)
- `Bước 3:` Một địa chỉ IP mới sẽ xuất hiện, hãy sao chép địa chỉ IP đó (`http://0.tcp.ap.ngrok.io:15336`)

![image](https://user-images.githubusercontent.com/95084615/179447505-87021cee-90da-46d6-8fa5-b47acca087e1.png)
- `Bước 4:` Dán địa chỉ IP vừa sao chép bỏ vào file code của ESP8266.ino

![image](https://user-images.githubusercontent.com/95084615/179448421-0ec4e605-3391-439c-8bfd-e563c24b853d.png)
- `Bước 5:` Tiến hành chạy code ESP8266 sẽ xuất hiện được địa chỉ IP như hình bên dưới.

![image](https://user-images.githubusercontent.com/95084615/179447400-9062a4a6-7a7b-4ae8-8351-eaf26cd1fa10.png)
- `Bước 6:` Sao chép địa chỉ IP đó rồi dán vào trong file ESP8266.bat.

![image](https://user-images.githubusercontent.com/95084615/179447641-ffdec01b-e754-47e4-a643-bcfa00ac069c.png)
- `Bước 7:` Nhấn Enter, một địa chỉ IP mới sẽ xuất hiện, đây là địa chỉ IP public nên chúng ta chỉ cần có địa chỉ IP đó là sẽ điều khiển được hồ cá cho dù ở bất cứ nơi nào chỉ cần có internet.

![image](https://user-images.githubusercontent.com/95084615/179447760-c3a9b099-be94-4e41-8858-ff4b349984b2.png)

![image](https://user-images.githubusercontent.com/95084615/179447855-232cf966-2171-454e-9df7-d24a92233efa.png)

## Version
`Version 1` -- Đây không phải là phiên bản cuối cùng và chúng có thể sẽ được cập nhật trong tương lai.

## Installs
- [Download Zip](https://github.com/QuocViet132/Smart-Aquarium/archive/refs/heads/master.zip)   Lưu các file `.bat` tại thư mục cài đặt Ngrok
- [Install Ngrok](https://ngrok.com/download)
- [Install Arduino IDE](https://www.arduino.cc/en/software)
