# BaiTap
BaiTap2-nguyentheduong-k58ktp-He quan tri csdl

BÀI TOÁN:

Tạo csdl quan hệ với tên QLSV gồm các bảng sau:

SinhVien(#masv,hoten,NgaySinh)

Lop(#maLop,tenLop)

GVCN(#@maLop,#@magv,#HK)

LopSV(#@maLop,#@maSV,ChucVu)

GiaoVien(#magv,hoten,NgaySinh,@maBM)

BoMon(#MaBM,tenBM,@maKhoa)

Khoa(#maKhoa,tenKhoa)

MonHoc(#mamon,Tenmon,STC)

LopHP(#maLopHP,TenLopHP,HK,@maMon,@maGV)

DKMH(#@maLopHP,#@maSV,DiemTP,DiemThi,PhanTramThi)

YÊU CẦU:

Thực hiện các hành động sau trên giao diện đồ hoạ để tạo cơ sở dữ liệu cho bài toán:

Tạo database mới, mô tả các tham số(nếu có) trong quá trình.

Tạo các bảng dữ liệu với các trường như mô tả, chọn kiểu dữ liệu phù hợp với thực tế (tự tìm hiểu)

Mỗi bảng cần thiết lập PK, FK(s) và CK(s) nếu cần thiết. (chú ý dấu # và @: # là chỉ PK, @ chỉ FK)  
Chuyển các thao tác đồ hoạ trên thành lệnh SQL tương đương. lưu tất cả các lệnh SQL trong file: Script_DML.sql.  

#GIẢI BÀI TẬP 

- Cách tạo database trên SQL.

![Untitled](https://github.com/user-attachments/assets/a98eeb81-38bf-47a1-88ad-28afa90d6c72)

- Cách tạo bảng

![Untitled2](https://github.com/user-attachments/assets/5c99fef0-2edf-478c-b2b7-6930f7f8ff79)

- Cách tạo khóa chính (PK)

![Untitled3](https://github.com/user-attachments/assets/0cff452f-8beb-4fcd-bc2e-3fbf3ca6dd76)

- Cách tạo khóa ngoại (FK)

![Untitled4](https://github.com/user-attachments/assets/ad11772b-0ac3-4e0b-aa1c-9aa36498f5dc)
![Untitled5](https://github.com/user-attachments/assets/bf7a0ad4-ac16-4e0a-b283-7e48ff6fae55)
![Untitled6](https://github.com/user-attachments/assets/ca738bff-45c9-4f8f-b07c-17fa999810a7)

- Cách show code SQL của các bảng ra màn hình

![Untitled7](https://github.com/user-attachments/assets/26ae8f49-020e-4861-8585-6f79d7dd4d27)












