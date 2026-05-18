---
nav_order: 1
title: Giới thiệu
---
Learn-Static Lesson Template là một dự án của Jekyll để tạo một trang web bài học hoặc hội thảo đơn giản, với chủ đề dựa trên [Bootstrap](https://getbootstrap.com/), được thiết kế để lưu trữ trên [GitHub Pages](https://pages.github.com/).

Nó có tính năng điều hướng thanh bên cung cấp cấu trúc rõ ràng cho nội dung từng bước. Điều hướng thanh bên hỗ trợ các trang lồng vào các phần để giúp sắp xếp nội dung bài học của bạn.

Tất cả nội dung được viết bằng Markdown cơ bản, giúp việc viết, chỉnh sửa và sử dụng lại tài liệu bài học trở nên đơn giản.

Để sử dụng Mẫu bài học để tạo trang web của riêng bạn - > tạo một bản sao và thay thế nội dung mẫu bằng nội dung của riêng bạn!


Learn-Static Lesson Template is a Jekyll project to create a simple lesson or workshop website, with a [Bootstrap](https://getbootstrap.com/)-based theme, designed for hosting on [GitHub Pages](https://pages.github.com/).

It features a sidebar navigation providing clear structure for step by step content.
The sidebar nav supports pages nested into sections to help organize your lesson content. 

All content is written using basic Markdown, making it simple to write, edit, and reuse lesson materials.

To use Lesson Template to create your own website--> make a copy and replace the template content with your own!

## Why?

Rather than making slides for a workshop, why not make a website? 
It's easier to write, access, share, and reuse. 
GitHub and GitHub Pages makes this relatively straightforward.

Writing content in this simple, reuseable format makes for a better [Open Educational Resource](https://en.wikipedia.org/wiki/Open_educational_resources) since anyone can make a copy and adapt!

## GitHub Pages 

One amazingly useful GitHub feature is [GitHub Pages](https://guides.github.com/features/pages/).
It provides free static web hosting from any repository.
Gh-pages is intended to host relatively simple sites for your GitHub portfolio, project, or documentation.
Because it is free and a valuable transferable skill, this is a great option for teaching and learning.

Many organizations are using GitHub to collaboratively create and publish public workshop websites. 
For example: 

- [Programming Historian](http://programminghistorian.org/)
- [Software Carpentry](https://software-carpentry.org/), [Data Carpentry](http://www.datacarpentry.org/), [Library Carpentry](https://librarycarpentry.org/)
- this site!

{% capture text %}Note:
There are *soft* limits and guidelines for gh-pages usage: sites should be < 1GB, use < 100GB bandwidth per month, and make < 10 builds per hour.
If your site exceeds these quotas, GitHub will send you a notice asking you to modify the repository.
All content must follow the [community guidelines](https://help.github.com/articles/github-community-guidelines/), e.g. no violence, obscene sex, or illegal stuff.{% endcapture %}
{% include alert.html text=text color=secondary %}
