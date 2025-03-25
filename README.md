# K58kmt
Bài tập 02 của sv-K225480106008- Nguyên Khánh Duy- Hệ Quản Trị CSDL
BÀI TOÁN:
- Tạo csdl quan hệ với tên QLSV gồm các bảng sau:
  + SinhVien(#masv,hoten,NgaySinh)
  + Lop(#maLop,tenLop)
  + GVCN(#@maLop,#@magv,#HK)
  + LopSV(#@maLop,#@maSV,ChucVu)
  + GiaoVien(#magv,hoten,NgaySinh,@maBM)
  + BoMon(#MaBM,tenBM,@maKhoa)
  + Khoa(#maKhoa,tenKhoa)
  + MonHoc(#mamon,Tenmon,STC)
  + LopHP(#maLopHP,TenLopHP,HK,@maMon,@maGV)
  + DKMH(#@maLopHP,#@maSV,DiemTP,DiemThi,PhanTramThi)
   + SinhVien(#masv,hoten,NgaySinh)
![image](https://github.com/user-attachments/assets/4a04f58c-e227-4bd2-9584-b540f4188f5b)
![image](https://github.com/user-attachments/assets/983ac5d5-4a43-4196-b11e-7300c6908039)

+ Lop(#maLop,tenLop)
+ ![image](https://github.com/user-attachments/assets/18e7588a-6493-4112-a27f-c6496d2c4d91)
+ GVCN(#@maLop,#@magv,#HK)
+ ![image](https://github.com/user-attachments/assets/ea73a934-4f81-4684-9323-68b72c05b474)
 + LopSV(#@maLop,#@maSV,ChucVu)
 + ![image](https://github.com/user-attachments/assets/3e78fcc6-6c55-43c3-8bb9-cd0665ed0bb2)
  + GiaoVien(#magv,hoten,NgaySinh,@maBM)
 + ![image](https://github.com/user-attachments/assets/e986348f-698e-4f23-a619-031ed965e31a)
  + BoMon(#MaBM,tenBM,@maKhoa)
  + ![image](https://github.com/user-attachments/assets/3223f797-da4d-4d86-a468-a65b75a96f45)
+ Khoa(#maKhoa,tenKhoa)
+ ![image](https://github.com/user-attachments/assets/6a5b02a2-7799-445e-b25d-cd34389a3786)
 + MonHoc(#mamon,Tenmon,STC)
![image](https://github.com/user-attachments/assets/a641cb95-0c1f-4d93-bba8-cff6b7f6b6c5)
  + LopHP(#maLopHP,TenLopHP,HK,@maMon,@maGV)
  + ![image](https://github.com/user-attachments/assets/2b93b5b2-174e-441f-b7c4-7465b3d6372f)
  + DKMH(#@maLopHP,#@maSV,DiemTP,DiemThi,PhanTramThi)
  + ![image](https://github.com/user-attachments/assets/3d6cc6b6-4f21-4081-8aa7-d51a91b6105e)
   + SinhVien(#masv,hoten,NgaySinh)
   + ![image](https://github.com/user-attachments/assets/b68206d3-31db-4e3d-9e3d-f8ec481cb16c)
Thiết lập các khóa FK, CK, PK cho bảng
![image](https://github.com/user-attachments/assets/30af2f48-16f3-4bcb-b863-3e594c7c71f7)
các bảng tiếp theo tương tự
+Thiết lập FK cho bảng GVCN
![image](https://github.com/user-attachments/assets/9a8e756b-8510-4ec0-ab47-1b63917a2c6b)

