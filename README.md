# Intrusion Detection Systems

Hệ thống phát hiện xâm nhập (IDS) là hệ thống phần mềm hoặc phần cứng tự động hóa tiến trình giám sát các sự kiện xảy ra trong hệ thống máy tính hoặc mạng, phân tích chúng để tìm ra các dấu hiệu của sự cố bảo mật. Khi các cuộc tấn công mạng ngày càng tăng về số lượng và mức độ nghiêm trọng trong vài năm qua, các hệ thống phát hiện xâm nhập đã trở thành một bổ sung cần thiết cho cơ sở hạ tầng bảo mật của hầu hết các tổ chức.

1. Tổng quan về IDS

1.1.Phát hiện xâm nhập là gì?

Phát hiện xâm nhập là quá trình theo dõi các sự kiện xảy ra trong hệ thống máy tính hoặc mạng và phân tích chúng để tìm các dấu hiệu xâm nhập, được định nghĩa là các nỗ lực nhằm xâm nhập tính bí mật, tính toàn vẹn, tính khả dụng (CIA) hoặc để vượt qua các cơ chế bảo mật của máy tính hoặc mạng. Sự xâm nhập là do những kẻ tấn công truy cập hệ thống từ Internet, người dùng được ủy quyền của hệ thống cố gắng đạt được các đặc quyền bổ sung mà họ không được ủy quyền và những người dùng được ủy quyền sử dụng sai các đặc quyền được cấp cho họ. Hệ thống phát hiện xâm nhập (IDS) là các sản phẩm phần mềm hoặc phần cứng tự động hóa quá trình giám sát và phân tích này.

1.2. Tại sao phải dùng IDS??

Tính năng phát hiện xâm nhập cho phép các tổ chức bảo vệ hệ thống của họ khỏi các mối đe dọa đi kèm với sự gia tăng kết nối mạng và sự phụ thuộc vào hệ thống thông tin.
Với mức độ và bản chất của các mối đe dọa an ninh mạng hiện đại, câu hỏi đặt ra cho các chuyên gia bảo mật không phải là có nên sử dụng tính năng phát hiện xâm nhập hay không mà là sử dụng các tính năng và khả năng phát hiện xâm nhập nào.

IDS đã được chấp nhận như một sự bổ sung cần thiết cho cơ sở hạ tầng bảo mật của mọi tổ chức. Bất chấp những đóng góp đã được ghi nhận trong tài liệu về công nghệ phát hiện xâm nhập đối với bảo mật hệ thống, trong nhiều tổ chức, người ta vẫn phải biện minh cho việc mua lại IDS. Có một số lý do thuyết phục để có được và sử dụng IDS:


The event, or signature-based: hoạt động giống như phần mềm chống vi-rút mà hầu hết mọi người đều quen thuộc. Nhà cung cấp tạo ra một danh sách các mẫu mà họ cho là đáng ngờ hoặc là dấu hiệu của một cuộc tấn công; IDS chỉ đơn thuần quét môi trường để tìm kiếm sự phù hợp với các mẫu đã biết. Sau đó, IDS có thể phản hồi bằng cách thực hiện hành động do người dùng xác định, gửi cảnh báo hoặc thực hiện ghi nhật ký bổ sung. Đây là loại hệ thống phát hiện xâm nhập phổ biến nhất.

Network IDS thường có hai thành phần logic: sensor và management station. Sensor nằm trên một phân đoạn mạng, giám sát nó để biết lưu lượng truy cập đáng ngờ. management station nhận các cảnh báo từ (các) sensor và hiển thị chúng cho người vận hành.

Sensor là các hệ thống chuyên dụng chỉ tồn tại để giám sát mạng. Chúng có giao diện mạng ở chế độ quảng bá, có nghĩa là chúng nhận được tất cả lưu lượng mạng, không chỉ dành riêng cho địa chỉ IP của chúng và chúng nắm bắt lưu lượng mạng đi qua để phân tích. Nếu họ phát hiện điều gì đó có vẻ bất thường, họ sẽ chuyển nó trở lại trạm phân tích.

Host IDS

The host-based IDS tìm kiếm các dấu hiệu xâm nhập vào hệ thống máy chủ cục bộ. Những điều này thường sử dụng cơ chế kiểm tra và ghi nhật ký của hệ thống máy chủ lưu trữ như một nguồn thông tin để phân tích.

Chúng tìm kiếm hoạt động bất thường được giới hạn trong máy chủ cục bộ như đăng nhập, truy cập tệp không đúng cách, báo cáo đặc quyền chưa được phê duyệt hoặc các thay đổi về đặc quyền hệ thống. Kiến trúc IDS này thường sử dụng các công cụ dựa trên quy tắc để phân tích hoạt động. Do đó, các nỗ lực đăng nhập liên tiếp vào tài khoản gốc có thể được coi là một cuộc tấn công

Các thành phần của IDS
![image](https://user-images.githubusercontent.com/72652376/184272733-36b3d003-88f9-4525-a22d-64b03ab13e3d.png)


