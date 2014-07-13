---
layout: post
author: Pham Xuan Khoai
title: Meeting Minutes 6
category: Conference
tags: [meeting]
---
**Thời gian:** Thứ 7, ngày 12/07/2014 - 16h15 – 18h00 (GMT +7)

**Thành phần tham dự:** anh Hưng, Khoái, Huy

**Địa điểm:** Fixx Cafe

<!-- more -->

**Mục đích:**

* Lên kế hoạch cho thời gian tiếp theo:

  - Phương hướng làm việc

  - Gợi ý cho sản phẩm

  - Đưa ra các bài tập gần với sản phẩm dự án

**Nội dung cuộc họp:**

* Phương hướng làm việc:

  - Nhóm kết thúc quá trình training về github, python, …

  - Thời gian còn lại là khoảng 2 tháng. Nhóm chuyển sang giai đoạn làm sản phẩm, trong quá trình này sẽ có thêm các bài tập sát với sản phẩm để bổ sung thêm kỹ năng, kiến thức.

* Gợi ý cho sản phẩm từ phía anh Hưng:

  - Sử dụng SQLite để quản lý các version được lưu trên máy. (Áp dụng mô hình U1DB mà anh Quân đưa ra.)

    ![U1DB](/assets/images/U1DB.jpg)

  - Trong 1 vài tuần tới, tập trung làm về phía mảng máy local gồm app Zim + SQLite.

  - Một số usecases cần lưu tâm:

    + Tạo một page mới ở Zim, ấn Ctrl+S, sẽ lưu lại vào database một record gồm các trường: ID, Thời gian, Trạng thái, coi như lưu lại 1 version.

    + Có 2 máy. Một máy edit một page của Zim và lưu lại. Một máy khác ấn Sync để lấy version mới nhất về máy.

      ![Sync](/assets/images/Sync.jpg)

  - Một số vấn đề cần thảo luận:

    + Nếu các page Zim không hỗ trợ mã wiki, sẽ diff như thế nào?

    + Khi diff các versions sẽ hiển thị bằng khác biệt code wiki hay hiển thị trực quan side-by-side(ví dụ font to/nhỏ, bôi đậm hay không, …)

    + Đồng bộ hóa thủ công hay tự động? Để cài đặt mặc định như thế nào? (Mặc định để đồng bộ hóa tự động hay không)

    + Lưu trữ nội dung các version như thể nào? Toàn bộ hay chỉ lưu sự thay đổi.

  - Một số kiến thức cần bổ sung:

    + Học thêm về database

    + Học thêm về sequence diagram. Tool: Astah.

* Các bài tập mới:

  - So sánh hai file plain text.

  - Thực hành SQLite, thiết kết một bảng có các trường ID(tự động tăng), Timestamp, Status, Content. Tool gợi ý: navicat

  - Lập trình python để diff trường n và trường n+1 trong 1 database SQLite

  - Lập trình python để thêm, xóa, sửa các bảng lưu trong 1 database SQLite

  - Sửa Zim có khả năng nhận tổ hợp Ctrl+S là Lưu lại.

* Một số lưu ý khác:

  - Khi có câu hỏi, thắc mắc, gửi email trực tiếp hỏi mentors.

  - Đề nghị các thành viên cài teamviewer để trong trường hợp gặp trục trặc nếu qua miêu tả không giải quyết được, thì sử dụng teamviewer.

  - Đặt tên file bỏ các thông tin không cần thiết như: Ngày, tháng, năm, tên người nộp.

  - Show kết quả các bài tập ở phần comment phía dưới của các issue.
