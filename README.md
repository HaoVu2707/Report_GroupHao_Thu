# Report_GroupHao_Thu
This is the report  our group
**Cách sử dụng .gitignore**
*.gitignore là gì ?*
-Tình huống là: Bạn làm việc theo nhóm, bạn muốn sử dụng git để quản lý mã nguồn.Tuy nhiên, dự án của bạn sẽ sinh ra những file build, gen, config, local, password, properties.Những file này thường là sẽ tự sinh và sẽ khác nhau tuỳ từng máy, khi đưa lên git thì khi người khác lấy về sẽ sinh ra xung đột (conflict) => gây cản trở cho công việc của bạn. Ngoài ra thì những file này thường rất nặng => tốn băng thông và tốn thời gian pull/push.Để giải quyết vấn đề này, git đưa ra .gitignore file.
-.gitignore là file định nghĩa những file, folder nào sẽ bị bỏ qua (ignore) và không thêm nó vào git. 
* Cách tạo file .gitignore*
-Đầu tiên mở terminal trong repository của bạn và gõ lệnh:
touch .gitignore
-Lúc này git sẽ tạo ra cho chúng ta 1 tệp tin là .gitignore,dùng notepad mở lên và khai báo các thư và mục tệp tin cần loại bỏ. 
Bạn có thể vào https://github.com/github/gitignore để tham khảo một số mẫu gitignore đã có sẵn của rất nhiều ngôn ngữ & framework (Chỉ việc copy về dùng, thay đổi nếu cảm thấy cần thiết).