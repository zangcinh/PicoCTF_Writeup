# Overview #
`Medium`

# Description #
Can you find the flag? shark2.pcapng.

# Writeup #
Đầu tiên ta sẽ xem xét Protocol Hierachy 
Có 2 cái cần chú ý là HTP và DNS
Đầu tiên ta sẽ xem xét HTP 
Khi kiểm tra TCP Stream, ta thấy có dòng picoCTF nhưng nội dung lại thay đổi mỗi theo mỗi stream

![image](https://github.com/zangcinh/PicoCTF_Writeup/assets/173159694/6939c1b5-6631-40da-a793-4965e82648c8)

Kiểm tra DNS
Ở mục info, ta để ý sub domain trước reddshrimp là dạng 
