# Overview #
`100 points`

# Description #
We found this weird message being passed around on the servers, we think we have a working decryption scheme.
Download the message here.
Take each number mod 37 and map it to the following character set: 0-25 is the alphabet (uppercase), 26-35 are the decimal digits, and 36 is an underscore.
Wrap your decrypted message in the picoCTF flag format (i.e. picoCTF{decrypted_message})

# Tiếp cận #
Lấy mỗi số trong đoạn mã mod 37 theo set : 0-25 chữ cái thường, 26-35 là số, 36 là dâu gạch dưới

![image](https://github.com/hgiang20/PicoCTF_Writeup/assets/130575510/41d37d8e-80ed-4a54-8812-efc71c1d778c)

-> picoCTF{R0UND_N_R0UND_79C18FB3}
