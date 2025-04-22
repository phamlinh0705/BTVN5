# BTVN5
Phạm Khắc Linh_K225480106037_HQTCSDL

BÀI TẬP VỀ NHÀ 05, Môn Hệ quản trị csdl.

SUBJECT: Trigger on mssql

A. Trình bày lại đầu bài của đồ án PT&TKHT:

Mô tả bài toán của đồ án PT&TKHT, đưa ra yêu cầu của bài toán đó
Cơ sở dữ liệu của Đồ án PT&TKHT : Có database với các bảng dữ liệu cần thiết (3nf), Các bảng này đã có PK, FK, CK cần thiết
B. Nội dung Bài tập 05:

Dựa trên cơ sở là csdl của Đồ án
Tìm cách bổ xung thêm 1 (hoặc vài) trường phi chuẩn (là trường tính toán đc, nhưng thêm vào thì ok hơn, ok hơn theo 1 logic nào đó, vd ok hơn về speed) => Nêu rõ logic này!
Viết trigger cho 1 bảng nào đó, mà có sử dụng trường phi chuẩn này, nhằm đạt được 1 vài mục tiêu nào đó. => Nêu rõ các mục tiêu
Nhập dữ liệu có kiểm soát, nhằm để test sự hiệu quả của việc trigger auto run.
Kết luận về Trigger đã giúp gì cho đồ án của em.
Xây dựng Hệ thống Quản lý Tiệm Bán Hoa với các chức năng:

Quản lý sản phẩm hoa, loại hoa, khách hàng, đơn hàng.

Quản lý nhập hàng, tồn kho.

Hỗ trợ thống kê doanh thu, sản phẩm bán chạy, kiểm soát tồn kho.

Yêu cầu hệ thống:
Lưu trữ và quản lý chi tiết các loại hoa và đơn đặt hàng.

Theo dõi doanh thu theo thời gian.

Tự động cập nhật dữ liệu phụ phục vụ thống kê (ví dụ: tổng tiền mỗi đơn hàng).

Bảng Hoa:
![image](https://github.com/user-attachments/assets/322c7457-7d36-4479-9a8b-3895c717317e)
Bảng LoaiHoa
![image](https://github.com/user-attachments/assets/f4d0eb24-f9e2-4447-9519-1869ed086d7d)
Bảng KhachHang
![image](https://github.com/user-attachments/assets/4b97b457-18a4-463a-9f29-bb3baeb12c8e)
Bảng Đơn Hàng
![image](https://github.com/user-attachments/assets/ae7e2c88-44a3-429b-ab5a-0d6af5b985ab)
Bảng ChiTietDH
![image](https://github.com/user-attachments/assets/bd522f27-6777-4476-bc44-860b81f068e1)

Với các khóa ngoại liên kết cho các bảng:
![image](https://github.com/user-attachments/assets/471604e2-61ef-43f4-bf88-dcc2a0951556)
![image](https://github.com/user-attachments/assets/77930cf1-f9a8-435f-b5cc-45da52b91829)
![image](https://github.com/user-attachments/assets/5bf14271-3772-48b0-8216-6d148cf75a5d)
![image](https://github.com/user-attachments/assets/d752fc42-faa1-4a6c-80cd-6d8522c9bbb7)
![image](https://github.com/user-attachments/assets/c2d72c1d-4335-469e-8662-ba6ec9dab88d)

B.Nội dung Bài tập 05:

Tạo csdl cho hệ thống tìm bạn chơi
2.Bố sung thêm trường phi chuẩn: số lượng sân còn trống trước và sau khi được tạo, số lượng người tham gia trong bảng trận đấu, số trận đã chơi và số trận đã tạo trong bảng thông tin người chơi

Viết trigger cho các bảng để đạt được mục tiêu:
Bấm dấu "+" vào bảng và chuột phải vào Triggers ---> new trigger
![image](https://github.com/user-attachments/assets/fb07b18b-20bc-4319-b2f1-14293c66f03f)
Bảng trận đấu: số lượng người tham gia sẽ tự động tăng khi có người bấm tham gia trận đấu:
![image](https://github.com/user-attachments/assets/db2101bb-0241-4af1-bcdc-48bb26f63022)
Test trigger: chuyển trạng thái của 1 người tham gia từ chờ xử lí thành đã tham gia và xem kết quả:
![image](https://github.com/user-attachments/assets/46447713-d96e-4c6a-96cf-1f418ea42c07)


