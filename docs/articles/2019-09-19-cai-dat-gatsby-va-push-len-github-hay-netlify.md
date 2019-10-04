---
title: Cài đặt Gatsby và Push lên GitHub hay Netlify
cover: 'https://ucarecdn.com/de3b813b-c4f7-4297-a053-d72323245430/'
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
  Blazing fast React.js static site generator. Tương đối phức tạp hơn so với
  Hexo.
---
**Gatsby là gì?**

Gatsby là loại công nghệ web mới nhất. với nền tảng **React.js** tốc độ cao, tạo ra content tĩnh.



Hỗ trợ viết **pages & post** bằng định dạng Markdown, HTML, và React.js xử lý các tác vụ. Dễ dàng tạo ra những bản file types hỗ trợ khác nhau.



## Thành tựu mà Gatsby đạt được

> No-reload page transitions
>
> Hot reload editing. Tweak your pages, templates, and styles and see changes in real time.
>
> Make React.js component model and ecosystem available for building static sites
>
> Intuitive directory-based URLs. The URL of a page is derived from its spot on the file system.
>
> Support “Starters” — install starter sites directly from Github. Use open sourced starters or build your own.

## Vì sao dùng Gatsby thay cho những Open source tạo content tĩnh khác?

> No-refresh page transitions
>
> The awesome React.js component model
>
> Live editing on every part of your site. Dramatically speed development.

## Getting started

**Install**

Cài đặt Gatsby vào trong hệ thống máy khi đã có Node.js

```
npm install -g gatsby
```



**Tạo với Source mặc định**

1. Create new Gatsby site gatsby new my-test-gatsby-site This creates the directory for your Gatsby project and adds the minimal files needed.
2. cd my-test-gatsby-site
3. gatsby develop — Gatsby will start a hot-reloading development server accessible at localhost:8000

See the tutorial below for more.

**Gatsby Starters**

The Gatsby CLI tool lets you install “starters”. These are partially built sites preconfigured to help you get moving faster on creating a certain type of site.



When creating a new site, you can optionally specify a starter to base your new site on e.g. _gatsby new \[SITE_DIRECTORY] \[URL_OF_STARTER]_



For example, to quickly create a blog using Gatsby, you could install the Gatsby Starter Blog by running:



```
gatsby new blog https://github.com/gatsbyjs/gatsby-starter-blog
```



This downloads the files and initializes the site by running npm install



If you don’t specify a custom starter, your site will be created from the default starter.



## Deploying to Github Pages (and other hosts where your site’s links need prefixes)

Gatsby supports automatically prefixing links with its _prefixLink_ helper function.



First set the prefix in your config file e.g. _linkPrefix = '/your-project'_



Then simply import the function and run all links in your site through it e.g.



```
import { prefixLink } from 'gatsby-helpers'
```

```
prefixLink('/')
```

```
// During development this will return "/"
```

```
// When deployed to example.github.io/your-project/ this will return "/your-project/"
```

Then finally, when building your site, run _gatsby build --prefix-links_



The built site is now in _/public_. These files need copied to your _gh-pages_ branch and committed and pushed. You can do this manually or use the handy _gh-pages_ CLI tool.



Both the sample sites are deployed to github pages and use link prefixing. Read their source for more help: [documentation](https://github.com/gatsbyjs/gatsby-starter-documentation)/[blog](https://github.com/gatsbyjs/gatsby-starter-blog).



## Kinh nghiệm Thảo Am

Tạo repository ở Github. tránh gặp lỗi, tốt nhất chả nên tạo README, license hay gitignore. Thêm những file này sau khi project đẩy lên github thành công



Mở Terminal (dành cho máy Mac) hoặc **CMD** command prompt (Windows và Linux).



**Cài đặt**

```
npm install -g gatsby
```

Tạo thư mục chứa source



```
cd ~/PATH/TO/thu_muc_chua_gatsby/
```

Initialize the local directory as a Git repository.



```
git init
```

Add the files in your new local repository. This stages them for the first commit.



```
git add .
```

Commit the files that you’ve staged in your local repository.



```
git commit -m "first commit"
```

At the top of your GitHub repository’s Quick Setup page, click the clipboard icon to copy the remote repository URL.



In Terminal, add the URL for the remote repository where your local repository will be pushed.



```
git remote add origin Git_Repository_URL
```

Verify your URL



```
git remote -v
```

The build log is complaining that gatsby is not installed, so make sure to add gatsby to your package.json as a dependency.



Simplest way is to run:



```
npm install gatsby --save
```

Locally and then add the updated package.json to your repository. That way netlify will know to install gatsby before running your build command.



Now, it’s time to push the changes in your local repository to GitHub.



```
git push -u origin master
```

## Nếu gặp lỗi, sử dụng dòng lệnh này để thay thế

Cần phải Commit trước khi Đẩy lên GitHub



```
mkdir repo && cd repo
```

```
git remote add origin /path/to/origin.git
```

```
git add .
```



Ví dụ khi chưa Commit!



```
git push -u origin master
```



Lỗi kiểu này



_error: src refspec master does not match any._

Cuối cùng:



```
git commit -m "initial commit"
```

```
git push origin master
```



Success!
