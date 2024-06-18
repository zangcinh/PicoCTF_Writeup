# Overview #
`10 points`

# Description #
Files can always be changed in a secret way. Can you find the flag? cat.jpg

# Tiếp cận #
Sử dụng [hexeditor](https://hexed.it/) để kiểm tra
......JFIF......
.......0Photosho
p 3.0.8BIM......
....t..PicoCTF..
..........

http:/
/ns.adobe.com/xa
p/1.0/.<?xpacket
begin='...' id=
'W5M0MpCehiHzreS
zNTczkc9d'?>.<x:
xmpmeta xmlns:x=
'adobe:ns:meta/'
x:xmptk='Image:
:ExifTool 10.80'
>.<rdf:RDF xmlns
:rdf='http://www
.w3.org/1999/02/
22-rdf-syntax-ns
#'>.. <rdf:Descr
iption rdf:about
=''.  xmlns:cc='
http://creativec
ommons.org/ns#'>
.  <cc:license r
df:resource='cGl
jb0NURnt0aGVfbTN
0YWRhdGFfMXNfbW9
kaWZpZWR9'/>. </
rdf:Description>
.. <rdf:Descript
ion rdf:about=''
.  xmlns:dc='htt
p://purl.org/dc/
elements/1.1/'>.
 <dc:rights>.
<rdf:Alt>.    <
rdf:li xml:lang=
'x-default'>Pico
CTF</rdf:li>.
</rdf:Alt>.  </d
c:rights>. </rdf
:Description>.</
rdf:RDF>.</x:xmp
meta>.

Ta thấy 2 đoạn mã trông giống dạng base64 `W5M0MpCehiHzreSzNTczkc9d` và `cGljb0NURnt0aGVfbTN0YWRhdGFfMXNfbW9kaWZpZWR9`

Decode bằng [base64](https://www.base64decode.org/) ta được picoCTF{the_m3tadata_1s_modified}
