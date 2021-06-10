# DoAnChuyenNganh
Máy tính chạy chương trình phải tải về và cài đặt Nodejs trước (https://nodejs.org/en/).
Nhập “npm i”
Nhập “npm install -g cordova ionic” để cài đặt Ionic và cordova.
Trên thiết bị di động:
  -	Tùy vào thiết bị muốn chạy nhập các lệnh sau “ionic cordova platform add ios” hoặc “ionic cordova prepare platform”
  -	Điện thoại hoặc Android studio phải được cài đặt trong máy trước
  -	Nhập “ionic cordova run ios -l” hoặc “ionic cordova run android -l” để chạy chương trình.
Trên trình duyêt:
  -	Do ứng dụng có sử dụng API nên khi chạy trên trình duyệt sẽ xuất hiện lỗi “CORS Error”.
    Để sửa lỗi nhập đường link: https://cors-anywhere.herokuapp.com/corsdemo trên trình duyệt sau đó nhấn vào nút “Request temporary access to demo server”.
  -	Vào file ionic\GameE\src\app\services\game-data.service.ts dòng số 208  và thêm đoạn mã https://cors-anywhere.herokuapp.com/ vào biến “url”
  
