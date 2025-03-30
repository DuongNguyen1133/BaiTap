![image](https://github.com/user-attachments/assets/a10d4d73-a16d-4b15-a952-6291d70c3742)BÀI TOÁN: Sửa bài 2 để có csdl như sau:
  + SinhVien(#masv,hoten,NgaySinh)
  + Lop(#maLop,tenLop)
  + GVCN(#@maLop,#@magv,#HK)
  + LopSV(#@maLop,#@maSV,ChucVu)
  + GiaoVien(#magv,hoten,NgaySinh,@maBM)
  + BoMon(#MaBM,tenBM,@maKhoa)
  + Khoa(#maKhoa,tenKhoa)
  + MonHoc(#mamon,Tenmon,STC)
  + LopHP(#maLopHP,TenLopHP,HK,@maMon,@maGV)
  + DKMH(#id_dk, @maLopHP,@maSV,DiemThi,PhanTramThi)
  + Diem(#id, @id_dk, diem)

YÊU CẦU:
1. Sửa bảng DKMH và bảng Điểm từ bài tập 2 để có các bảng như yêu cầu.
2. Nhập dữ liệu demo cho các bảng (nhập có kiểm soát từ tính năng Edit trên UI của mssm)
3. Viết lệnh truy vấn để: Tính được điểm thành phần của 1 sinh viên đang học tại 1 lớp học phần.

#BÀI LÀM  
#**1. Sửa bảng DKMH và bảng Điểm từ bài tập 2 để có các bảng như yêu cầu.**
- Sửa bảng DKMH
  ![Untitled](https://github.com/user-attachments/assets/5073f78f-13b3-432c-8758-587c5f0c8664)
  ![Untitled1](https://github.com/user-attachments/assets/5ff51995-2828-4c57-9813-b8690195358d)

- Sửa bảng Diem
  ![Untitled2](https://github.com/user-attachments/assets/a3f58abe-3abc-46d5-a8eb-abc545c6ae05)


#**2. Nhập dữ liệu demo cho các bảng (nhập có kiểm soát từ tính năng Edit trên UI của mssm)**
- Nhập dữ liệu cho bảng BoMon
![Untitled3](https://github.com/user-attachments/assets/f21aa422-5127-44d3-a975-27f88dd57c7f)
- Dữ liệu được nhập trong bảng BoMon
  ![Untitled4](https://github.com/user-attachments/assets/00ec5725-c7a3-4fb6-83d8-1002e3b7f541)


- Nhập dữ liệu trong bảng Diem
  ![Untitled3](https://github.com/user-attachments/assets/f9b8b3ff-3553-4c18-8c00-d1af29a2d92b)
- Dữ liệu được nhập trong bảng Diem
  ![image](https://github.com/user-attachments/assets/ac4be126-0611-4ee0-bfa8-8157cb17d42e)

- Nhập dữ liệu trong bảng DKMH
![Untitled3](https://github.com/user-attachments/assets/25ebd998-b378-4eca-b85a-84446391ac57)
- Dữ liệu được nhập trong DKMH
  ![image](https://github.com/user-attachments/assets/f7367dbc-01c0-44e3-9b4e-47426a799af2)

- Nhập dữ liệu trong bảng GiaoVien
  ![Untitled3](https://github.com/user-attachments/assets/7ed0212b-2421-4c7c-a6d5-900b570eab77)
- Dữ liệu được nhập trong GiaoVien
  ![image](https://github.com/user-attachments/assets/3091bba8-f18e-4531-937d-d80c3ed4447a)

- Nhập dữ liệu trong bảng GVCN
  ![Untitled3](https://github.com/user-attachments/assets/6e0b46a6-3504-4bdb-9103-75925ca1004e)
- Dữ liệu được nhập trong GVCN
![image](https://github.com/user-attachments/assets/e1474034-bba9-49ba-b7a8-6f4c6b7a7490)

- Nhập dữ liệu trong bảng Khoa
![Untitled3](https://github.com/user-attachments/assets/6e0b46a6-3504-4bdb-9103-75925ca1004e)
- Dữ liệu được nhập trong Khoa
  ![image](https://github.com/user-attachments/assets/1bc683fd-c1d4-4135-bf64-d058db2a5579)

- Nhập dữ liệu trong bảng  Lop
   ![Untitled3](https://github.com/user-attachments/assets/6e0b46a6-3504-4bdb-9103-75925ca1004e)
- Dữ liệu được nhập trong Lop
  ![image](https://github.com/user-attachments/assets/a9e21944-87d4-49d0-a2bf-8ce897995016)


- Nhập dữ liệu trong bảng LopHP
  ![Untitled3](https://github.com/user-attachments/assets/6e0b46a6-3504-4bdb-9103-75925ca1004e) 
- Dữ liệu được nhập trong LopHP
  ![image](https://github.com/user-attachments/assets/213eb18b-e699-47b5-a9e1-e47061299075)


- Nhập dữ liệu trong bảng LopSV
 ![Untitled3](https://github.com/user-attachments/assets/6e0b46a6-3504-4bdb-9103-75925ca1004e) 
- Dữ liệu được nhập trong LopSV
![image](https://github.com/user-attachments/assets/1c9f45e7-23df-4190-b955-ad4f098caa29)


- Nhập dữ liệu trong bảng MonHoc
![Untitled3](https://github.com/user-attachments/assets/6e0b46a6-3504-4bdb-9103-75925ca1004e) 
- Dữ liệu được nhập trong MonHoc
![image](https://github.com/user-attachments/assets/16a00e9b-42a7-4334-a7c1-2d4a67132e28)


- Nhập dữ liệu trong bảng SinhVien
![Untitled3](https://github.com/user-attachments/assets/6e0b46a6-3504-4bdb-9103-75925ca1004e) 
- Dữ liệu được nhập trong SinhVien
![image](https://github.com/user-attachments/assets/bb9fcde6-0613-48f9-a534-77fd6a27c289)


#**3. Viết lệnh truy vấn để: Tính được điểm thành phần của 1 sinh viên đang học tại 1 lớp học phần.**
- Lấy điểm thi và điểm thành phần của 1 sinh viên trong 1 lớp học phần
![image](https://github.com/user-attachments/assets/c879adf5-b702-40c8-a32f-fa145088ceda)

- Truy vấn với tên sinh viên và tên môn học
  ![image](https://github.com/user-attachments/assets/c77c224a-ed02-4645-b5c8-09cc569111fd)


#**4. Tạo diagram mô tả các PK, FK của db.**
![image](https://github.com/user-attachments/assets/43bbf1fb-634c-4cf6-9d08-b7fecfcb4990)





