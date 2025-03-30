# BaiTap2
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

- PRIMARY KEY CLUSTERED:
PRIMARY KEY: Xác định rằng ràng buộc này là khóa chính. Khóa chính đảm bảo:  
Không có giá trị trùng lặp trong tổ hợp các cột.  
Không có giá trị NULL trong các cột thuộc khoá chính.  
CLUSTERED: Dữ liệu trong bảng sẽ được sắp xếp vật lý trên đĩa theo thứ tự của khóa chính này.

- Chọn mối quan hệ

![Untitled8](https://github.com/user-attachments/assets/1264bc35-536f-42f8-9aff-defc52022939)

![Untitled9](https://github.com/user-attachments/assets/83f097da-665d-4eb5-ae9d-db6afa367e5f)
![Untitled10](https://github.com/user-attachments/assets/f422338e-65f1-407b-bf7f-846d2809c7db)
- sau khi xong Ctrl + S để save

- Các bảng còn lại làm như trên
- Bảng LopSV
![untitled11](https://github.com/user-attachments/assets/d0cf18e2-bdae-41fc-bfe9-04f8a7571cce)
-MaSV
![Untitled12](https://github.com/user-attachments/assets/99549fe1-8aea-4755-bba3-9a51896e462d)

- Bảng giáo viên
- maBM
![Untitled13](https://github.com/user-attachments/assets/81c25b47-78ce-46e3-bd14-ab173368722b)

- Bảng bộ môn
- maBM
![Untitled14](https://github.com/user-attachments/assets/aaaf0418-aa7c-40a0-98db-f0f069f7d32b)

- maKhoa
![Untitled15](https://github.com/user-attachments/assets/6e8aa7e3-3509-432c-bcfd-01476285772a)

- Bảng Khoa
![Untitled16](https://github.com/user-attachments/assets/8d73907d-619c-4281-a93c-a12531f5ce79)

- Bảng monHoc
- maMon
![Untitled17](https://github.com/user-attachments/assets/fffada2b-17de-4ca0-90dc-c5ab0501da8f)

- STC
  ![image](https://github.com/user-attachments/assets/acd5f421-ee5d-4e2e-b215-9b4e07ebdd47)

- Bảng LopHP
- MalopHp
  ![Untitled19](https://github.com/user-attachments/assets/5fe29fdd-5072-4a25-9132-6d12b5581139)

-maGV
![Untitled20](https://github.com/user-attachments/assets/ce38f4c8-03fd-45da-81f7-b7e4d05f793f)

- HK
![image](https://github.com/user-attachments/assets/7052d60d-6035-4b96-a9e1-2261c93a4bed)

- Bảng DKMH
![image](https://github.com/user-attachments/assets/deb1b74b-d0eb-4d48-824b-951f9182382f)

- maLopHP
![Untitled21](https://github.com/user-attachments/assets/b97d3625-cdb6-4de8-adfd-605e8f489a10)

- maSV
![Untitled22](https://github.com/user-attachments/assets/915b8db7-753b-46ee-a14a-6c050c57fffa)

- diemTP
 ![image](https://github.com/user-attachments/assets/e48873cb-f996-40b1-bf35-defa675243e1)

- diemthi
  ![image](https://github.com/user-attachments/assets/1b3843bf-4e26-4060-8659-66476d02bb77)
- phamtramThi
  ![image](https://github.com/user-attachments/assets/46580b0e-a03f-47a1-ae5f-5c2181b0c6e4)
#2. Chuyển các thao tác đồ hoạ trên thành lệnh SQL tương đương. lưu tất cả các lệnh SQL trong file: Script_DML.sql
- Click trọn vào QLSV --> chọn Tasks ---> Gererate Scripts..
![Untitled23](https://github.com/user-attachments/assets/e1733f13-3b39-4f48-8e67-32070f422d6d)

- Sau khi vào Gererate Scrips ---> Click next
![Untitled24](https://github.com/user-attachments/assets/d3f6ace0-8310-4663-999f-e3128de601b7)

- Chọn Script entire database... ---> click Next
  ![Untitled25](https://github.com/user-attachments/assets/e449f4ca-1890-4acb-91bd-3578ab4cfe00)

- Chọn theo 1-->2-->3
![Untitled26](https://github.com/user-attachments/assets/2aaa04b6-319c-421c-a8a1-e628366b7cf6)

- Xem lại các lựa chọn
  ![Untitled27](https://github.com/user-attachments/assets/99578995-aff1-430f-9c8e-f41a8fba22a8)

![Untitled28](https://github.com/user-attachments/assets/afd8332e-6818-49b8-b2b9-4d6cc8da18cd)

#ViewCode 

![Untitled29](https://github.com/user-attachments/assets/47335b5c-d33f-43fd-a2e3-a386faef783c)
![Untitled30](https://github.com/user-attachments/assets/ace2d106-bc8f-41c0-8dd8-a1c5a5b439af)
![Untitled31](https://github.com/user-attachments/assets/3a951a3f-36ac-4291-88a0-16628fc33f6e)
![Untitled32](https://github.com/user-attachments/assets/3f619f02-12b2-4240-9a2e-42f699f85b9e)
![Untitled33](https://github.com/user-attachments/assets/26f9bd6c-5658-41ec-9cb3-1725f8820210)













