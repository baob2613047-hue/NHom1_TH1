# Thông tin chung     
## Nhóm thực hiện: Nhóm 01           
Tên thành viên: Bùi Trương Bảo Ngọc_ Nguyễn Thái Anh_ Lê Phạm Gia Bảo_ Trần Ngọc Thiên Bảo           
Học phần: CT005_D12/ Nền tảng công nghệ số         
**Nhiệm vụ**: Sử dụng AI để khắc phục lỗi Notepad++ không mở được file Python lớn         
**Nguyên nhân gây ra lỗi**: tải file Python có dung lượng lớn (>1MB)    
## BÁO CÁO KẾT QUẢ XỬ LÝ LỖI PHẦN MỀM CƠ BẢN
**Mô tả lỗi**: Notepad++ không mở được hoặc bị treo (Not Responding) khi tải file Python có dung lượng lớn (>1MB) do hạn chế trong việc quản lý bộ nhớ đệm (buffer memory) của các trình biên tập văn bản nhẹ.     
Prompt sử dụng cho AI: "Cách khắc phục lỗi Notepad++ không mở được file Python lớn trên Windows."
Giải pháp đề xuất bởi AI:
Chuyển sang sử dụng trình biên tập mã nguồn chuyên dụng có khả năng tối ưu bộ nhớ tốt hơn như Visual Studio Code (VS Code) hoặc PyCharm.
Cài đặt plugin BigFiles trên Notepad++ hoặc tắt tính năng Tô màu cú pháp (Syntax Highlighting) cho file dung lượng lớn.
**Kết quả thực hiện**:
Trạng thái: Thành công.
**Giải pháp áp dụng**: Cài đặt và sử dụng Visual Studio Code. File Python mẫu (large_script.py, kích thước 2.578 KB ~ 2.5 MB) được mở và chỉnh sửa mượt mà.
Mở mượt mà: File hiển thị đầy đủ số dòng ở góc dưới, không bị đơ "(Not Responding)" và không hiện hộp thoại lỗi . 
Hình ảnh minh chứng
![image](https://github.com/baob2613047-hue/NHom1_TH1/blob/1beecc213b711f1d651a6e2c586317fe7e28aae7/NV2.2_SuaLoi.png)
