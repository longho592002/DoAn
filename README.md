Đồ án này gồm 2 phần:
  - Phân tích giá vàng theo dữ liệu thời gian thực
  - Phần mềm xem thông tin của tiền điện tử bằng ngôn ngữ Flutter
Để chạy phần mềm Flutter, sau khi mở folder bằng Android Studio thì người dùng nên chọn thiết bị là Pixel 6 Pro API 34 và chạy file main.dart. Nếu lần đầu chạy ứng dụng thì người dùng nên vào file pubspec và click vào nút pubget trên màn hình trước khi build và sẽ mất một khoảng thời gian ( tầm 5-10 phút) để build.\
![image](https://github.com/longho592002/DoAn/assets/71805121/1c3b0021-bcce-4941-97df-f0026169c99d)
Với phần phân tích giá vàng thì sẽ gồm 2 file python là displaySignal và displayCandle. Trước hết người dùng nên tải phần mềm MetaTrader5 (https://www.metatrader5.com/). Sau đó nếu người dùng chưa có môi trường ảo và các thư viện thì hãy làm theo các bước sau:
  - Người dùng cần bật terminal trên IDE chạy python
  - Nhập "pip install virtualenv"
  - Nhập "virtualenv venv"
  - Nhập “pip install -r requirement.txt”
Sau khi thực hiện xong, người dùng đã có thể chạy 2 file python. File displaySignal dùng để hiện thị tín hiệu cho thấy giá vàng sắp tăng hay giảm. Tín hiệu này được thể hiện trong terminal, với giá trị ở cột divSignal là 1 thì là dấu hiệu giá vàng sẽ tăng và nếu giá trị là 2 nghĩa là giá vàng sắp tới sẽ giảm
![image](https://github.com/longho592002/DoAn/assets/71805121/3e47d8a8-3f38-4a77-97ae-2b06dceb8ec0)

Còn file displayCandle dùng để hiển thị thông tin biểu đồ của giá vàng trên website
![image](https://github.com/longho592002/DoAn/assets/71805121/f773ad38-4519-4b8d-94f5-9bf6dc4da06f)

**Người dùng nên sử dụng vào các ngày từ thứ 2 đến thứ 6, ngoài thời gian này, thị trường giá vàng sẽ không hoạt động nên sẽ không áp dụng được việc phân tích dữ liệu theo thời gian thực**
