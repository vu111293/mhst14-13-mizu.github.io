---
layout: post
author: khoaipx
title: Meeting Minutes 6
category: Conference
tags: [meeting]
---
**Thời gian**: Chủ nhật, ngày 15/06/2014 - 19h30 – 20h35

**Thành phần tham dự**: anh Quân, Khoái, Nam, Hùng, Huy

**Địa điểm**: Qua Skype

<!-- more -->

**Mục đích**:

* Báo cáo quá trình họp tập, training trong 2 tuần qua.

* Lên kế hoạch cho tuần tiếp theo: 

  - Thảo luận về các bài tập training trong tuần này 

  - Thảo luận về sản phẩm: Quá trình đồng bộ hóa

  - Tổng hợp các tài liệu training



**Nội dung cuộc họp**:

* Báo cáo quá trình học tập, training:

  - Python:

    + Khoái: Đang học python, code được một số chương trình nhỏ, đã hoàn thành bài tập làm một mini-calculator với 2 phép tính cộng trừ.

    + Huy: Đang tìm hiểu về python, đã từng học một chút khi tham gia website [brilliant](http://brilliant.org)

    + Hùng: Đang tìm hiểu về python

  - Ubutu:

    Cả nhóm đã cài đặt Ubutu 14.04

  - Github:
    + Cả nhóm đã tham gia một buổi training về git và github do anh Nam đứng lớp. Đã có thể tạo một repository demo để thực hành:
      
      [Thực hành của Khoái](https://github.com/khoaipx/15-06-guide)

      [Thực hành của Huy](https://github.com/Khuchuuhuy/15-06-guide)

    + Sẽ có tiếp một buổi training nữa vào tối thứ Hai, ngày 16/06/2014.

  - Lên kế hoạch tuần sau:

    + Trong tuần này, tiếp tục quá trình training với các bài tập do mentors đưa ra, bắt đầu suy nghĩ cụ thể hơn về các vấn đề của sản phẩm

    + Thảo luận về các bài tập đặt ra:

      Phát triển tiếp calculator với phép nhân, phép chia, xử lý dấu ngoặc. Bài tập này được giao cho Hùng.

    + Bài tập Scan ảnh:

      - Viết 1 script để quét các file JPG trong đó, và sắp xếp vào các thư mục con, nhóm theo ngày tháng chụp ảnh, đồng thời đổi đuôi file từ chữ hoa sang chữ thường.

      - Chương trình chạy phải nhận tham số như sau:

        + Nếu không có tham số, thì xử lý trên thư mục chứa script.

        + Tham số thứ nhất là thư mục chứa ảnh gốc, tham số thứ 2 là thư mục đầu ra. Nếu không có tham số thứ 2 thì thư mục đầu ra cùng là thư mục đầu vào, của tham số 1.

      Ví dụ: có file Photos/DSC0001.JPG chụp ngày 3/4/2014 thì sẽ đưa nó vào Photos/2014/04/03/DSC0001.jpg

  + Bài tập tìm kiếm số điện thoại:

      Cho 1 thư mục chứa đầy các file vCard (danh bạ điện thoại), trong đó có thể có những vCard chứa trùng số điện thoại. Viết script để lục tìm số điện thoại trùng và liệt kê ra file trùng.

      Ví dụ:

```
+8490902244:

     Doraemon.vcf

     Doremini.vcf

+8498989833:

     Xuka.vcf

     Shizuka.vcf

     Shizuka(1).vcf
```

  - Thảo luận về vấn đề Đồng bộ hóa của sản phẩm:

      + Mô hình gợi ý được đưa ra là U1BD

      + Cần lưu ý các vấn đề:

        - Hiểu những hành động xảy ra trong quá trình đồng bộ hóa

        - Trao đổi dữ liệu như thế nào giữa SQLite và SQL trên server, những thông tin gì cần được trao đổi.

  - Tổng hợp các tài liệu tham khảo trong quá trình training:

      [Dive into Python](http://www.diveintopython.net/toc/index.html)

      [Python guide](http://docs.python-guide.org/en/latest/)

      [Python 2.7 tutorial](https://docs.python.org/2.7/tutorial/index.html)

      [Python 2.7 library](https://docs.python.org/2.7/library/index.html)

      [Python 2.7 HOWTO](https://docs.python.org/2.7/howto/index.html)

      [Python regular expession](http://www.pyregex.com/)
