# Overview #
`easy`

# Description #
We found this packet capture. Recover the flag.

# Writeup #
Đầu tiên ta kiểm tra protocol hierachy 
![image](https://github.com/zangcinh/PicoCTF_Writeup/assets/173159694/140ba2eb-374a-47c3-a591-2412c7baa287)

Ta thấy data ở version 6 và 4 có sự khác nhau -> apply as filter
![image](https://github.com/zangcinh/PicoCTF_Writeup/assets/173159694/67e93d35-8192-4f79-b547-2474462488f7)

Follow UDP và kiểm tra các giao thức
Ở giao thức 6 xuất hiện flag

![image](https://github.com/zangcinh/PicoCTF_Writeup/assets/173159694/71e81059-f526-438f-8107-8f1dae056956)
