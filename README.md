# Web bán hàng thời trang FASHIONSHOP sử dụng công nghệ Asp.Net MVC
# Giao diện người dùng
- Giao diện trang chủ


- Giao diện đăng nhập , đăng ký


- Giao diện xem chi tiết sản phẩm như hình và bên dưới gồm 2 tab(chi tiết sản phẩm, đánh giá)

#Phần đánh giá sẽ hiển thị danh sách các đánh giá, form đánh giá chỉ hiển thị khi bạn đã mua sản phẩm này(đã đăng nhập// chưa đăng nhập khi nhập đánh giá sẽ hiển thị message phải login)

- Giao diện giỏ hàng
- Giao diện thanh toán (chưa login sẽ chuyển về trang login)

- Giao diện xem lịch sử mua hàng
#Có thể hủy đơn hàng nếu bạn đặt hàng dưới 2 ngày, đã giao khi đơn hàng được giao đến bạn, còn lại đang giao

# Giao diện Admin 
- Giao diện trang danh sách sản phẩm (số lượng, màu, size ở bảng khác liên kết với bảng sản phẩm)

- Giao diện trang đơn hàng

#Kích vào chi tiết sẽ hiển thị trang chi tiết đơn hàng, nút cập nhật sẽ cập nhật trạng thái gồm chưa giao hàng, đã giao, hoàn thành

##Option Hoàn thành khi kích vào lựa chọn này mặc định đơn hàng đã giao =>> phía giao diện người dùng đơn hàng này sẽ chuyển về đã giao

#Còn 1 nút Hủy bên cạnh nút cập nhật (chỉ admin mới hủy được, nhân viên không có quyền hủy)

- Giao diện trang thống kê


# Những hạn chế của trang web
- Phía người dùng
  + Trang chi tiết sản phẩm khi thêm sản phẩm vào giỏ hàng đã giới hạn số lượng đặt của sản phẩm
  + Khi đặt hàng thành công số lượng của sản phẩm không bị trừ đi
  + Phần thanh toán bằng thẻ ngân hàng dù thanh toán thành công hay thất bại vẫn sẽ tạo ra đơn hàng mới

- Phía admin
  + Trang đơn hàng chưa được tối ưu, khi kích vào trạng thái hoàn thành chưa ẩn nút cập nhật lại
  + Phần thống kê chỉ thống kê theo ngày
# sẽ dần update lại trang web, sửa lại các lỗi..
