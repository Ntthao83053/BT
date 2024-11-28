# BT
## Chương 1: Tổng quan về cấu trúc máy tính
 **1.1** Cấu trúc máy tính:

  - CPU (Central Processing Unit): Bộ xử lý trung tâm, gồm:
       CU (Control Unit): Đơn vị điều khiển.
       ALU (Arithmetic Logic Unit): Đơn vị toán học và logic.
       RF (Register File): Tập thanh ghi lưu trữ tạm thời.
  - GPU (Graphics Processing Unit): Xử lý đồ họa.
  - RAM (Random Access Memory): Bộ nhớ tạm thời, truy cập nhanh.
  - ROM (Read-Only Memory): Bộ nhớ chỉ đọc, lưu thông tin khởi động.
  - SSD (Solid State Drive): Bộ nhớ lưu trữ nhanh và bền.
  - HDD (Hard Disk Drive): Bộ nhớ lưu trữ lớn, tốc độ chậm hơn SSD.
  - Bo mạch chủ (Motherboard): Kết nối tất cả các thành phần của máy tính.
**1.2** Các thế hệ máy tính:

  - Thế hệ 1 (1940-1956): Sử dụng đèn chân không.
  - Thế hệ 2 (1956-1963): Sử dụng transistor.
  - Thế hệ 3 (1964-1971): Sử dụng mạch tích hợp (IC).
  - Thế hệ 4 (1971-1980s): Máy tính cá nhân, sử dụng vi xử lý.
  - Thế hệ 5 (1980s-nay): Trí tuệ nhân tạo (AI), máy tính lượng tử.
**1.3** Phần cứng, phần mềm, hệ điều hành:

  - Phần cứng:
     a, Bộ xử lý trung tâm (CPU - Central Processing Unit)
     + Bộ nhớ (Memory)
        RAM (Random Access Memory): Bộ nhớ tạm thời, lưu dữ liệu để CPU xử lý.
        ROM (Read-Only Memory): Bộ nhớ chỉ đọc, lưu trữ chương trình khởi động hệ thống.
        Cache Memory: Bộ nhớ đệm tốc độ cao gần CPU, lưu trữ dữ liệu hay được sử dụng.
        Virtual Memory: Không phải phần cứng vật lý mà là một phần của ổ đĩa được hệ điều hành sử dụng như RAM tạm thời.
     + Bộ lưu trữ (Storage Devices)
        HDD (Hard Disk Drive): Ổ cứng truyền thống, dung lượng lớn, giá rẻ nhưng tốc độ chậm hơn.
        SSD (Solid State Drive): Ổ cứng thể rắn, tốc độ nhanh, độ bền cao hơn HDD.
        USB Flash Drive: Thiết bị lưu trữ di động nhỏ gọn.
        CD/DVD Drive (không phổ biến hiện nay): Đọc/ghi dữ liệu từ đĩa quang.
     + Bo mạch chủ (Motherboard)
     + Card đồ họa (GPU - Graphics Processing Unit)
     + Nguồn máy tính (Power Supply Unit - PSU) Cung cấp năng lượng cho toàn bộ hệ thống máy tính.
    b, Thiết bị ngoại vi (Peripheral Devices)
     + Thiết bị đầu vào (Input Devices): Dùng để nhập dữ liệu vào máy tính:
     + Thiết bị đầu ra (Output Devices)
     + Thiết bị đầu vào/ra (Input/Output Devices): Một số thiết bị có thể thực hiện cả hai chức năng:
        Màn hình cảm ứng (Touchscreen)
        Ổ đĩa USB
        Tai nghe (Headset): Có tích hợp micro.
    c, Các thành phần mạng và kết nối
     + Card mạng (NIC - Network Interface Card): Kết nối máy tính với mạng (Ethernet hoặc Wi-Fi).
     + Modem/Router: Thiết bị mạng dùng để kết nối Internet.
     + Bluetooth Adapter: Kết nối không dây với các thiết bị khác.
        Vỏ máy tính và các phụ kiện khác
    d, Vỏ máy (Case): Bao bọc và bảo vệ các linh kiện bên trong.
     + Hệ thống tản nhiệt: Bao gồm quạt hoặc bộ làm mát (cooler) để giảm nhiệt độ cho CPU và GPU.
    e,  Phần cứng đặc biệt (Dành cho nhu cầu riêng)
     + Card âm thanh (Sound Card): Cải thiện chất lượng âm thanh.
     + Card mạng chuyên dụng: Dùng trong các hệ thống server.
     + Phần cứng AI hoặc Machine Learning: Các bộ xử lý chuyên dụng như TPU (Tensor Processing Unit).

  - Phần mềm: Chương trình chạy trên máy tính.
  - Hệ điều hành (OS): Quản lý phần cứng, phần mềm (Windows, Linux...).
**1.4** bộ sử lý trung tâm:
  - Đơn vị điều khiển (CU-Control Unit)
  - Đơn vị số học và logic (ALU-Arithmetic)
  - tập thanh ghi (RF-Register File)
  - Đơn vị giao diện Bus (BIU-Bus interface Unit)
**1.5** Bộ nhớ chính (Main memory) vs. Bộ nhớ đệm (Cache memory):
  - Main memory: Lưu trữ tạm thời, dung lượng lớn hơn, tốc độ 3.2** Phím tắt thao tác với file/thư mục:

  - Copy (Ctrl+C), Cut (Ctrl+X), Paste (Ctrl+V).
  - Tạo thư mục mới: Ctrl+Shift+N.
## Chương 2:Thông tin và hệ thống 
 **2.1** Hệ thống số trong máy tính
  - Hệ thập phân (Decimal - cơ số 10): Là hệ số phổ biến nhất, sử dụng 10 ký tự từ 0-9.
     Ví dụ: 123 trong hệ thập phân biểu diễn giá trị 100 + 20 + 3.                             
  - Hệ nhị phân (Binary - cơ số 2): Dùng hai ký tự 0 và 1, được sử dụng trong máy tính để biểu diễn dữ liệu.
     Ví dụ: 101 trong hệ nhị phân tương đương với 1×2² + 0×2¹ + 1×2⁰ = 5 trong thập phân.
  - Hệ bát phân (Octal - cơ số 8): Sử dụng 8 ký tự từ 0-7. Thường được sử dụng làm rút gọn cho hệ nhị phân.
     Ví dụ: 17 trong hệ bát phân là 1×8¹ + 7×8⁰ = 15 trong thập phân.
  - Hệ thập lục phân (Hexadecimal - cơ số 16): Sử dụng 16 ký tự: 0-9 và A-F (trong đó A=10, B=11, ..., F=15).
    Thường được sử dụng để biểu diễn màu sắc hoặc mã hóa bộ nhớ.
    Ví dụ: 1A trong hệ thập lục phân là 1×16¹ + 10×16⁰ = 26 trong thập phân.
 **2.2** Ứng Dụng của Biểu Diễn Thông Tin
  - Xử lý số học: Biểu diễn số nguyên và số thực để tính toán.
  - Lưu trữ dữ liệu: Số hóa văn bản, hình ảnh, âm thanh để lưu trữ trong máy tính.
  - Truyền dữ liệu: Dữ liệu nhị phân được truyền qua mạng hoặc thiết bị lưu trữ.
  - Mã hóa và bảo mật: Biểu diễn thông tin dưới dạng nhị phân để mã hóa thông tin an toàn.
## Chương 3: Kĩ năng sử dụng máy tính và công cụ
**3.1** Cấu Trúc Cây Thư Mục
   - Cấu trúc cây thư mục (Directory Tree Structure) là cách tổ chức các tệp tin và thư mục (folders) trên một hệ thống tệp (file system) theo dạng phân cấp, giống như cấu trúc của một cây. Dưới đây là chi tiết về cấu trúc cây thư mục, cách hoạt động và vai trò của nó.
    + Thư mục gốc (Root Directory): Là thư mục cao nhất trong cây, từ đó các thư mục con được tạo ra.
    + Thư mục con (Subdirectory): Là các thư mục nằm trong thư mục khác.
    + Tệp tin (File): Là các dữ liệu cụ thể như văn bản, hình ảnh, video, nằm trong thư mục.
    + Đường dẫn:
      Đường dẫn tuyệt đối (Absolute Path): Bắt đầu từ thư mục gốc, ví dụ: /home/user/documents/file.txt.
      Đường dẫn tương đối (Relative Path): Dựa vào vị trí hiện tại, ví dụ: documents/file.txt.
    + Hệ thống file bắt đầu từ thư mục gốc. Tùy thuộc vào hệ điều hành:
      Trên Linux và macOS: Thư mục gốc ký hiệu là /.
      Trên Windows: Mỗi ổ đĩa là một thư mục gốc (ví dụ: C:\).

## Chương 4: Hệ điều hành Linux và các lệnh cơ bản trong hệ điều hành 
 **4.1** Lệnh cơ bản:

  - cd: Di chuyển giữa các thư mục.
  - ls: Liệt kê nội dung thư mục.
  - mkdir: Tạo thư mục mới.
  - rmdir: Xóa thư mục rỗng.
  - cat: Hiển thị nội dung file.
  - cp: Sao chép file/thư mục.
  - rm: Xóa file/thư mục.
  - touch: Tạo file trống.
   **4.2** Hệ thống tệp và quyền:
  - Các loại tệp trong linux:
     + Tệp thông thường (Regular File): Dùng để lưu trữ dữ liệu, văn bản, chương trình.
     + Thư mục (Directory): Chứa các tệp và thư mục con.
     + Tệp liên kết (Link): Tệp tham chiếu đến một tệp hoặc thư mục khác.
     + Tệp đặc biệt (Special File):
        Character device files: Đại diện thiết bị nhập/xuất theo ký tự.
        Block device files: Đại diện thiết bị lưu trữ theo khối.
  - Quyền cơ bản:
     + Read (r): Quyền đọc tệp/thư mục.
     + Write (w): Quyền ghi, sửa đổi nội dung tệp hoặc thêm/xóa tệp trong thư mục.
     + Execute (x): Quyền thực thi tệp (chạy tệp thực thi) hoặc truy cập thư mục.
  - Cách thay đổi quyền:
     chmod u+x file.txt  # Thêm quyền thực thi cho chủ sở hữu.
     chmod g-w file.txt  # Bỏ quyền ghi của nhóm.
## chương 5: Git và ứng dụng
 **5.1** Các khái niệm chính trong Git
  - Repository (Repo): Kho lưu trữ, nơi chứa toàn bộ mã nguồn và lịch sử thay đổi.
  - Commit: Một điểm chụp lại trạng thái hiện tại của dự án, bao gồm mã nguồn và các thay 
       đổi.
  - Branch: Nhánh, giúp phân tách các luồng công việc độc lập.
     Merge: Hợp nhất các nhánh sau khi làm việc riêng lẻ.
  - Conflict: Xung đột xảy ra khi nhiều người chỉnh sửa cùng một nội dung.
  **5.2** Quy trình làm việc với Git
  - Khởi tạo kho (Initialize Repository): git init để tạo một repository mới.
  - Thêm tệp vào vùng theo dõi (Staging Area): git add <tên_tệp> để đưa tệp vào trạng thái 
        chuẩn bị commit.
  - Lưu thay đổi (Commit): git commit -m "Mô tả thay đổi" để lưu các thay đổi vào lịch sử.
  - Làm việc với nhánh (Branches):
     + Tạo nhánh mới: git branch <tên_nhánh>.
     + Chuyển đổi nhánh: git checkout <tên_nhánh> hoặc git switch <tên_nhánh>.
     + Hợp nhất nhánh: git merge <tên_nhánh>.
  - Đồng bộ với kho từ xa (Remote Repository):
     + Kết nối với kho từ xa: git remote add origin <URL>.
     + Đẩy thay đổi: git push origin <tên_nhánh>.
     + Lấy thay đổi: git pull origin <tên_nhánh>.
## Chương 6: ACM Code of Conduct
 **6.1** Các mối đe dọa phổ biến trong không gian số:
  - Phần mềm độc hại (Malware): Virus, trojan, ransomware và spyware có thể đánh cắp thông tin 
     hoặc gây hư hại thiết bị.
  - Tấn công lừa đảo (Phishing)
  - Tấn công từ chối dịch vụ (DDoS): Làm quá tải hệ thống, khiến dịch vụ trực tuyến không thể 
     hoạt động.
  - Xâm phạm quyền riêng tư
  - Tấn công mạng xã hội: Mạo danh, phát tán tin giả, hoặc sử dụng tài khoản người khác để 
     thực hiện hành vi xấu.
 **6.2** Nguyên tắc để đảm bảo an toàn:
  - Sử dụng mật khẩu mạnh
  - Cập nhật phần mềm thường xuyên
  - Cảnh giác với email và tin nhắn lạ:
  - Sử dụng xác thực hai yếu tố (2FA):
  - Sử dụng phần mềm bảo mật:
  - Kiểm soát quyền truy cập ứng dụng:
  - Duy trì ý thức bảo mật
 **6.3** Các nguyên tắc đạo đức:
  - Tôn trọng quyền riêng tư
  - Trách nhiệm và trung thực
  - Không gây hại
  - Tôn trọng tài sản trí tuệ
  - Nâng cao hiểu biết và kỹ năng

## Chương 7+8: Wordpress
  - WordPress là một hệ quản trị nội dung (CMS - Content Management System) mã nguồn mở, miễn phí, được sử dụng phổ biến nhất để tạo và quản lý các trang web.
  - Tạo website mới:
    + Bước 1: Cài đặt WordPress
      Chọn hosting và domain:
      Tải xuống WordPress:
      Cài đặt WordPress:
    + Bước 2: Tùy chỉnh giao diện
      Cài đặt theme:
      Tùy chỉnh giao diện: Appearance → Customize để chỉnh sửa logo, màu sắc, và bố cục.
    + Bước 3: Cài đặt plugin
    + Bước 4: Tạo nội dung
      Tạo bài viết (Post): Vào Dashboard → Posts → Add New để viết blog hoặc bài viết mới.
      Tạo trang (Page): Vào Dashboard → Pages → Add New để tạo trang như "Giới thiệu", "Liên hệ".
    + Bước 5: Cấu hình trang web
      Settings → General: Đặt tên trang, slogan.
      Settings → Permalinks: Tùy chỉnh cấu trúc URL thân thiện với SEO.


## Chương 9: Thuật toán ứng dụng
 **9.1** Thuật toán: Thuật toán là một tập hợp hữu hạn các bước được xác định rõ ràng để giải 
     quyết một vấn đề hoặc thực hiện một nhiệm vụ cụ thể.
   - Biểu diễn thuật toán:
     + Liệt kê
     + Sử dụng sơ đồ khối
   - Độ phức tạp của thuật toán:
     + Độ phức tạp thời gian (Time Complexity):
     + Độ phức tạp không gian (Space Complexity): Đo lường lượng bộ nhớ mà thuật toán sử dụng 
       trong suốt quá trình thực hiện.
  - Ký hiệu Big-O (Asymptotic Notation): 
     + O(1) – Hằng số: Thời gian không phụ thuộc vào kích thước đầu vào.
     + O(logn) – Logarithmic: Thời gian tăng theo log của kích thước đầu vào (ví dụ: 
        tìm kiếm nhị phân).
     + O(n) – Tuyến tính: Thời gian tỷ lệ thuận với kích thước đầu vào.
     + O(nlogn) – Tuyến tính-logarithmic: Thường thấy trong thuật toán sắp xếp tối 
        ưu (như Merge Sort).
     + O(n 2 ) – Bậc hai: Thời gian tăng theo bình phương của đầu vào (ví dụ: Bubble 
        Sort).
     + O(2 n) – Hàm mũ: Thời gian tăng cực nhanh theo kích thước đầu vào (ví dụ: bài 
        toán tháp Hà Nội).

     + O(n!) – Giai thừa: Thường gặp trong các bài toán tổ hợp phức tạp.
  **9.2** Ứng dụng:
    - Tìm kiếm và sắp xếp dữ liệu
    - Nén dữ liệu
    - Mạng máy tính
    - Mã hóa và bảo mật
    - Lập kế hoạch và tối ưu hóa

## Chương 10:Python
 **10.1** Giới thiệu về python:
    - Python là một ngôn ngữ lập trình bậc cao, mã nguồn mở, và đa mục đích, được phát triển bởi Guido van Rossum vào năm 1991.
    - Python nổi bật với cú pháp đơn giản, dễ đọc và dễ học, phù hợp cho cả người mới bắt đầu và các chuyên gia lập trình.
  **10.2** Lệnh cơ bản trong python:
    - print(): Lệnh cơ bản dùng để in thông tin ra màn hình.
    - if, elif, else: Dùng để kiểm tra điều kiện.
    - Vòng lặp for: Dùng để lặp qua một dãy hoặc danh sách.
    - Định nghĩa hàm: Sử dụng từ khóa def để định nghĩa hàm.
    - is và ==: Dùng để so sánh.
    - try và except: Dùng để bắt lỗi khi có ngoại lệ xảy ra.
    
# **Bài kiểm tra: Cấu trúc cây thư mục**

## **1. Trắc nghiệm chọn 1 đáp án**
### Câu hỏi 1:
Trong cấu trúc cây thư mục Linux, thư mục nào chứa các tệp tạm thời được tạo trong quá trình hệ thống hoạt động?  

A. `/var`  
B. `/tmp`  
C. `/etc`  
D. `/usr`  

**Đáp án đúng:** B  

---

## **2. Trắc nghiệm chọn nhiều đáp án**
### Câu hỏi 2:
Chọn các thư mục trong cấu trúc cây thư mục Linux có liên quan đến việc lưu trữ dữ liệu của hệ thống hoặc nhật ký:  

A. `/var/log`  
B. `/home`  
C. `/tmp`  
D. `/etc`  
E. `/dev`  

**Đáp án đúng:** A, C, D  

---

## **3. Điền vào chỗ trống**
### Câu hỏi 3:
Trong cấu trúc cây thư mục của hệ điều hành Linux, thư mục __________ được sử dụng để chứa các tệp thực thi cần thiết cho hệ thống khởi động.  

**Đáp án đúng:** `/bin`  









