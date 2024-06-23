# Overview #
`100points`

# Description #
Fix the syntax error in this Python script to print the flag. Download Python script

# Writeup #
Có một vài điểm trong code ban đầu mà cần được điều chỉnh để chương trình hoạt động đúng
1.Xử lý mã hóa XOR:

    Hàm str_xor(secret, key) trong code ban đầu có một vài vấn đề. Cụ thể là nó lặp lại từng ký tự của key để tạo ra new_key có độ dài bằng secret. Tuy nhiên, việc này không cần thiết vì Python có thể tự lặp lại key khi chúng ta sử dụng phép toán zip trên hai chuỗi có độ dài khác nhau.

2.Xử lý chuỗi flag_enc:

    flag_enc trong code ban đầu được biểu diễn như một danh sách các ký tự. Thay vì biểu diễn như vậy, chúng ta nên đại diện nó dưới dạng một chuỗi ký tự để có thể sử dụng hàm str_xor một cách chính xác.

3.Giải mã và in ra flag:

    Sau khi giải mã được flag_enc sử dụng str_xor và key là 'enkidu', chúng ta cần in ra kết quả dưới dạng một chuỗi văn bản thông thường, chứ không phải in ra từng phần tử trong danh sách flag_enc.
Code đã sửa lại như sau
![image](https://github.com/zangcinh/PicoCTF_Writeup/assets/173159694/4c7fb7c8-1dda-4677-bbcc-946cadffd3e1)
