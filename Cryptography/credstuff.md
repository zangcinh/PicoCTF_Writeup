# Overview #
`100 points`

# Description #
We found a leak of a blackmarket website's login credentials. Can you find the password of the user cultiris and successfully decrypt it?
Download the leak here.
The first user in usernames.txt corresponds to the first password in passwords.txt. The second user corresponds to the second password, and so on.

# Tiếp cận #
Để tìm password tương ứng với username `cultiris` ta đánh dấu số thứ tự từng dòng ( sử dụng tiện ích đánh số trên word hoặc gg tài liệu )
![image](https://github.com/hgiang20/PicoCTF_Writeup/assets/130575510/61a368ba-8232-4d98-804c-5f2216ba650e)

Username ở dòng 378 , tương ứng password dòng 378 : cvpbPGS{P7e1S_54I35_71Z3}
Ta decode bằng [Affine Cipher](https://www.dcode.fr/affine-cipher)

Flag 	picoCTF{C7r1F_54V35_71M3}
