# Kriptografi Pertemuan 11


## Profil
| #               | Biodata                      |
| --------------- | ---------------------------- |
| **Nama**        | M. AKMAL AL ABDILAH          |
| **NIM**         | 312110034                    |
| **Kelas**       | TI.21.A.1                    |
| **Mata Kuliah** | Kriptografi                  |




<hr>

<p align="center">
 <img src="https://user-images.githubusercontent.com/91085882/137566814-9c8c078c-1c3e-475c-b23d-7f4922f74beb.gif"/>
</p>
<p align="center">
<a href="https://github.com/akmalabdilah"><img title="Author" src="https://img.shields.io/discord/102860784329052160?color=BLUE&label=M.%20AKMAL%20AL%20ABDILAH1&logo=GITHUB&logoColor=BLACK&style=plastic"></a>
<p align="center">



<hr>


<hr>

## Implementasi Stegano

<hr>

<p>

<h2>Fungsi OTP yg digunakan</h2>

<b>Fungsi untuk mengenkripsi teks menggunakan One-Time Pad (OTP)</b>

```py
def otp_encrypt(plain_text, key):
    encrypted_text = ''
    for i in range(len(plain_text)):
        char = plain_text[i]
        key_char = key[i % len(key)]
        encrypted_text += chr(ord(char) ^ ord(key_char))
    return encrypted_text
```

<p>Fungsi untuk mengonversi teks ke dalam bentuk biner</p>

```py
def text_to_binary(text):
    binary_data = ''.join(format(ord(char), '08b') for char in text)
    return binary_data
```


<h2>Foto Kode di Jupyter Notebook</h2>

![Gambar 1](screenshoot/1.png)
![Gambar 2](screenshoot/2.png)
![Gambar 3](screenshoot/3.png)

<p>
 sekian and selesai.
</p>

<div>
<h2 align="center">Thanks For Reading!!!</h2>
<div align="center">
<img src="https://user-images.githubusercontent.com/91085882/222731693-24383140-7623-4e7a-a528-6621380b7be8.gif">
