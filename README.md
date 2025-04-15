# Bai tap 4
# bai tap 4: (sql server)
yêu cầu bài toán:
 - Tạo csdl cho hệ thống TKB (đã nghe giảng, đã xem cách làm)
 - Nguồn dữ liệu: TMS.tnut.edu.vn
 - Tạo các bảng tuỳ ý (3nf)
 - Tạo được query truy vấn ra thông tin gồm 4 cột: họ tên gv, môn dạy, giờ vào lớp, giờ ra.
   trả lời câu hỏi: trong khoảng thời gian từ datetime1 tới datetime2 thì có những gv nào đang bận giảng dạy.

các bước thực hiện:
1. Tạo github repo mới: đặt tên tuỳ ý (có liên quan đến bài tập này)
2. tạo file readme.md, edit online nó:
   paste những ảnh chụp màn hình
   gõ text mô tả cho ảnh đó

Gợi ý:
  sử dung tms => dữ liệu thô => tiền xử lý => dữ liệu như ý (3nf)
  tạo các bảng với struct phù hợp
  insert nhiều rows từ excel vào cửa sổ edit dữ liệu 1 table (quan sát thì sẽ làm đc)

  ##
  #
  #
  ## bài làm:
  # tạo 1 sơ sở dữ liệu mới và tiến hành tạo các bảng 

![Screenshot (299)](https://github.com/user-attachments/assets/b9108647-0a80-428e-8ec5-e8950e81d813)
![Screenshot (300)](https://github.com/user-attachments/assets/fd7998b7-3a7b-4f69-b716-cc92d3520068)
![Screenshot (301)](https://github.com/user-attachments/assets/e9a536bf-d852-4a30-862c-7179d59da19e)

# thiết lập khóa chính và khóa quan hệ ta có quan hệ như sau 

![Screenshot (302)](https://github.com/user-attachments/assets/b07f7855-3c07-4a01-891a-2fb9601bf294)

# tiến hành sử dụng dữ liệu từ TMS.tnut.edu.vn bài này mình sẽ lấy bảng của 1 tuần để làm demo 

![Screenshot (304)](https://github.com/user-attachments/assets/11829fd9-ab3d-4e2d-b963-f29070985c08)
![Screenshot (305)](https://github.com/user-attachments/assets/b415b749-0e84-4b1e-99e2-cc493c842bf1)
# và các bảng còn lại khác
# Tạo được query truy vấn ra thông tin gồm 4 cột: họ tên gv, môn dạy, giờ vào lớp, giờ ra.
![image](https://github.com/user-attachments/assets/40f03c57-7fef-48ac-bd76-eed72885bad0)

