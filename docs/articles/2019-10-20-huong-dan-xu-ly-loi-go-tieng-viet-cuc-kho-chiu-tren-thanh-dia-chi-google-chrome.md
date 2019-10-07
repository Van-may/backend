---
title: >-
  Hướng dẫn xử lý lỗi gõ tiếng việt cực khó chịu trên thanh địa chỉ google
  chrome
cover: 'https://ucarecdn.com/8aaceb68-8077-4a72-8e65-5adf48568699/'
date: '2019-10-20'
editorial: publisher
authors:
  - 2019-1-pham-xuan-tiep
semester: 2019/2
tags:
  - Đời sống
  - Bộ gõ tiếng việt
featured: false
headline: >-
  Một trong những phiền toái hầu như người dùng Unikey nào cũng gặp phải là lỗi
  gõ tiếng Việt trên thanh địa chỉ của Chrome.
---
Cụ thể, khi bạn gõ các ký tự như aa, dd, ee, oo,..., bạn sẽ nhận được aâ, dđ, eê, oô,… thay vì â, đ, ê, ô,... như thông thường. Trong bài viết hôm nay, chúng tôi sẽ hướng dẫn bạn cách sửa lỗi cực kỳ khó chịu này.

![](https://ucarecdn.com/7d4835c0-cd1b-4a38-a844-3d595cfe431c/)

Nguyên nhân

Lỗi này là do sự phối hợp không "ăn ý" giữa cơ chế bỏ dấu của Unikey và chức năng tự động gợi ý và hoàn thành (AutoComplete) của Google Chrome.

Đối với Unikey, khi bạn gõ các dấu thanh, dấu mũ và dấu móc bằng kiểu gõ Telex, phần mềm này sẽ thực hiện hai thao tác. Đầu tiên, nó sẽ xóa ký tự thứ nhất. Sau đó, nó mới đặt dấu cho ký tự còn lại. Ví dụ, khi bạn gõ aa, Unikey sẽ xóa ký tự a thứ nhất, sau đó nó đặt dấu mũ cho ký tự a còn lại, và bạn sẽ nhận được ký tự â.

Đối với Chrome, khi bạn gõ một từ khóa tìm kiếm bất kỳ trên thanh địa chỉ, trình duyệt này sẽ tự động kiểm tra lịch sử duyệt web của bạn để đưa ra các gợi ý và tự động điền phần còn lại của từ khóa.

Khi bạn gõ tiếng Việt bằng Unikey trên thanh địa chỉ của Chrome, những từ khóa bạn thường tìm kiếm sẽ được Chrome gợi ý, tự động điền và đồng thời bôi đen phần gợi ý. Quá trình này diễn ra song song với quá trình đặt dấu của Unikey. Và đây chính là nơi khởi nguồn của vấn đề.

Như đã nói ở trên, khi bạn gõ các dấu thanh, dấu mũ và dấu móc bằng kiểu gõ Telex, Unikey trước hết sẽ xóa ký tự thứ nhất và sau đó đặt dấu cho ký tự còn lại. Tuy nhiên, do quá trình đặt dấu diễn ra đồng thời với quá trình gợi ý và tự động điền của Chrome nên Unikey nhận nhầm ký tự đầu tiên là phần gợi ý được bôi đen của Chrome. Chính vì vậy, nó chỉ xóa phần bôi đen gợi ý thay vì xóa ký tự thứ nhất như thông thường.

Cách khắc phục

Như chúng tôi đã đề cập ở phần trên, lỗi gõ tiếng Việt trên thanh địa chỉ của Chrome là do sự phối hợp không "ăn ý" giữa cơ chế đặt dấu của Unikey và chức năng gợi ý để tự động điền của Google Chrome. Do vậy, để xử lý lỗi này, chúng ta có hai hướng, hoặc xử lý ở phía bộ gõ hoặc xử lý ở phía trình duyệt Chrome.

Cách 1: Xử lý ở phía trình duyệt Chrome

Tắt chức năng gợi ý và tự động điền của Chrome

Về phần Chrome, bạn chỉ cần tắt chức năng gợi ý và tự động điền của trình duyệt này. Cách thực hiện như sau:

\- Truy cập vào trình đơn của Chrome bằng cách nhấn nút hình ba dấu chấm ở phía trên, góc phải.

\- Chọn Settings (Cài đặt).

\- Nhấn nút Advanced (Nâng cao) nằm ở dưới cùng.

\- Trong phần Privacy and security (Quyền riêng tư và bảo mật), bạn chuyển công tắt tại mục Use a prediction service to help complete searches and URLs typed in the address bar (Sử dụng dịch vụ gợi ý để giúp hoàn thành các tìm kiếm và URL được nhập trong thanh địa chỉ) sang vị trí Off (Tắt) để vô hiệu hóa chức năng gợi ý và tự động điền trên thanh địa chỉ của Chrome.

![](https://ucarecdn.com/0a8ddfce-b1b5-442d-9721-9e2d3ef666b3/)

Lưu ý: Bởi vì dữ liệu gợi ý và tự động điền được lấy từ lịch sử tìm kiếm và duyệt web của bạn. Do vậy, nếu sau khi tắt chức năng gợi ý và tự động điền, lỗi vẫn còn, bạn chỉ cần xoá lịch sửa duyệt web bằng cách nhấn Ctrl + Shift + Delete và sau đó nhấn nút Clear Data (Xoá dữ liệu).

![]()

Sử dụng phím tắt tìm kiếm

Nếu bạn không muốn tắt gợi ý tìm kiếm, bạn vẫn có cách để gõ tiếng Việt trên thanh địa chỉ không bị lỗi là sử dụng phím tắt tìm kiếm.

Thông thường, khi cần tìm kiếm gì đó, bạn sẽ nhập từ khóa trực tiếp lên thanh địa chỉ. Tuy nhiên, với cách này, bạn sẽ gặp lỗi gõ tiếng Việt như đã nói ở trên. Để khắc phục, trước khi nhập từ khóa tìm kiếm, bạn chỉ cần nhấn phím Ctrl + K hoặc Ctrl + E để mở công cụ Google Search (Tìm kiếm Google), sau đó nhập từ khóa và nhấn Enter.

![](https://ucarecdn.com/386afb20-8ea8-45fb-8a5b-fa50cbef9871/)

Cách 2: Xử lý ở phía bộ gõ

Sử dụng bộ gõ tiếng Việt EVKey thay cho Unikey

Tính đến hiện tại, tác giả bộ gõ Unikey vẫn chưa đưa ra bất kỳ giải pháp nào để khắc phục vấn đề này. Do vậy, cách duy nhất để xử lý lỗi này ở phía bộ gõ là bạn phải sử dụng bộ gõ khác thay thế cho bộ gõ Unikey. Trên mạng hiện giờ có rất nhiều bộ gõ tiếng Việt. Tuy nhiên, để khắc phục lỗi này, bộ gõ EVKey là lựa chọn tốt nhất.

EVKey là chương trình gõ tiếng Việt do lập trình viên Lâm Quang Minh xây dựng dựa trên mã nguồn mở Unikey của tác giả Phạm Kim Long.

Bên cạnh giao diện mới, ứng dụng còn được sửa lại phần gửi phím từ Unikey tới ứng dụng, thêm chức năng loại trừ ứng dụng bạn không muốn nhập tiếng Việt, và đặc biệt là tích hợp sẵn khả năng sửa lỗi tiếng Việt trên thanh địa chỉ của trình duyệt web và gợi ý trên Excel.

![](https://ucarecdn.com/713a147e-903a-4d2c-a632-45dd796994d3/)
