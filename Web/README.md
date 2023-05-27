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


### 2. Phân loại API

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

## GET, POST, PUT, DELETE

### 1. GET

- GET là phương thức phổ biến và được sử dụng nhiều nhất trong các API và website.

- Phương thức GET được sử dụng để lấy dữ liệu từ máy chủ từ tài nguyên nào đó. Ví dụ: Bạn có API trả về danh sách người dùng. Thực hiện request GET đó sẽ trả về danh sách tất cả người dùng.

- Vì GET chỉ lấy dữ liệu về và không thay đổi bất kỳ dữ liệu nào nên GET được xem là một method an toàn. Chúng ta cũng chỉ nên sử dụng GET để lấy dữ liệu chứ không nên sử dụng để cho các chức năng cần nhập form để đăng ký/đăng nhập/...

### 2. POST

- Trong các web service, các request POST được sử dụng để gửi dữ liệu đến API server để tạo mới hoặc cập nhật dữ liệu. Dữ liệu gửi đến server được lưu trữ trong phần request body của request HTTP.

- Ví dụ: trong một form liên hệ trên một website, khi điền các input trong một form và nhấn Submit, dữ liệu đó sẽ được đưa vào phần request body của request và được gửi đến server. Đây có thể là JSON, XML hoặc query parameters...

- Request POST sẽ thay đổi dữ liệu trên backend server (tạo mới hoặc cập nhật dữ liệu), không giống với request GET không thay đổi bất kỳ dữ liệu nào.

### 3. PUT

Tương tự POST, requests PUT được dùng để gửi dữ liệu đến API cho chức năng cập nhật hoặc tạo mới dữ liệu. Sự khác biệt là PUT idempotent. Nếu sử dụng phương thức PUT nhiều lần sẽ sẽ chỉ có cùng một kết quả và nếu là tạo hoặc sửa sẽ thực hiện một lần. Còn đối với POST thì sẽ tạo ra nhiều dữ liệu.

### 4. DELETE

- DELETE có thể được nghe đến như dạng: gọi đến một URL để xóa dữ liệu.

- Nếu một người dùng mới sau khi tạo bằng POST tới /users, và sau đó có thể lấy dữ liệu băng cách GET tới /users/, vậy nếu sử dụng DELETE tới /users/ sẽ thực hiện xóa user.

## Giao thức mạng

Protocol hay Communication protocol - dịch ra là Giao thức truyền thông là một bộ quy tắc và thỏa thuận được sử dụng trong các tình huống giao tiếp hoặc trao đổi thông tin giữa các thiết bị, ứng dụng hoặc hệ thống khác nhau. Nó cung cấp một hướng dẫn cho việc xử lý thông tin và trao đổi dữ liệu giữa các bên, đảm bảo tính đúng đắn, hiệu quả và bảo mật trong quá trình truyền tải.

Protocol sẽ đảm bảo rằng dù có khác biệt về cơ sở hạ tầng, thiết kế hay tiêu chuẩn cơ bản vẫn sẽ giúp các thiết bị máy tính giao tiếp diễn ra tốt nhất.

Các protocol được sử dụng rộng rãi trong công nghệ thông tin, như các protocol để truyền tải dữ liệu qua mạng như TCP/IP, HTTP, FTP, SMTP, SSH, DNS, SNMP, và nhiều protocol khác. Các protocol cũng được sử dụng trong các lĩnh vực khác như y tế, giao thông, năng lượng và các lĩnh vực kỹ thuật khác.

### 1. Giao thức Transmission Control Protocol (TCP)

- TCP là một giao thức đáng tin cậy và toàn diện, được sử dụng để truyền tải các gói tin dữ liệu giữa các thiết bị trên mạng Internet. Nó cung cấp các tính năng điều khiển lỗi, bảo mật, truyền tải dữ liệu theo trình tự và đồng bộ hóa. TCP đảm bảo rằng các gói tin được gửi từ nguồn sẽ đến đích theo đúng thứ tự, mà không bị mất hoặc bị trùng lặp.

- Các ứng dụng của TCP bao gồm truyền tải dữ liệu qua trình duyệt web (HTTP), truyền tải thư điện tử (SMTP), truyền tải tập tin (FTP) và nhiều ứng dụng khác. TCP là một trong những giao thức mạng quan trọng nhất và được sử dụng rộng rãi trên toàn cầu.

- Để truyền tải dữ liệu, TCP sử dụng mô hình cửa sổ trượt (Sliding Window) để quản lý việc truyền tải dữ liệu giữa hai thiết bị trên mạng. Theo mô hình này, mỗi bên đều giữ một bộ đệm (buffer) để lưu trữ dữ liệu. Khi bắt đầu truyền tải, bên gửi sẽ chia dữ liệu thành các gói tin nhỏ, gọi là segment, và gửi chúng đến bên nhận. Khi bên nhận nhận được các segment, nó sẽ gửi lại cho bên gửi một thông báo xác nhận (ACK) để xác nhận việc nhận được các segment.

- TCP sử dụng cơ chế điều khiển luồng (Flow Control) để đảm bảo rằng bên nhận sẽ không bị quá tải bởi các segment được gửi từ bên gửi. Để làm điều này, TCP sử dụng một phương thức gọi là "cửa sổ trượt", trong đó bên nhận sẽ thông báo cho bên gửi về dung lượng bộ đệm mà nó có thể xử lý được. Bên gửi sẽ gửi các segment với số lượng không vượt quá dung lượng của cửa sổ trượt, và đợi ACK từ bên nhận trước khi gửi thêm các segment tiếp theo.

### 2. Giao thức Internet Protocol (IP)

- Là một trong những giao thức cơ bản trong mạng Internet. IP là giao thức truyền tải dữ liệu không đáng tin cậy, chịu trách nhiệm về việc định tuyến (routing) các gói tin dữ liệu từ nguồn đến đích trên mạng.

- IP sử dụng địa chỉ IP để xác định vị trí của các thiết bị trên mạng. Mỗi thiết bị trên mạng có một địa chỉ IP riêng, được đại diện bằng một số thập phân 32-bit (IPv4) hoặc 128-bit (IPv6). Địa chỉ IP cho phép các gói tin dữ liệu được định tuyến đến thiết bị đích trên mạng Internet.

- Các gói tin dữ liệu được truyền tải qua mạng theo kiểu chuyển tiếp (datagram), trong đó mỗi gói tin chứa địa chỉ nguồn và đích, và được truyền tải từ thiết bị nguồn đến các thiết bị trung gian trên mạng cho đến khi đến được thiết bị đích. Khi một gói tin đến được một thiết bị trung gian trên mạng, nó sẽ được xác định và định tuyến đến thiết bị kế tiếp trên đường truyền.

- Để đảm bảo tính toàn vẹn của dữ liệu, IP sử dụng một kiểm tra bảo vệ (checksum) để kiểm tra lỗi truyền tải trong quá trình truyền tải dữ liệu trên mạng. Tuy nhiên, IP không cung cấp các tính năng điều khiển lỗi, đồng bộ hóa hay bảo mật cho gói tin dữ liệu.

- IP là một phần quan trọng trong giao thức TCP/IP (Transmission Control Protocol/Internet Protocol), cung cấp các tính năng định tuyến và truyền tải dữ liệu cho các ứng dụng trên mạng Internet. IP là giao thức mạng quan trọng và được sử dụng rộng rãi trên toàn cầu.

### 3. Giao thức Hypertext Transfer Protocol (HTTP)

- Là một trong những giao thức cơ bản trong World Wide Web (WWW). HTTP được sử dụng để truyền tải các tài liệu siêu văn bản (HTML, CSS, JavaScript...) giữa các máy chủ web và trình duyệt web của người dùng.

- HTTP sử dụng mô hình yêu cầu-phản hồi (request-response) để truyền tải dữ liệu giữa các máy chủ web và trình duyệt web. Trình duyệt web sẽ gửi yêu cầu (request) đến máy chủ web, yêu cầu này bao gồm các thông tin như phương thức HTTP, URL (Uniform Resource Locator) và các tham số yêu cầu khác. Máy chủ web sẽ phản hồi (response) bằng cách gửi trả lại các tài liệu siêu văn bản (HTML, CSS, JavaScript...) được yêu cầu.

- HTTP sử dụng các phương thức HTTP như GET, POST, PUT, DELETE để chỉ định các hoạt động được thực hiện trên tài nguyên được yêu cầu. HTTP cũng hỗ trợ các mã trạng thái HTTP để thông báo về kết quả của yêu cầu (như mã trạng thái 200 OK, 404 Not Found, 500 Internal Server Error...).

- HTTP là một trong những giao thức mạng quan trọng nhất trong World Wide Web (WWW), được sử dụng rộng rãi để truyền tải các tài liệu siêu văn bản trên mạng Internet. Ngoài ra, HTTP cũng được sử dụng trong các ứng dụng web khác như Web Services, API, các ứng dụng trực tuyến,...

### 4. Giao thức File Transfer Protocol (FTP)

- là một trong những giao thức cơ bản trong việc truyền tải tập tin trên mạng Internet. FTP được sử dụng để truyền tải các tập tin giữa các máy chủ và trình duyệt của người dùng.

- FTP cũng sử dụng mô hình yêu cầu-phản hồi (request-response) giống SMTP để truyền tải tập tin giữa các máy chủ và trình duyệt của người dùng. Khi người dùng muốn tải xuống hoặc tải lên một tập tin từ máy chủ, trình duyệt của người dùng sẽ sử dụng FTP để thực hiện việc này. FTP sử dụng các lệnh như USER, PASS, RETR, STOR, LIST để quản lý quá trình truyền tải tập tin.

- FTP sử dụng cổng 21 để kết nối giữa trình duyệt và máy chủ, và sử dụng cổng 20 để truyền tải dữ liệu giữa hai bên.

- FTP là một trong những giao thức quan trọng nhất trong việc truyền tải tập tin trên mạng Internet, được sử dụng rộng rãi trong các ứng dụng truyền tải tập tin như FileZilla, WinSCP,...

### 5. Giao thức Secured Shell (SSH)

- Là một giao thức mạng được sử dụng để thiết lập kết nối an toàn tới các thiết bị từ xa. SSH cung cấp khả năng mã hóa dữ liệu để bảo vệ thông tin đăng nhập và các hoạt động của người dùng khỏi các mối đe dọa bảo mật trên mạng.

- Khi thiết lập kết nối SSH, người dùng cần cung cấp địa chỉ IP hoặc tên miền của thiết bị từ xa, cùng với tên đăng nhập và mật khẩu để xác thực quyền truy cập. Sau khi thiết lập kết nối, người dùng có thể nhập các lệnh và dữ liệu trực tiếp từ bàn phím của máy tính, và các hoạt động này sẽ được mã hóa để đảm bảo an toàn.

- SSH sử dụng phương thức mã hóa đối xứng để bảo vệ thông tin truyền tải giữa máy tính của người dùng và thiết bị từ xa. Các phiên bản mới của giao thức SSH cũng hỗ trợ phương thức mã hóa khóa công khai/ giấu khóa (public-key cryptography), cho phép các thiết bị được xác thực mà không cần sử dụng mật khẩu.

- SSH được sử dụng phổ biến trong các môi trường máy chủ và mạng lớn để thiết lập kết nối an toàn và truyền tải dữ liệu. Ngoài ra, SSH còn được sử dụng để truy cập vào các thiết bị mạng như router, switch, firewall,... để thực hiện các tác vụ quản trị.

### 6. Giao thức Telnet

- Telnet là một giao thức mạng được sử dụng để thiết lập kết nối tới một thiết bị từ xa và điều khiển nó bằng cách gửi các lệnh từ máy tính của người dùng. Giao thức Telnet sử dụng kiểu dữ liệu văn bản thuần túy để truyền tải các lệnh và dữ liệu giữa máy tính của người dùng và thiết bị từ xa.

- Khi thiết lập kết nối Telnet, người dùng cần cung cấp địa chỉ IP hoặc tên miền của thiết bị từ xa, cùng với tên đăng nhập và mật khẩu để xác thực quyền truy cập. Sau khi thiết lập kết nối, người dùng có thể nhập các lệnh và dữ liệu trực tiếp từ bàn phím của máy tính, và thiết bị từ xa sẽ thực hiện các lệnh đó.

- Cổng mặc định của Telnet là 23.

### 7. Giao thức Simple Mail Transfer Protocol (SMTP)

- Là một trong những giao thức cơ bản trong việc truyền tải email trên mạng Internet. SMTP là giao thức được sử dụng để truyền tải các email giữa các máy chủ thư điện tử (mail server) trên mạng.

- SMTP sử dụng mô hình yêu cầu - phản hồi (request - response) để truyền tải các email giữa các máy chủ thư điện tử. Khi người dùng muốn gửi một email, trình duyệt sẽ gửi email đó tới máy chủ thư điện tử của người dùng (mail client). Mail client sẽ sử dụng SMTP để gửi email đó tới máy chủ thư điện tử của người nhận (mail server). 

- SMTP sử dụng cổng 25 hoặc 587 để truyền tải email giữa các máy chủ thư điện tử. SMTP cũng hỗ trợ các lệnh SMTP như HELO, MAIL FROM, RCPT TO, DATA để quản lý quá trình gửi email.

- SMTP là một trong những giao thức quan trọng nhất trong việc truyền tải email trên mạng Internet, được sử dụng rộng rãi trong các ứng dụng email như Gmail, Yahoo Mail, Outlook… SMTP cũng được sử dụng trong các ứng dụng khác như Web Services, để truyền tải các tin nhắn trên mạng.

### 10. Giao thức Domain Name System (DNS)

- Domain Name System (DNS) được sử dụng để chuyển đổi tên miền thành địa chỉ IP. 

- Hệ thống phân cấp DNS bao gồm máy chủ gốc, TLD và máy chủ có thẩm quyền.

- Cổng mặc định của DNS là 53.

### 11. Giao thức Post Office Protocol phiên bản 3 (POP 3)

- Post Office Protocol phiên bản 3 là một trong hai giao thức chính được sử dụng để lấy mail từ Internet. 

- POP 3 rất đơn giản vì giao thức này cho phép client lấy nội dung hoàn chỉnh từ hộp thư của server và xóa nội dung khỏi server đó.

- Cổng mặc định của POP3 là 110 và cổng được bảo mật là 995.

### 12. Giao thức Internet Message Access Protocol (IMAP)

- IMAP phiên bản 3 là một giao thức chính khác được sử dụng để lấy thư từ máy chủ. IMAP không xóa nội dung khỏi hộp thư của máy chủ.

- Cổng mặc định của IMAP là 143 và cổng được bảo mật là 993.

### 13. Giao thức Simple Network Management Protocol (SNMP)

- Simple Network Management Protocol được sử dụng để quản lý mạng. 

- SNMP có khả năng giám sát, cấu hình và điều khiển các thiết bị mạng. 

- SNMP trap cũng có thể được cấu hình trên các thiết bị mạng, để thông báo cho máy chủ trung tâm khi xảy ra hành động cụ thể.

- Cổng mặc định của SNMP là 161/162.

### 14. Giao thức Hypertext Transfer Protocol over SSL/TLS (HTTPS)

- HTTPS được sử dụng với HTTP để cung cấp các dịch vụ tương tự, nhưng với kết nối bảo mật được cung cấp bởi SSL hoặc TLS.

- Cổng mặc định của HTTPS là 443.

## Giao tiếp giữa BE-FE là giao thức nào? (HTTP?)

## Webserver

### 1. Khái niệm

Web server hay máy chủ web là một máy tính được kết nối và liên kết mạng máy tính mở rộng. Máy chủ web được cài đặt các chương trình để phục vụ ứng dụng web, chứa toàn bộ dữ liệu và nắm quyền quản lý. Web server có thể lấy thông tin requess từ phía trình duyệt web và gửi phần hồi tới máy khách thông qua HTTP hoặc giao thức khác.

### 2. Cấu trúc

2 phần chính quan trọng để thực hiện cấu hình máy chủ web không thể thiếu đó là phần cứng hoặc phần mềm, đôi khi phải cả phần mềm lẫn phần cứng. 

- Về phía phần cứng:
Máy chủ web server sẽ được kết nối với internet và truy cập bằng một tên miền. Đây cũng là nơi lưu trữ các file thành phần của một website (như file ảnh, CSS, Javascript và HTML) và có thể chuyển chúng tới thiết bị người dùng cuối cùng.

- Về phía phần mềm:
Web server sẽ bao gồm các phần để điều khiển người dùng truy cập tới các file lưu trữ trên một HTTP server. Một HTTP server là một phần mềm có thể hiểu được các URL và giao thức trình duyệt đang sử dụng. Bất cứ lúc nào trình duyệt cần đến file dữ liệu trên máy chủ, trình duyệt sẽ gửi yêu cầu file đó thông qua HTTP. 

### 3. Chức năng

Chức năng cơ bản của web server không thể thiếu là lưu trữ, xử lý và phân phối nội dung website đến với khách hàng. 

- Xử lý dữ liệu qua giao thức HTTP: Xử lý và cung cấp thông tin cho khách hàng thông qua các máy tính cá nhân trên Internet qua giao thức HTTP. Nội dung được chia sẻ từ máy chủ web là những nội dung định dạng HTML, các thẻ style sheets, hình ảnh, những đoạn mã script hỗ trợ nội dung văn bản...

- Kết nối linh hoạt: Máy tính nào cũng có thể là một máy chủ nếu nó được cài đặt một chương trình phần mềm server và có kết nối internet.

- Chương trình chuyển đổi thông minh: Phần mềm web server cũng giống như các phần mềm khác, nó cho phép người dùng cài đặt và hoạt động trên bất kỳ máy tính nào đáp ứng đủ yêu cầu về bộ nhớ.

- Lưu trữ dữ liệu trên hình thức thuê các máy chủ nhỏ, máy chủ áo VPS hoặc hosting.