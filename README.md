# Website Hỗ TRỢ ORDER TẠI CÁC QUÁN NƯỚC

## 1. Giới thiệu

Website được xây dựng dựa trên nền tảng **Web Forms** của **ASP.NET Framework**.

### **Công cụ và công nghệ sử dụng**

- **Phần mềm phát triển:** Visual Studio 2020.
- **Quản lý cơ sở dữ liệu:** SQL Server Management Studio 2019.
- **Ngôn ngữ lập trình:** C#, JavaScript.
- **Các công nghệ hỗ trợ:** HTML, Bootstrap.

---

## 2. Giao diện và chức năng

### **2.1. Đăng nhập**

Người dùng nhập **Tên đăng nhập** và **Mật khẩu** để truy cập hệ thống.

![image](https://github.com/user-attachments/assets/82214bf6-15d9-4508-aecb-8bd7712542a4)


Sau khi đăng nhập thành công:

![image](https://github.com/user-attachments/assets/102efe67-dfe4-4221-b6b0-593b7b6a185b)


---

### **2.2. Quản lý hóa đơn**

Hiển thị danh sách các hóa đơn chưa thanh toán, kèm theo **số bàn** và **tổng tiền**.

- Mỗi hóa đơn có nút **"Thanh toán"** và **"Xem chi tiết"**.

![image](https://github.com/user-attachments/assets/b2972bf8-78c1-4071-a396-b8be4730a359)


**Tạo hóa đơn mới:**

![image](https://github.com/user-attachments/assets/1d8a82e0-9fd0-4cd7-b5f9-8e71df40b9a7)


---

### **2.3. Tạo hóa đơn mới**

- Thêm chi tiết hóa đơn (món nước, số lượng).
- Chọn số bàn.
- Giao diện bao gồm danh sách món bên trái, hóa đơn bên phải.

![image](https://github.com/user-attachments/assets/5c251abb-01fd-4721-a376-77e2ed88e9d5)


---

### **2.4. Danh sách bàn**

- Hiển thị danh sách bàn theo khu vực.
- **Màu bàn:**
  - ** Đỏ**: Bàn đang có khách.
  - ** Xanh**: Bàn trống.

![image](https://github.com/user-attachments/assets/5a5d1be8-1ad4-4100-993f-81ea301dd085)


---

### **2.5. Menu**

- Danh sách món nước kèm **hình ảnh, tên món, loại, giá**.

![image](https://github.com/user-attachments/assets/a9ea596e-17fe-46fb-8552-cc148bc73002)


---

### **2.6. Danh sách tài khoản**

- Hiển thị danh sách người dùng kèm theo **tên, chức vụ, số điện thoại**.
- Tìm kiếm theo trạng thái.

![image](https://github.com/user-attachments/assets/5ec414e7-0ec6-4378-8f89-73ed6a9c79ca)


---

### **2.7. Doanh thu**

- Hiển thị tổng doanh thu theo **ngày, tháng**.
- Tổng doanh thu từng món.

![image](https://github.com/user-attachments/assets/a5f61afb-a622-4632-80a7-e8885efe946c)


![image](https://github.com/user-attachments/assets/cdaeb0d4-4a02-47ac-8c59-a4ee98f98ba8)


![image](https://github.com/user-attachments/assets/070d49bc-bc55-457d-b8d5-1926f02952b2)


---

### **2.8. Lịch sử thanh toán**

- Danh sách hóa đơn đã thanh toán.
- Xem chi tiết tồng doanh thu theo ngày.

![image](https://github.com/user-attachments/assets/2162d3b0-dfd3-4fcf-80a8-ccc3dc9d9a71)



- Có thể xem danh sách hóa đơn đã xóa ở giao diện này

![image](https://github.com/user-attachments/assets/f889c8ba-8060-41f1-bd97-e7ed9c4de6de)


---

### **2.9. Thanh điều hướng**

- Chuyển nhanh giữa các giao diện.
- ** "Đăng xuất"**: Thoát khỏi hệ thống
- Có sự khác biệt ở thanh điều hướng dựa vào loại tài khoản "Quản lý" hoặc "Nhân viên"

![image](https://github.com/user-attachments/assets/5a9f6901-c337-48ec-837e-fc60e13c5013)

![image](https://github.com/user-attachments/assets/49f40c5e-02c2-4a8f-b5dd-934724ef0e48)



