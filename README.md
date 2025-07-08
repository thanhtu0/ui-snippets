# UI Snippets Library

📁 Một bộ sưu tập các component HTML/CSS nhỏ như card, button, navigation bar...

## Danh mục

-   cards/
-   buttons/
-   navbars/
-   hover-effects/

## Cách dùng

Mỗi file HTML đều chạy độc lập, bạn có thể mở trực tiếp bằng trình duyệt.

## 6 khả năng HTML manh mẽ

1.Check the spelling (Kiểm tra chính tả) -> Thuộc tính HTML 'spellcheck' kiểm tra lỗi chính tả.
<input type="text" spellcheck="true" />

2.Download file -> Thuộc tính download sẽ cho phép bạn tải xuống tệp được chỉ định trong thuộc tín href khi người dùng nhấp vào siêu liên kết.
<a download href="/your_url/here">DOWNLOAD</a>

3.Video thumbnail -> Thuộc tính "poster" chỉ định hình ảnh được hiển thị khi video đang tải xuống cho đến khi người dùng nhất nút phát. Giống như hình thủ nhỏ của YouTube.
<video poster="/images.jpg" width="640" height="480">

4.Translate -> Đặt giá trị của nó thành "không" cho tên công ty. Vì vậy, trong TH trang web được dịch sang ngôn ngữ khác, tên thương hiệu vẫn giữ nguyên.

 <footer>
     <p translate="no">Company Name</p>
 </footer>

5.Autocomplete input file -> Thuộc tính "Autocomplete" chỉ định xem một biểu mẫu hoặc input field có nên bật hay tắt tự động hoàn thành hay không.
<input type="text" autocomplete="on" />

6.Multiple files -> Sử dụng thuộc tính "multiple" của phần tử đầu vào, người dùng được phép nhập nhiều giá trị vào trường đầu vào. Nó chỉ hợp lệ cho loại "email" và "file".
<input type="email" multiple>

### Mẹo tăng tốc độ viết HTMl

1.Elements: div>ul>li
2.Siblings: div+p+bq
3.Climb up: div+div>p>span+em^bq
4.Multiplication: ul>li*2
5.Grouping: div>(header>ul>li*2)
6.Id&Class: div#header+div.page
7.Custom attributes: td[title="Hello world!"]
8.Item numbering: ul>li.item$*2
