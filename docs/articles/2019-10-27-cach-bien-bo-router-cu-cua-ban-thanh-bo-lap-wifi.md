---
title: Cách biến bộ router cũ của bạn thành bộ lặp WiFi
cover: 'https://ucarecdn.com/46ceff7a-33bf-4235-bb4e-e72b3fa21714/'
date: '2019-10-27'
editorial: livings
authors:
  - 2019-1-pham-xuan-tiep
semester: 2019/2
tags:
  - Wifi
  - Router
  - Mạng
featured: false
headline: >-
  Internet bây giờ đã trở thành một phần không thể thiếu trong xã hội và cuộc
  sống hàng ngày của chúng ta. Nó được sử dụng như cả phương tiện giải trí
  chính, cách chúng ta kết nối với bạn bè và gia đình và đối với một số người,
  một yếu tố quan trọng trong công việc của họ.
---
Với mọi thứ ngày nay không dây, bộ định tuyến WiFi cũng đã trở thành một mặt hàng cần thiết. Hầu hết các gia đình ngày nay có thể sẽ có một bộ định tuyến được cài đặt. Nhưng với sự thay đổi của chúng tôi đối với một thế giới hoàn toàn không dây cũng có những vấn đề cụ thể. Đối với một, các bộ định tuyến không dây vẫn dễ bị các vấn đề phạm vi tín hiệu. 

Những ngôi nhà có nhiều phòng và tường sẽ khiến tín hiệu bộ định tuyến giảm đáng kể. Vì vậy, bạn có thể làm gì để tránh những vấn đề như vậy? Khác với việc mua một bộ định tuyến mạnh hơn, có thể tốn vài trăm đô la, bạn cũng có thể sử dụng bộ định tuyến cũ của mình làm bộ mở rộng phạm vi. 



Trong bài viết này, chúng tôi sẽ thực hiện các bước về cách bạn có thể chuyển đổi bộ định tuyến cũ thành bộ tăng cường tín hiệu WiFi để cải thiện phạm vi của bộ định tuyến. 



Trước khi chúng tôi bắt đầu, tôi muốn nhấn mạnh rằng đây không phải là một giải pháp hoàn hảo cho tín hiệu WiFi yếu. Hãy nghĩ về nó như là một sự thay thế hiệu quả về chi phí sẽ làm những gì cần thiết cho thời điểm hiện tại. Đây cũng là một giải pháp khá thiết thực. Bây giờ, chúng ta hãy bắt đầu chuyển đổi bộ định tuyến cũ của bạn trong bộ tăng cường phạm vi WiFi, phải không?



## Bước 1: Kiểm tra xem bộ định tuyến cũ của bạn có tương thích với công việc không 



Điều đầu tiên, bạn phải kiểm tra xem bộ định tuyến cũ của bạn có thể được chuyển đổi thành bộ lặp / mở rộng tín hiệu hay không. Nếu nó có thể được sử dụng như một bộ mở rộng tín hiệu, thì đó là một tin tuyệt vời, nhưng nó không có gì? 



Đừng lo lắng vì có một cách có thể khắc phục vấn đề này. 



Tuy nhiên, tôi nên cảnh báo bạn về các bộ định tuyến thế hệ của gout (802.11b) vì chúng không lý tưởng để trở thành bộ mở rộng. Do băng thông hạn chế, việc sử dụng phiên bản bộ định tuyến này sẽ khiến tốc độ internet của bạn bị tắc nghẽn, sau đó sẽ biểu hiện ở sự chậm chạp đáng chú ý. Để tránh vấn đề này, chỉ sử dụng các bộ định tuyến từ thế hệ 802.11n trở lên.

Trong trường hợp bộ định tuyến của bạn không có khả năng mặc định để chạy như một bộ lặp, bạn có thể kiểm tra xem nó có hỗ trợ phần sụn tùy chỉnh như DD-WRT không. Nếu có thể, thì có khả năng cao bạn có thể chuyển đổi bộ định tuyến cũ thành bộ mở rộng.



## Bước 2: Thiết lập bộ định tuyến cũ của bạn



Bây giờ, chúng ta cần bắt đầu cấu hình của bộ định tuyến cũ. Đơn hàng đầu tiên của doanh nghiệp là cập nhật firmware DD-WRT lên phiên bản mới nhất. Kiểm tra trang web chính thức của DD-WRT để tìm phiên bản tương thích cho bộ định tuyến của bạn, tải xuống và cài đặt chương trình cơ sở tùy chỉnh phù hợp. 



Khi hoàn tất, đăng nhập vào giao diện web của bộ định tuyến của bạn.



 URL sẽ phụ thuộc vào bộ định tuyến bạn có, nhưng hầu hết sẽ sử dụng địa chỉ 192.168.1.1. Thông tin đăng nhập rất có thể sẽ trở về mặc định. Kiểm tra trực tuyến thông tin đăng nhập mặc định của mô hình bộ định tuyến của bạn hoặc kiểm tra nhãn trên thiết bị để biết thông tin cần thiết. Sau khi đăng nhập, hãy đảm bảo cập nhật tên người dùng và mật khẩu của bạn thành thứ gì đó mạnh mẽ hơn. 

Đối với những người đã quên tên người dùng và mật khẩu cũ, bạn có thể đặt lại bộ định tuyến về cài đặt gốc của nó. Điều này có thể được thực hiện bằng cách nhấn và giữ nút lõm (lỗ nhỏ có kích thước pin trên thiết bị) trong 20 đến 30 giây. 



Trong màn hình cấu hình, nhấp vào menu Không dây và mở phần Cài đặt nâng cao và Lặp lại không dây. Bắt đầu với menu phụ 2.4GHz và kiểm tra kỹ xem liệu tên người dùng và mật khẩu có khớp với mạng chính của bạn không. Khi bạn chắc chắn mọi thứ đều theo thứ tự, hãy nhấp vào Bật chức năng lặp lại không dây và sau đó là Bộ lặp không dây. 

## Bước 3: Nhập địa chỉ tĩnh



Bước này sẽ phức tạp hơn một chút. Việc chọn địa chỉ tĩnh cho bộ tăng cường phạm vi nên được xử lý cẩn thận. Tôi lấy địa chỉ của bộ định tuyến chính và thay đổi chữ số cuối cùng bằng cách thêm một. Điều này sẽ giúp bạn phân biệt rằng địa chỉ tĩnh này là một phần của cùng cấu trúc mạng LAN. Bạn cũng nên tạo thói quen viết ra tất cả các địa chỉ tĩnh bạn sử dụng để tránh nhầm lẫn trong tương lai. 

Bây giờ, bạn cần đặt mặt nạ mạng con. Cái này khá đơn giản vì bạn cần sao chép mặt nạ mạng con mặc định mà bạn có thể tìm thấy trên cùng màn hình với địa chỉ IP cơ sở của bạn. Nếu bạn không biết mặt nạ mạng con là gì, nó thường trông như thế này: 255.255.255.0. Chỉ cần sao chép này vào bộ định tuyến tăng cường phạm vi. 



Trước khi thoát, hãy đảm bảo rằng hộp cho cài đặt Vô hiệu hóa Hiệp hội khách hàng không dây được bỏ chọn. Nhập địa chỉ MAC của bộ định tuyến cơ sở mà bạn thường có thể tìm thấy trên nhãn của bộ định tuyến hoặc trong hướng dẫn.



Lưu ý: Các bước tương tự cũng áp dụng cho bộ định tuyến băng tần kép 5GHz.



## Bước 4: Thực hiện chạy thử bộ mở rộng bộ định tuyến của bạn



Bây giờ bạn đã cấu hình bộ định tuyến và chuyển đổi nó thành một bộ mở rộng, đã đến lúc kiểm tra nó. Chọn một khu vực mà bạn cho là có tín hiệu WiFi yếu nhất trong nơi cư trú của bạn và cắm bộ mở rộng bộ định tuyến ở đó. 



Mang theo điện thoại thông minh của bạn và bật bộ mở rộng WiFi mới (cũ?). Hãy thử truy cập trực tuyến và chạy Speedtest.net để xem mọi thứ có hấp dẫn với băng thông không. Đừng nản lòng nếu bạn nhận được kết quả khủng khiếp với bài kiểm tra tốc độ. Sẽ mất một chút thời gian để tìm ra điểm ngọt ngào của người dùng cho người mở rộng của bạn, nhưng bạn sẽ đến đó. Ngoài ra, bạn có thể muốn chuẩn bị một dây mở rộng cho bước này. 

## Phần kết luận

Hãy nhớ rằng không phải tất cả các bộ định tuyến đều được thực hiện như nhau. Hướng dẫn từng bước này sử dụng bộ định tuyến Netgear và với tính năng Netgear Genie, việc chuyển đổi thành một bộ mở rộng khá dễ dàng và đơn giản. Tuy nhiên, các bước chúng tôi chỉ ra ở đây có khá nhiều quy trình chung bạn sẽ thực hiện cho nhiệm vụ này. 



Giờ đây, bạn đã tăng đáng kể phạm vi của bộ định tuyến không dây, hãy tận hưởng trình duyệt internet không ngừng cho dù bạn đang ở nhà.
