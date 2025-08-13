# Mạch led đơn MKE-M01 10mm single LED module

## Giới thiệu

Mạch led đơn MKE-M01 10mm single LED module sử dụng loại LED kích thước lớn 10mm giúp bạn dễ dàng ứng dụng trong các mô hình xe, trang trí,..., mạch gồm có 4 phiên bản với các màu sắc: Trắng, Xanh lá, Vàng, Đỏ.

Mạch led đơn MKE-M01 10mm single LED module thuộc **hệ sinh thái phần cứng Robotics MakerEdu** nên có thể sử dụng trực tiếp an toàn với các mạch điều khiển trung tâm ở cả hai mức điện áp 3.3VDC và 5VDC như: Arduino, Raspberry Pi, Jetson Nano, Micro:bit,....với chuẩn kết nối Connector XH2.54 thông dụng.

## Thông số kỹ thuật

- Điện áp hoạt động: 5VDC
- Chuẩn giao tiếp: Digital
- Điện áp giao tiếp: TTL 3.3VDC/5VDC
- Có 4 phiên bản màu sắc: Trắng , Xanh Lá, Vàng, Đỏ.
- Sử dụng LED kích thước 10mm.
- Tích hợp Transistor giúp giảm dòng tiêu thụ và bảo vệ các chân GPIO của mạch xử lý.
- Sử dụng trực tiếp an toàn với các board mạch giao tiếp ở cả hai mức điện áp 3.3VDC và 5VDC như: Arduino, Raspberry Pi, Jetson Nano, Micro:bit,....
- Bổ sung thêm các thiết kế ổn định, chống nhiễu.
- Chuẩn kết nối: connector XH2.54 3Pins
- Thuộc hệ sinh thái phần cứng Robotics MakerEdu, tương thích tốt nhất khi sử dụng với các mạch điều khiển trung tâm của MakerEdu và MakerEdu Shield.

## Hình ảnh sản phẩm

![MKE_M01](/image/MKE_M01_1.jpg)

![MKE_M01](/image/MKE_M01_2.jpg)

## Kích thước sản phẩm

![MKE_M01](/image/MKE_M01_3.jpg)

## Các chân tín hiệu

![MKE_M01](/image/MKE_M01_2.jpg)

<table><thead>
  <tr>
    <th>MKE-M01</th>
    <th>Ghi chú</th>
  </tr></thead>
<tbody>
  <tr>
    <td>GND</td>
    <td>Chân cấp nguồn âm 0VDC</td>
  </tr>
  <tr>
    <td>5V</td>
    <td>Chân cấp nguồn dương 5VDC</td>
  </tr>
  <tr>
    <td>SIG</td>
    <td>Chân tín hiệu Digital In</td>
  </tr>
</tbody>
</table>

<table><thead>
  <tr>
    <th>SIG (Digital In)</th>
    <th>Trạng thái</th>
  </tr></thead>
<tbody>
  <tr>
    <td>TTL HIGH</td>
    <td>Hoạt động (On)</td>
  </tr>
  <tr>
    <td>TTL LOW</td>
    <td>Không hoạt động (Off)</td>
  </tr>
</tbody>
</table>

## Hướng dẫn sử dụng

### Các thiết bị sử dụng trong bài hướng dẫn

#### Arduino

- [Mạch Vietduino Uno (Arduino Uno Compatible)](https://www.makerlab.vn/vuno)
- [Mạch MakerEdu Shield for Vietduino](https://www.makerlab.vn/vietduinosd)
- [Mạch led đơn MKE-M01 10mm single LED module](https://www.makerlab.vn/mkem01)
- [Mạch màn hình MKE-M07 LCD1602 I2C Display Module](https://www.makerlab.vn/mkem07)

#### mBlock

- [Mạch MakerEdu Creator (Arduino Uno Compatible)](https://www.makerlab.vn/creator)
- [Mạch led đơn MKE-M01 10mm single LED module](https://www.makerlab.vn/mkem01)
- [Mạch màn hình MKE-M07 LCD1602 I2C Display Module](https://www.makerlab.vn/mkem07)

#### Micro:bit:

- [Mạch Micro:bit V2](https://hshop.vn/products/kit-hoc-lap-trinh-stem-cho-tre-em-micro-bit-v2) hoặc các phiên bản tương thích.
- [Mạch MakerEdu Shield for Micro:bit](https://www.makerlab.vn/microbitsd)
- [Mạch led đơn MKE-M01 10mm single LED module](https://www.makerlab.vn/mkem01)
- [Mạch màn hình MKE-M07 LCD1602 I2C Display Module](https://www.makerlab.vn/mkem07)

### Hướng dẫn sử dụng với Arduino (Code C)
  
[Hướng dẫn cài đặt phần mềm, nạp chương trình, cài đặt bộ thư viện Arduino cơ bản.](https://github.com/makerlabvn/Arduino-Vietduino)

- Tải và cài đặt [phần mềm Arduino tại đây.](https://www.arduino.cc/en/software)
- Trong **Tools / Library Manager**, tìm và cài đặt bộ thư viện tổng hợp **"MAKERLABVN" by MakerLab.vn**
- Mở chương trình mẫu **"MKE_M01_Single_LED_LCD_Serial"** tại **File / Examples / MAKERLABVN / Module / MKE_M01_Single_LED_LCD_Serial** hoặc [tải chương trình mẫu tại đây](/arduino)
- Chọn board là **Arduino Uno** (mạch Vietduino Uno tương thích với Arduino Uno), chọn đúng cổng **COM Port** của mạch và tiến hành nạp chương trình.
- Kết nối mạch **Vietduino Uno** với **MakerEdu Shield**, kết nối **Module LED** vào cổng **[D10]**. Cấp nguồn qua cổng USB của Vietduino Uno để thấy chương trình hoạt động.

### Hướng dẫn lập trình với mBlock (kéo thả khối)

[Hướng dẫn cài đặt phần mềm, nạp chương trình, cài đặt Extension mBlock cơ bản.](https://github.com/makerlabvn/mBlock-MakerEdu-Creator)

- Tải và cài đặt phần mềm mBlock 5 ([Windows](https://www.mediafire.com/file/ma55iajd7glwmbo/%255BMakerLab.vn%255D_mBlock_V5.4.3_for_Windows.zip/file) / [Mac Intel](https://www.mediafire.com/file/pjfngy6d7ktb55f/%255BMakerLab.vn%255D_mBlock_V5.4.3_for_Mac_Intel.zip/file) / [Mac M1M2](https://www.mediafire.com/file/mfdkgpgnpa7uv2s/%255BMakerLab.vn%255D_mBlock_V5.4.3_for_Mac_M1M2.zip/file))
- Thêm Device **"MakerEdu Creator"** by MakerEduVN
- Thêm Extension **"Upload Mode Broadcast"** by mBlock Official
- Thêm Extension **"MakerEdu Hardware"** by MakerEduVN
- Mở [chương trình mẫu tại đây](/mBlock5), kết nối MakerEdu Creator với máy tính và nạp chương trình.
- Kết nối **Module LED** vào cổng **[D10]** và **màn hình LCD** vào cổng **[I2C]** trên MakerEdu Creator, **cấp nguồn qua cổng USB** của MakerEdu Creator để thấy chương trình hoạt động.

### Hướng dẫn lập trình với Micro:bit (kéo thả khối)

[Hướng dẫn nạp chương trình, cài đặt Extension Micro:bit cơ bản.](https://github.com/makerlabvn/MakeCode-microbit)

- Khởi động phần mềm MakeCode tại: [https://makecode.microbit.org/](https://makecode.microbit.org/)
- Chọn **My Projects / Import / Import URL** theo đường link của chương trình mẫu:

      https://github.com/devmakerlabvn/makecode-mke-m01-single-led-module

- Kết nối **Micro:bit với máy tính** và **nạp chương trình**.
- Kết nối mạch **Micro:bit với MakerEdu Shield**, kết nối **Module LED tại cổng [P0]** và **màn hình LCD vào cổng [I2C] trên MakerEdu Shield**, **cấp nguồn qua cổng USB của MakerEdu Shield** để thấy chương trình hoạt động.

## Hỗ trợ và liên hệ

- Website: [https://www.makerlab.vn/](https://www.makerlab.vn/)
- Facebook: [https://www.facebook.com/makerlabvn](https://www.facebook.com/makerlabvn)

## Nhà phân phối

- Các bạn có thể mua sản phẩm của MakerLab tại các [Nhà Phân Phối.](https://www.makerlab.vn/distributor/)
