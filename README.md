# BTVN4   
Yêu cầu bài toán:
 - Tạo csdl cho hệ thống TKB (đã nghe giảng, đã xem cách làm)
 - Nguồn dữ liệu: TMS.tnut.edu.vn
 - Tạo các bảng tuỳ ý (3nf)
 - Tạo được query truy vấn ra thông tin gồm 4 cột: họ tên gv, môn dạy, giờ vào lớp, giờ ra.
   trả lời câu hỏi: trong khoảng thời gian từ datetime1 tới datetime2 thì có những gv nào đang bận giảng dạy.

Các bước thực hiện:
1. Tạo github repo mới: đặt tên tuỳ ý (có liên quan đến bài tập này)
2. tạo file readme.md, edit online nó:
   paste những ảnh chụp màn hình
   gõ text mô tả cho ảnh đó
Trình bày các bước làm
Bước 1: Tạo bảng các bảng bằng cách ấn chuột trái vào table
![image](https://github.com/user-attachments/assets/18c95f9f-59b7-480f-998a-8902cbf76c16)

Bước 2:Tạo bảng GiangVien với 2 trường là MaGv và HoTen.   
![image](https://github.com/user-attachments/assets/1d3201d1-3e1a-44a7-9137-e3b55e2c7521)   

Bước 3:Tạo bảng Lop  
![image](https://github.com/user-attachments/assets/ed3fb5b8-5eef-4cbb-a932-6c70d30baf66)  

Bước 4:Tạo bảng MonHoc với 2 trường là MaMon và TenMon  
![image](https://github.com/user-attachments/assets/58d5c61b-1951-406c-aa2d-52501f5e8c74)  

Bước 5:Tạo Bảng PhongHoc.  
![image](https://github.com/user-attachments/assets/d1c44364-0957-4ad5-b223-df0e7a95b7db)   

Bước 6:Tạo bảng LichHoc.   
![image](https://github.com/user-attachments/assets/49dcb07d-4d7f-4489-a55d-c592d31b2491)  

Bước 7: Nhập dữ liệu cho bảng PhongHoc.  
![image](https://github.com/user-attachments/assets/7d168174-1185-449f-9ccc-147791a14f2a)   

Bước 8:Nhập dữ liệu cho bảng MonHoc.  
![image](https://github.com/user-attachments/assets/f22f3cb9-97a4-4c80-9484-e83c8d21214c)  

Bước 9:Nhập dữ liệu cho bảng Lop.  
![image](https://github.com/user-attachments/assets/8b4eaf02-ec10-4777-ae04-79937f681af4)   

Bước 10:Nhập dữ liệu cho bảng GiangVien.  
![image](https://github.com/user-attachments/assets/75f21d09-089a-4aab-81fa-c12d6d6d4636)  

Bước 10:Nhap dữ liệu cho bảng LichHoc.   
![image](https://github.com/user-attachments/assets/e94b2328-b553-4ff5-b07b-58a5db14c756)   

Bước 11: Tạo sơ đồ quan hệ giữa các bảng trong cơ sở dữ liệu BTVN-4 bằng Database Diagram.

Các bảng được liên kết gồm: LichHoc, GiangVien, MonHoc, Lop, PhongHoc.
Trong đó, bảng trung tâm là LichHoc, liên kết khóa ngoại đến các bảng còn lại.
![image](https://github.com/user-attachments/assets/570b4f77-6a1d-48d9-b173-b39de6cabe89)   

Bước 12:sử dụng SQL Server Management Studio (SSMS) để chạy một câu truy vấn SQL trong cơ sở dữ liệu có tên là BTVN-4. Đây là một truy vấn SELECT kết hợp nhiều bảng để lọc thông tin từ bảng LichHoc.
![Screenshot (99)](https://github.com/user-attachments/assets/4988b86e-d8e1-4ecb-ab23-6557bea18135)













