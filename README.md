# bai6
bai tap ve nha so 6 mssv k225480106088 Ta Pham Dinh Hoa mon He Quan Tri Co So Du Lieu
Yêu cầu bài tập: 
Cho file sv_tnut.sql (1.6MB)
1. Hãy nêu các bước để import được dữ liệu trong sv_tnut.sql vào sql server của em
2. dữ liệu đầu vào là tên của sv; sđt; ngày, tháng, năm sinh của sinh viên (của sv đang làm bài tập này)
3. nhập sql để tìm xem có những sv nào trùng hoàn toàn ngày/tháng/năm với em?
4. nhập sql để tìm xem có những sv nào trùng ngày và tháng sinh với em?
5. nhập sql để tìm xem có những sv nào trùng tháng và năm sinh với em?
6. nhập sql để tìm xem có những sv nào trùng tên với em?
7. nhập sql để tìm xem có những sv nào trùng họ và tên đệm với em.
8. nhập sql để tìm xem có những sv nào có sđt sai khác chỉ 1 số so với sđt của em.
9. BẢNG SV CÓ HƠN 9000 ROWS, HÃY LIỆT KÊ TẤT CẢ CÁC SV NGÀNH KMT, SẮP XẾP THEO TÊN VÀ HỌ ĐỆM, KIỂU TIẾNG  VIỆT, GIẢI THÍCH.
10. HÃY NHẬP SQL ĐỂ LIỆT KÊ CÁC SV NỮ NGÀNH KMT CÓ TRONG BẢNG SV (TRÌNH BÀY QUÁ TRÌNH SUY NGHĨ VÀ GIẢI NHỮNG VỨNG MẮC)

DEADLINE: 23H59:59 NGÀY 25/4/2025
# bài làm 
tạo database với tên là SV_tnut
![image](https://github.com/user-attachments/assets/ef386024-64b7-432a-98e5-f98fe4acc74a) 
mở file sv_tunt đã tải về
![image](https://github.com/user-attachments/assets/67fb2d36-06dc-454f-88e1-dbe06b85e7e2) 
![image](https://github.com/user-attachments/assets/10ff6a62-1438-47a9-8732-cba0fa9db038) 
khi mở lên ta được như này 
![image](https://github.com/user-attachments/assets/7e12af1c-2a7c-44d8-b22a-20f204f03780) 
chuột phải vào dbo.sv chọn edit top 200 ta được bảng sv như sau
![image](https://github.com/user-attachments/assets/a12abe44-bb92-42bc-833a-d76d150dd367) 
1. nhập sql để tìm xem có những sv nào trùng hoàn toàn ngày/tháng/năm với em?
![image](https://github.com/user-attachments/assets/684923ce-5f48-4330-bccf-bbc73c854bcf)
2. nhập sql để tìm xem có những sv nào trùng ngày và tháng sinh với em?
![image](https://github.com/user-attachments/assets/3c2ed84f-cdcb-4cca-880d-6498dd9d66bf)
3. nhập sql để tìm xem có những sv nào trùng tháng và năm sinh với em?
![image](https://github.com/user-attachments/assets/3378e701-c19a-44e4-aff6-daf964563539)
4. nhập sql để tìm xem có những sv nào trùng tên với em?
![image](https://github.com/user-attachments/assets/6a200425-b285-4d28-9da9-7065fa53c8ce)
5. nhập sql để tìm xem có những sv nào trùng họ và tên đệm với em.
![image](https://github.com/user-attachments/assets/828ad91d-722a-4b1f-b506-9f68ee1fbf44)
6. nhập sql để tìm xem có những sv nào có sđt sai khác chỉ 1 số so với sđt của em.
giải thích: so sánh từng ký tự của số điện thoại và đếm số ký tự khác 
![image](https://github.com/user-attachments/assets/e073d01a-5f9f-4d14-a79a-b97520ef126d)
8. HÃY LIỆT KÊ TẤT CẢ CÁC SV NGÀNH KMT, SẮP XẾP THEO TÊN VÀ HỌ ĐỆM, KIỂU TIẾNG  VIỆT, GIẢI THÍCH.
giải thích:
lọc theo cột lớp có chứa KMT
 RIGHT(...): lấy tên từ HoTen.
LEFT(...): lấy phần còn lại (họ và tên đệm).
COLLATE Vietnamese_CI_AS: sắp xếp theo chuẩn tiếng Việt.
![image](https://github.com/user-attachments/assets/4448244a-e633-46a0-8d32-6a071b5d1344)
9. LIỆT KÊ CÁC SV NỮ NGÀNH KMT CÓ TRONG BẢNG SV
giải thích:
vì không có cột giới tính nên không thể in ra chính xác 100%
nên ta sẽ lọc theo Lớp KMT và theo Tên của sinh viên nữ 
![image](https://github.com/user-attachments/assets/4ba9e4a9-ffab-415b-a3b0-5e6b9ee8307e)



















