HƯỚNG Dẫn SỬ DỤNG :
- astar.py : chương trình tìm đường đi trong mê cung sử dụng A*

- theta.py : chương trình tìm đường đi trong mê cung sử dụng A* kết hợp dùng theta để cập nhật đường đi ngắn nhất

- map.txt : bản đồ mê cung mã hóa như sau : 0 là đường đi , 1 là tường, 2 là điểm đầu , 3 là điểm đích . Tổng cộng có 7 map

1.Tạo bản đồ

1.1.Đọc bản đồ có sẵn trong file map.txt

- Sử dụng các phím 1,2,3,4,5,6,7 để tự động vẽ 1 trong 7 bản đồ có sẵn
- Có thể chuyển đổi qua bản đồ mình muốn bằng cách nhấn vào một trong các phím trên , chương trình sẽ tự xóa bản đồ cũ và cập nhật bản đồ mới
  
1.2. Tạo bản đồ thủ công
- Click chuột trái để tạo điểm đích , điểm nguồn và tường : nếu chưa có đích và hay điểm đầu thì khi click sẽ có độ ưu tiên tạo điểm đầu sau đó tới đích sau đó tới tường
- Xóa một ô bằng cách click chuột phải.
  
2.Chạy chương trình tìm đường đi

  Sau khi tạo bản đồ nhấn Space để tìm đường đi .
  
3.Chú giải:

- Điểm đầu : ô màu cam
- Điểm đích : ô màu xanh da trời
- Tường : ô đen
- Đường đi : ô trắng
- Đường đi ngắn nhất tìm được : ô tím (khi chạy file astar.py) , đường kẻ đen (khi chạy theta.py do kết hợp giải thuật theta tìm đường đi ngắn nhất )
  
