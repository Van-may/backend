---
title: Cài đặt HMG Themes Hexo chạy trên GitHub Pages
cover: 'https://ucarecdn.com/e9bb7e32-9450-4a8b-b468-5ccf8f8e1362/'
date: '2019-09-19'
editorial: publisher
authors:
  - 2019-2-tiep-staff
semester: 2019/1
tags:
  - Tools
  - Web
featured: false
headline: >-
  Để cài đặt Hexo làm blog chạy trực tiếp trên hosting miễn phí Github thì chúng
  ta cần phải đảm bảo một vài yếu tố dưới đây trước.
---
Phần mềm blog [Hexo](https://hexo.io/).

Tài liệu [documentation](https://hexo.io/docs/).

Nếu có lỗi, tham khảo các vấn đề chính [troubleshooting](https://hexo.io/docs/troubleshooting.html) hoặc viết các nội dung thông tin trên [GitHub](https://github.com/hexojs/hexo/issues).

## Các công cụ chính Thảo Am cần

**Cài đặt Install Git**

Windows: Download & install Git. + Node.js

Đối với Windows bạn **nên chọn phiên bản install cho phù hợp** và dễ thao tác nhanh hơn là tải source phần mềm trên về.

Mac: Install it with [Homebrew](http://mxcl.github.com/homebrew/), [MacPorts](http://www.macports.org/) or [installer](http://sourceforge.net/projects/git-osx-installer/).

Linux (Ubuntu, Debian):

```
sudo apt-get install git-core
```

Linux (Fedora, Red Hat, CentOS):

```
sudo yum install git-core
```

**Trường hợp đặc biệt**

Bạn có thể cài đặt **Install Node.js** bằng cách mới không cần cài đặt đó là sử dụng [Node Version Manager](https://github.com/creationix/nvm).

Dù sao đối với những bạn không chuyên về phần mềm nên chọn bản Installer thì hơn, còn đối với người chuyên thì dùng NVM sẽ tốt hơn.

Chọn **1 trong 2 cách** sau nhé bạn:

cURL:

```
$ curl -o- https://raw.githubusercontent.com/creationix/nvm/v0.33.2/install.sh | bash
```



Wget

```
$ wget -qO- https://raw.githubusercontent.com/creationix/nvm/v0.33.2/install.sh | bash
```



Khi mà **NVM** cài đặt xong, khởi động lại tác vụ và chạy dòng lệnh (sử dụng **CMD.exe** nhé) sau để bắt đầu cài đặt Node.js

Lưu ý là **chỉ chọn 1 trong 2 cách sau** đây nhé:



Cách 1



```
nvm install 4
```



Cách 2

```
nvm install stable
```

Cài đặt xong xuôi các hướng dẫn nêu trên, **đồng nghĩa với việc máy tính bạn đã sẵn sàng** để tiến đến bước kế tiếp.

Tuy hơi phức tạp tí nhưng mà Hexo nó đáp ứng tốt nhiều nhu cầu, đảm bảo tốt nhiều công việc và hiệu quả nhất là túi tiền. Những ưu điểm và nhược điểm thì các bạn kéo xuống dưới xem đánh giá nhé.

## Cài Đặt Hexo (Install Hexo)

Mở **CMD** lên, nếu máy tính bạn chỉ có ổ C thôi thì thao tác luôn dòng lệnh này Gõ luôn dòng lệnh này vào CMD nhé.

Nếu có nhiều hơn 1 ổ đĩa, ví dụ: D: ; E: ; F: ; … vân vân thì bạm gõ D: hoặc E: hoặc F: tùy tên tương ứng ổ đĩa để CMD nhảy sang ổ đĩa đó. Bằng các dòng lệnh này mkdir Tên_thư_mục hoặc md Tên_thư_mục chọn 1 trong 2 cách thôi nhé, sau đó cd Tên_thư_mục để vào thư mục đã tạo trước khi bắt đầu bằng dòng lệnh dưới và máy cài Hexo vào đó.



```
npm install -g hexo-cli
```

Sau khi đã hoàn tất việc tải về Hexo trên, bạn tiếp tục bước cài đặt Hexo vào thư mục nào đó trên đĩa.



Cài đặt Hexo vào thư mục cài đặt _<folder>_ ở đây có tên bất kỳ do bạn đặt, ví dụ Thảo Am cài đặt Hexo trên ổ đĩa D:, và thư mục cài là TABlogSystems, vậy là ta suy ra ngay Thảo Am đã thay _<folder>_ bằng TABlogSystems,.



```
hexo init <folder>
```

```
cd <folder>
```

```
npm install
```

Hoàn tất việc cài đặt các bạn vào thư mục vừa xuất Hexo ra đó kiểm tra xem cấu trúc có giống thế này không là được.

.

```
├── _config.yml
```

```
├── package.json
```

```
├── scaffolds
```

```
├── source
```

```
|   ├── _drafts
```

```
|   └── _posts
```

```
└── themes
```

## Chạy thử để kiểm tra Hexo đã chạy

Vẫn tại CMD bạn chạy dòng lệnh này.

```
$ hexo server
```



Tiếp đến thì bạn gõ cái địa chỉ liên kết này vào trình duyệt để Test thử Hexo mặc định chạy chưa: http://localhost:4000

## Cài đặt theme HMG của Thảo Am

Các bạn xuantiep.pham@gmail.com liên hệ email này để lấy Themes đã Nâng cấp mới nhé.

Hoặc comment bên dưới Email của bạn để nhận theme.



Sau khi có tập tin nén .zip của theme mới nhất, các bạn giải nén và copy vào thư mục themes của Hexo.

Bạn có thể đổi tên của thư mục theme vừa tải về, vấn đề là phải chính sửa cho khớp ở _config.yml của Hexo

đảm bảo file _config.yml có dòng này nhé _theme: tên_thư_mục_theme_



More info: [Generating](https://hexo.io/docs/generating.html)

Kích hoạt Theme

Chạy dòng lệnh dưới vào CMD để cài đặt prismjs vào Hexo để kiểm soát lỗi.



```
npm install prismjs --save
```



Sau đó, kiểm tra file _config.yml của Hexo nó phải đáp ứng điều kiện này



```
  enable: false
```

Chạy dòng lệnh _hexo s --debug_ vào CMD, rồi mở tiếp http://localhost:4000 để kiểm tra xem có lỗi không.

Nếu có lỗi thì bạn thành công rồi, bởi vì Theme này cần thêm ứng dụng để chạy hoàn chỉnh vì thế đừng lo nghĩ gì cả, cứ tiếp tục các bước dưới đây.

## Khởi tạo các Plugin đi kèm

Cài đặt Search

Bạn cài đặt **hexo-generator-search** để Theme kích hoạt chức năng tìm kiếm nhanh. Gõ dòng lệnh sau:



```
npm install hexo-generator-search --save
```



**Cài đặt Comment Disqus**

Bạn mở file _config.yml trong Themes ra.



```
comment:
```

```
    use: disqus
```

```
    shortname: ten_user_cua_ban
```

Nhớ, thay ten_user_cua_ban bằng user bạn đăng ký ở Disqus.

## Cài đặt RSS

ở trong CMD bạn gõ dòng lệnh sau để cài hexo-generator-feed giúp tạo RSS cho Hexo.



```
npm install hexo-generator-feed --save
```



Muốn tìm hiểu thêm thì vào link này https://github.com/hexojs/hexo-generator-feed

**Cài đặt QR_CODE**

QR Code dành cho cả trang lẫn bài viết, Có 2 lựa chọn true và false, cần cài hexo-helper-qrcode plugin để sử dụng chức năng này.

Chạy dòng lệnh này ở CMD trong thư mục Hexo



```
npm install hexo-helper-qrcode --save
```

## Đẩy lên GitHub Page

**Cài đặt**

Mở file _config.yml trong Hexo.

Chú ý: {your github repo url} chính là đường dẫn Repo mà bạn tạo ở GitGub, ví dụ https://github.com/abcxyz/abcxyz.github.io

Trong đó abcxyz là user của bạn ở GitHub. Còn abcxyz.github.io chính là user của bạn + với github.io



thêm dòng lệnh này vào file _config.yml của Hexo nhé.



```
deploy:
```

```
  type: git
```

```
  repo: {your github repo url}
```

```
  branch: master
```

```
  message: "Site updated: {{ now('YYYY-MM-DD HH:mm:ss') }}"
```

Deploy

Chạy 2 dòng lệnh này trong CMD



```
npm i -S hexo-deployer-git
```

```
hexo deploy
```



Đến bước này rồi thì Blog của bạn đã host miễn phí ở Github rồi theo địa chỉ tương tự abcxyz.github.io bạn đã tạo.
