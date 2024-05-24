# Hướng dẫn

Thao tác với Khách Hàng Tiềm Năng:
- Hiện từng thông tin: http://127.0.0.1:5000/khachhangtiemnang/id (thay id mong muốn)
- Hiện tất cả thông tin: http://127.0.0.1:5000/khachhangtiemnang
- Thêm thông tin khách hàng khác: http://127.0.0.1:5000/khachhangtiemnang [POST]
- Cập nhật thông tin từng khách hàng: http://127.0.0.1:5000/khachhangtiemnang/id [PUT]
- Xóa thông tin từng khách hàng: http://127.0.0.1:5000/khachhangtiemnang/id [DELETE]

Thao tác với Nhà Cung Cấp:
- Hiện từng thông tin: http://127.0.0.1:5000/nhacungcap/id (thay id mong muốn)
- Hiện tất cả thông tin: http://127.0.0.1:5000/nhacungcap
- Thêm thông tin nhà cung cấp khác: http://127.0.0.1:5000/nhacungcap [POST]
- Cập nhật thông tin từng nhà cung cấp: http://127.0.0.1:5000/nhacungcap/id [PUT]
- Xóa thông tin từng nhà cung cấp: http://127.0.0.1:5000/nhacungcap/id [DELETE]

# Kết quả kiểm thử với Postman

Xác thực và ủy quyền: 
- Đang bị giới hạn về ủy quyền, chưa có sự phân quyền rõ ràng.
- Thao tác với quyền bị giới hạn nếu nhiều request cùng lúc với các phương thức khác ngoài GET

Thời gian phản hồi, hiệu xuất:
- Nhanh

Thông tin trả về: 
- Chính xác
- Các status trả về đúng

Ảnh kết quả trả về:

- GET
![get](https://github.com/21010647AnNV/api-crm-with-postman/blob/main/images/get.png)

- POST
![post](https://github.com/21010647AnNV/api-crm-with-postman/blob/main/images/post.png)

- DELETE
![delete](https://github.com/21010647AnNV/api-crm-with-postman/blob/main/images/delete.png)
