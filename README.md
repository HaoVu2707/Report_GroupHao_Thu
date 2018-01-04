# Report_GroupHao_Thu
This is the report  our group
# 1.Cách sử dụng .gitignore
*.gitignore là gì ?*<br>
-Tình huống là: Bạn làm việc theo nhóm, bạn muốn sử dụng git để quản lý mã nguồn.Tuy nhiên, dự án của bạn sẽ sinh ra những file build, gen, config, local, password, properties.Những file này thường là sẽ tự sinh và sẽ khác nhau tuỳ từng máy, khi đưa lên git thì khi người khác lấy về sẽ sinh ra xung đột (conflict) => gây cản trở cho công việc của bạn. Ngoài ra thì những file này thường rất nặng => tốn băng thông và tốn thời gian pull/push.Để giải quyết vấn đề này, git đưa ra **.gitignore** file.<br>
-.gitignore là file định nghĩa những file, folder nào sẽ bị bỏ qua (ignore) và không thêm nó vào git. <br>
*Cách tạo file .gitignore*
-Đầu tiên mở terminal trong repository của bạn và gõ lệnh:<br>
**touch .gitignore** <br>
-Lúc này git sẽ tạo ra cho chúng ta 1 tệp tin là .gitignore,dùng notepad mở lên và khai báo các thư và mục tệp tin cần loại bỏ. 
Bạn có thể vào https://github.com/github/gitignore để tham khảo một số mẫu gitignore đã có sẵn của rất nhiều ngôn ngữ & framework (Chỉ việc copy về dùng, thay đổi nếu cảm thấy cần thiết).<br>
# 2.Cách sử dụng SourceTree
-Đầu tiên, bạn cần tải phần mềm Source Tree về cài đặt và đăng nhập vào để có thể sử dụng <br>
-Dưới đây là giao diện chính của Source Tree<br>
![](https://i.imgur.com/8qLgkTV.jpg)
**Kéo dự án về ( Clone project )**<br>
- Lên github để lấy địa chỉ của Responsitory về :<br>
![](https://i.imgur.com/j0s3pK6.jpg) <br><br>
 -Bạn click vào Clone/new một popup sẽ hiện ra , copy địa chỉ vừa lấy vào Source Path , chọn nơi lưu vào Destination Path, đặt tên tệp tùy ý vào Name <br>
 ![](https://i.imgur.com/94uzh1V.jpg)
**Đẩy code lên( push code )**<br>
-Đây là việc cần thiết khi có sự thay đổi trong source code, trước khi push được bắt buộc phải click vào unstaged files và comment -> click vào push trên toolbar của source tree. Việc làm này phải được thực hiện thường xuyên khi có sự thay đổi về code để người quản lý có thể quản lý được công việc cũng như là các thành viên khác có thể nắm bắt được sự thay đổi.<br>
![](https://i.imgur.com/oAtO37v.jpg)<br><br>
**Kéo code về( pull code )**<br>
-Cũng giống như Push code lên tuy nhiên việc bây giờ chỉ là lấy code về bao gồm những thay đổi mà thành viên khác đã push lên. Bạn chỉ cần click vào Pull ở trên toolbar của source tree<br>
![](https://i.imgur.com/ab3g1Ha.jpg)<br><br>
 
 
