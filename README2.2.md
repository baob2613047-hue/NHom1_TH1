Thông tin chung     
** Nhóm thực hiện: Nhóm 01           
Tên thành viên: Bùi Trương Bảo Ngọc_ Nguyễn Thái Anh_ Lê Phạm Gia Bảo_ Trần Ngọc Thiên Bảo       
Học phần: CT005_D12/ Nền tảng công nghệ số         
Nhiệm vụ: Sử dụng AI để khắc phục lỗi Notepad++ không mở được file Python lớn         
Nguyên nhân gây ra lỗi     
Bộ phân tích cú pháp Python: Khi mở file .py, Notepad++ kích hoạt tính năng tô màu code và phân tích dòng (indentation). Quá trình này tiêu tốn dung lượng RAM gấp 2–4 lần dung lượng thực của file.    
Cách khắc phục:       
Bước 1: Mở ứng dụng Notepad++ trống (chưa kéo file bị lỗi vào).    
Bước 2: Trên thanh Menu trên cùng, bấm chọn Language ,di chuột vào chữ N, bấm chọn Normal Text.   
Bước 3: Vào Settings ,chọn Preferences... ,bấm vào mục Performance (hoặc Large Document Restriction),đánh dấu tích vào Enable Large File Restriction.    
Bước 4: Thử kéo thả file Python lớn vào lại.     
Kết quả:      
Chữ hiển thị màu đen thống nhất: Không còn tô màu xanh/đỏ/tím cho biến và hàm Python (giúp tiết kiệm RAM tối đa).    
Thanh trạng thái góc dưới bên trái: Hiển thị chữ Normal text (thay vì chữ Python file).     
Mở mượt mà: File hiển thị đầy đủ số dòng ở góc dưới, không bị đơ "(Not Responding)" và không hiện hộp thoại lỗi . 
