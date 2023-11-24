---
title: "Chương 1: Quy mô từ 0 tới hàng triệu người dùng"
date: 2023-11-22 11:43:00 +0700
categories: [system design]
tags: [system design]
---
# Thiết kế hệ thống hỗ trợ hàng triệu người dùng là một thách thức, đó là một hành trình yêu cầu sự sàng lọc liên tục và cải tiến không ngừng. Trong chương này, chúng ta sẽ xây dựng một hệ thống hỗ trợ một người dùng duy nhất và sau đó dần dần mở rộng quy mô nó lên để phục vụ hàng triệu người dùng. Sau khi đọc chương này, bạn sẽ thành thạo một số kỹ thuật nó sẽ giúp bạn giải quyết các câu hỏi phỏng vấn về thiết kế hệ thống

## Thiết lập máy chủ đơn

Hành trình ngàn dặm được bắt đầu từ bước chân đầu tiên, và xây dựng một hệ thống phức tạp cũng không khác gì. Để bắt đầu với những gì đơn giản, mọi thứ được chạy trên một máy chủ duy nhất. Hình 1-1 minh họa một thiết lập máy chủ duy nhất nơi mà mọi thứ chạy trên máy chủ duy nhất: web app, database, cache, v.v

![image info](/assets/img/favicons/figure1_1.png)
