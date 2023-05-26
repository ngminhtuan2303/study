# WEB

## Frontend và Backend

### 1. Frontend

- Front end là một phần của một website ở đó người dùng có thể tương tác để sử dụng bao gồm tất cả những gì mà bạn nhìn thấy trên một website bao gồm: font chữ, màu sắc, danh mục sản phẩm, menu, thanh trượt, v.v. 

- 3 ngôn ngữ chính trong lập trình Frontend là: HTML, CSS, JavaScript

- Ngoài ra còn cần biết các framework như Bootstrap, Foundation, Backbone, AngularJS, và EmberJS, để đảm bảo nội dung luôn hiển thị tốt trên mọi thiết bị khác nhau, và các thư viện như jQuery và LESS, đóng gói code vào trong một hình thức giúp tiết kiệm thời gian và hữu dụng hơn.

### 2. Backend

- Backend là những chức năng hỗ trợ hoạt động của một trang web hoặc ứng dụng mà người dùng không nhìn thấy được. Nó có cơ chế hoạt động gần  giống như bộ não của con người, xử lý các yêu cầu, lệnh và chọn thông tin thích hợp để hiển thị trên màn hình.

- Backend của một trang web bao gồm ba thành phần: máy chủ, ứng dụng và cơ sở dữ liệu. Điều này cho phép trang web hoạt động hiệu quả và cung cấp cho người dùng thông tin chính xác nhanh chóng.

- Các ngôn ngữ thường được sử dụng trong Backend để xây dựng một ứng dụng là: PHP, Ruby, Python, Java, và .Net...

- Sử dụng các công cụ như MySQL, Oracle, SQL Server... để tìm kiếm, lưu trữ, hoặc thay đổi dữ liệu và phục vụ trở lại tới người dùng trong phần Frontend.  

## Phương pháp giao tiếp giữa Frontend và Backend

## API

### 1. API là gì?

- API là cơ chế cho phép 2 thành phần phần mềm giao tiếp với nhau bằng một tập hợp các định nghĩa và giao thức. 

- API là tên viết tắt của từ Application Programming Interface, hay còn gọi là giao diện lập trình của ứng dụng. API có khả năng cung cấp việc truy xuất đến một trong các hàm hay sử dụng. Từ đó, nó có thể trao đổi được các dữ liệu giữa một số ứng dụng cụ thể. API có thể sử dụng cho web-based system, operating system, database system, computer hardware và software library.

API hoạt động theo 4 cách khác nhau:

- API SOAP: Các API này sử dụng Giao thức truy cập đối tượng đơn giản. Máy chủ và máy khách trao đổi thông đệp bằng XML. Đây là loại API kém linh hoạt được dùng phổ biến trước đây.

- API RPC: Những API này được gọi là Lệnh gọi thủ tục từ xa. Máy khách hoàn thành một hàm (hoặc thủ tục) trên máy chủ còn máy chủ gửi kết quả về cho máy khách.

- API Websocket: là một bản phát triển API web hiện đại khác sử dụng các đối tượng JSON để chuyển dữ liệu. API WebSocket hỗ trợ hoạt động giao tiếp hai chiều giữa ứng dụng máy khách và máy chủ. Máy chủ có thể gửi thông điệp gọi lại cho các máy khách được kết nối, điều này khiến loại API này hiệu quả hơn API REST.

- API REST: Đây là loại API phổ biến và linh hoạt nhất trên web hiện nay. Máy khách gửi yêu cầu đến máy chủ dưới dạng dữ liệu. Máy chủ dùng dữ liệu đầu vào từ máy khách này để bắt đầu các hàm nội bộ và trả lại dữ liệu đầu ra cho máy khách. Hãy cùng xem xét API REST chi tiết hơn ở bên dưới.


### 2. Các loại API

Có nhiều cách để phân loại API. Một cách thường gặp là phân theo quyền hạn truy cập, gồm có:

- Open API: Còn được gọi là Public API, không có hạn chế nào khi truy cập các loại API này vì chúng có sẵn công khai.

- Partner API: Cần các quyền hoặc giấy phép cụ thể để truy cập loại API này vì chúng không có sẵn công khai.

- Internal API: Còn được gọi là Private API, chỉ các hệ thống nội bộ mới dùng loại API này, do đó chúng ít được biết đến và thường được sử dụng trong phạm vi công ty. Công ty sử dụng loại API này trong các đội ngũ phát triển nội bộ khác nhau để có thể cải thiện các sản phẩm và dịch vụ của mình.

- Composite API: Loại này kết hợp các API dịch vụ và dữ liệu khác nhau. Chức năng của Composite API được đặc trưng bởi một chuỗi các tác vụ chạy đồng bộ. Công dụng chính của API tổng hợp là để tăng tốc quá trình thực thi cũng như cải thiện hiệu suất cho listeners  trong web interface.

## StatusCode

### 1. StatusCode là gì?

- Status code (mã trạng thái) là mã code server trả về sau mỗi lần gửi request. Tất cả các request mà server nhận được đều sẽ được trả về 1 response với 1 mã code tương ứng.

- Các HTTP status code là chuẩn để server trả về. HTTP status code giúp xác định request thành công hay không, nếu thất bại thì nguyên nhân là gì.

### 2. Các loại StatusCode

Status code là một số nguyên 3 ký tự, trong đó ký tự đầu tiên của Status-Code định nghĩa loại Response và hai ký tự cuối không có bất cứ vai trò phân loại nào. Có 5 giá trị của ký tự đầu tiên:

- 1xx: Information (Thông tin): Khi nhận được những mã như vậy tức là request đã được server tiếp nhận và quá trình xử lý request đang được tiếp tục.

- 2xx: Success (Thành công): Khi nhận được những mã như vậy tức là request đã được server tiếp nhận, hiểu và xử lý thành công

- 3xx: Redirection (Chuyển hướng): Mã trạng thái này cho biết client cần có thêm action để hoàn thành request

- 4xx: Client Error (Lỗi Client): Nó nghĩa là request chứa cú pháp không chính xác hoặc không được thực hiện.

- 5xx: Server Error (Lỗi Server): Nó nghĩa là Server thất bại với việc thực hiện một request nhìn như có vẻ khả thi.

## Websocket

### 1. Websocket là gì?

- Websocket là giao thức hỗ trợ giao tiếp hai chiều giữa client và server để tạo một kết nối trao đổi dữ liệu. Giao thức này không sử dụng HTTP mà thực hiện nó qua TCP. Mặc dù được thiết kế để chuyên sử dụng cho các ứng dụng web, lập trình viên vẫn có thể đưa chúng vào bất kì loại ứng dụng nào.

- WebSocket cung cấp giao thức giao tiếp hai chiều mạnh mẽ. Nó có độ trễ thấp và dễ xử lý lỗi. Websocket thường được sử dụng cho những trường hợp yêu cầu real time như chat, hiển thị biểu đồ hay thông tin chứng khoán.

### 2. Cấu trúc

![alt](https://topdev.vn/blog/wp-content/uploads/2019/06/websocket-la-gi.png)

Giao thức chuẩn thông thường của WebSocket là ws:// , giao thức secure là wss:// . Chuẩn giao tiếp là String và hỗ trợ buffered arrays và blobs.

### 3. Các thuộc tính của WebSocket

readyState: Diễn tả trạng thái kết nối. Nó có các giá trị sau:
- Giá trị 0: kết nối vẫn chưa được thiết lập (WebSocket.CONNECTING)
- Giá trị 1: kết nối đã thiết lập và có thể giao tiếp (WebSocket.OPEN)
- Giá trị 2: kết nối đang qua handshake đóng (WebSocket.CLOSING)
- Giá trị 3: kết nối đã được đóng (WebSocket.CLOSED)

bufferedAmount: Biểu diễn số byte của UTF-8 mà đã được xếp hàng bởi sử dụng phương thức send()

### 4. Các sự kiện WebSocket

| SỰ KIỆN | EVENT HANDLER | MÔ TẢ |
|:-------:|:-------------:|:-----:|
|open|onopen|Khi một WebSocket chuyển sang trạng thái mở, “onopen” sẽ được gọi.|
|message|onmessage|Khi WebSocket nhận dữ liệu từ Server.|
|error|onerror|Có bất kỳ lỗi nào trong giao tiếp.|
|close|onclose|Kết nối được đóng. Những sự kiện được truyền cho “onclose” có ba tham số là “code”, “reason”, và “wasClean”.|

### 5. Các phương thức của WebSocket

- send(): send(data) gửi dữ liệu tới server. Message data là string, ArrayBuffer, blob.

- close(): Đóng kết nối đang tồn tại.

## Socket.IO

### 1. Socket.IO là gì?

- Socket.IO là công cụ kết nối mở cho phép máy chủ và máy khách giao tiếp hai chiều với nhau theo thời gian thực. Khi máy chủ có Socket.IO và máy khách có gói Socket.IO trong trình duyệt thì việc liên kết sẽ được thực hiện.

### 2. Socket.IO hoạt động như thế nào?

- Socket.IO sử dụng tính năng giao tiếp hai chiều để phát triển các ứng dụng trò chuyện. Các tin nhắn gửi về máy chủ sẽ được gửi trực tiếp cho máy khách mà không cần bất cứ yêu cầu trung gian nào.