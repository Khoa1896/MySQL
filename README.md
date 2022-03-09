## MySQL là gì ? 
MySQL là một hệ thống quản trị cơ sở dữ liệu mã nguồn mở (Relational Database Management System, viết tắt là RDBMS) hoạt động theo mô hình client-server. RDBMS là một phần mềm hay dịch vụ dùng để tạo và quản lý các cơ sở dữ liệu (Database) theo hình thức quản lý các mối liên hệ giữa chúng.

### Database 
Database là tập hợp dữ liệu theo cùng một cấu trúc. Hãy thử nghĩ về việc chụp hình tự sướng: bạn nhấn nút chụp ảnh về chính bản thân bạn. 
<li>Hình ảnh là dữ liệu
<li>Thư viện lưu ảnh là cơ sở dữ liệu

Cơ sở dữ liệu, hay database, là nơi chứa và sắp đặt dữ liệu. Dữ liệu được đặt trong một bộ dữ liệu chung, dataset, được tổ chức sắp xếp giống như một bảng tính vậy. Mỗi “bảng” này có liên hệ với nhau theo cách nào đó. Vì vậy từ Relational (liên hệ) trong RDBMS có ý nghĩa như vậy. Nếu phần mềm không hỗ trợ mô hình dữ liệu quan hệ với nhau như vậy thì gọi là DBMS.

### MySQL Server
MySQL Server là máy tính hay một hệ các máy tính cài đặt phần mềm MySQL dành cho server để giúp bạn lưu trữ dữ liệu trên đó, để máy khách có thể truy cập vào quản lý. Dữ liệu này được đặt trong các bảng, và các bảng có mối liên hệ với nhau. MySQL server nhanh, an toàn, đáng tin cậy

### MYSQL Client
MySQL client điển hình là đoạn mã PHP script trên một máy tính hay trên cùng server dùng để kết nối tới cơ sở dữ liệu MySQL database. Phpmyadmin cũng là một MySQL client có giao diện người dùng.

### SQL
MySQL và SQL không giống nhau.

MySQL là một trong các phần mềm RDBMS, hoạt động theo mô hình client-server. Nhưng, làm thế nào client và server liên lạc với nhau trong môi trường của RDBMS? Chúng sử dụng ngôn ngữ truy vấn có cấu trúc chung – Structured Query Language (SQL). 