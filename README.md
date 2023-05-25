# study
## 1. Git là gì?
- Git là một hệ thống quản lý mã nguồn phân tán (Distributed Version Control System – DVCS). Git cung cấp cho mỗi lập trình viên kho lưu trữ (repository) gọi tắt là Repo là nơi chứa cơ sở dữ liệu (database) tất cả những thông tin cần thiết để duy trì và quản lý các sử đổi và lịch sử của dự án. Git trở thành một trong các phần mềm quản lý mã nguồn phổ biến nhất.
- Git là một hệ thống kiểm soát phiên bản (Version Control System) mã nguồn mở miễn phí. Nó theo dõi các project và file khi chúng thay đổi theo thời gian. Cùng với đó là sự trợ giúp của những người đóng góp khác nhau.
## 2. Các hành động trong Git
- Để bắt đầu Git, chuyển đến terminal và chạy lệnh sau trong thư mục dự án của bạn để khởi tạo một thư mục dự án: **git init**
- Chạy lệnh sau để thêm file cho Git theo dõi. Thao tác này sẽ thêm các file này vào staging area: **git add <filename_one>**
- Chạy lệnh sau để commit các thay đổi của bạn đối với các file này: **git commit <filename_one>**
- Và chúng ta có thể push các thay đổi của mình sau khi hoàn tất: **git push**
- Cùng với việc thực hiện thêm bất kỳ thay đổi nào trong branch master sẽ yêu cầu các thay đổi này phải được commit lại.