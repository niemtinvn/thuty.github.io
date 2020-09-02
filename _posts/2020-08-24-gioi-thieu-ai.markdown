---
layout: post
title:  "Giới thiệu về AI!"
date:   2020-08-24 16:40:32 +0700
permalink: gioi-thieu-ai
categories: AI
---
# Giới thiệu sơ lược về AI (Artificial Intelligence)

## 1. AI là gì?
Một vài ứng dụng AI: Xe tự hành của Google và Tesla, hệ thống tự tag khuôn mặt trong ảnh của Facebook, trợ lý ảo Siri của Apple, hệ thống gợi ý sản phẩm của Amazon, hệ thống gợi ý phim của Netflix, máy chơi cờ vây AlphaGo của Google DeepMind, …

Làm rõ 3 khái niệm AI, ML, DL mà hiện tại đang hot.
Trong khoa học máy tính: trí tuệ nhân tạo (AI) hiểu là trí thông minh được thực hiện bằng máy móc. ===> khá mơ hồ

Định nghĩa theo 4 hướng tiếp cận chính:
1. Hành động như người.
2. Suy nghĩ như người.
3. Suy nghĩ hợp lý.
4. Hành động hợp lý.

Trong đó hành đồng va suy nghĩ như người là khó hơn và cũng là mục tiêu khoa học hướng tới.

Machine Learning (ML) là một lĩnh vực của trí tuệ nhân tạo: cho phép các hệ thống "học"được từ dữ liệu để giải quyết các vấn đề cụ thể (1 cách thức để hướng tới AI)

Định nghĩa theo khoa học: "Một chương trình máy tính CT được xem là học cách thực thi một lớp nhiệm vụ NV thông qua trải nghiệm KN, đối với thang đo năng lực NL nếu như dùng NL ta đo thấy năng lực thực thi của chương trình có tiến bộ sau khi trải qua KN"" -- Tom Mitchell

==> ML là 1 phương tiện để đạt được AI

DL là 1 phương pháp (thuật toán) trong ML. Nhưng quan trọng gần đây nó phát triển rất mạnh

## 2. Lịch sử AI, ML, DL
### 50s
Nghiên cứu “Computing Machinery and Intelligence” (Máy tính và Trí thông minh), được xuất bản năm 1950 bởi Alan Turing đã đưa ra một câu hỏi mà cho tới hiện tại vẫn chưa được giải đáp: “Liệu máy móc có thể suy nghĩ?”
### Perceptron (60s)
Một trong những nền móng đầu tiên của deep learning là perceptron learning algorithm. Perceptron là một thuật toán supervised learning giúp giải quyết bài toán phân lớp nhị phân, được khởi nguồn bởi Frank Rosenblatt năm 1957. Thuật toán perceptron được chứng minh là hội tụ nếu hai lớp dữ liệu là **linearly separable** ==> kỳ vọng “có thể đi, nói chuyện, nhìn, viết, tự sinh sản, và tự nhận thức được sự tồn tại của mình”

Nhưng nhanh chóng chứng minh không thể giải quyết được các bài toàn đơn giản: Năm 1969, Marvin Minsky và Seymour Papert trong cuốn sách nổi tiếng Perceptrons đã chứng minh rằng không thể ‘học’ được hàm số XOR khi sử dụng perceptron. Phát hiện này làm choáng váng giới khoa học thời gian đó, Perceptron được chứng minh rằng chỉ hoạt động nếu dữ liệu là linearly separable.

Phát hiện này khiến cho các nghiên cứu về perceptron bị gián đoạn gần 20 năm. Thời kỳ này còn được gọi là **Mùa đông AI thứ nhất (The First AI winter).**

Cho tới khi…
### MLP và Backpropagation ra đời (80s)
1986 Trong bài báo này, nhóm của [Geoffrey Hinton](https://en.wikipedia.org/wiki/Geoffrey_Hinton) chứng minh rằng neural nets với nhiều hidden layer (được gọi là multi-layer perceptron hoặc MLP) có thể được huấn luyện một cách hiệu quả dựa trên một quy trình đơn giản được gọi là backpropagation ===> giải quyết được hạn chế lớn nhấ của perceptron là có thể xử lý các mối quan hệ phi tuyến.

Ra đời các thuật toán như CNN nhận dạng chữ số viết tay của Yann LeCun.
### Mùa đông AI thứ hai (90s - đầu 2000s)
1. Để giải quyết được các bài toán _image classifiction_ thì cần nhiều dữ liệu được gán nhãn.
2. Thường dùng hàm sigmoid hoặc tanh bị chăn trong khoảng (1,1) ==> đạo hàm nhỏ ==> tích nhiều số nhỏ xấp xỉ 0 (backpropagation) ==> không thể cập nhật được thông qua gradient descent!

==> bế tắc
### Bùng nổ
1. Xuất hiện big data do sự bùng nổ của internet.
2. Thuật toán sử dụng được hiệu năng tính toán của GPU

Deep Blue đánh bại Garry Kasparov bằng sự trâu bò tính toán của hệ thống nhưng AlphaGo đánh bại Lee Sedol là áp dụng 1 thuật toán mới AlphaGo tự chơi với nó để tự học và suy nghĩ như người

[https://dlapplications.github.io/2018-06-27-Brief-History-of-Deep-learning/](https://dlapplications.github.io/2018-06-27-Brief-History-of-Deep-learning/)