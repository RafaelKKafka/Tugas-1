# Menghubungkan Git ke GitHub
## Persiapan
- Download dan install Visual Studio Code
- Download dan install Git
- Membuat akun GitHub
# Bash
- git config --global user.name "yourname"
- git config --global user.email "youremail@mail.com"
(harus sama dengan email yang terdaftar di GitHub)
- ssh-keygen -t ed25519 -C "youremail@mail.com"
- SSH key tersimpan di C:\Users \<username>\.ssh\id ed25519.pub
# GitHub
- Klik Profile Picture >Settings
- SSH and GPG keys >New SSH key
- Paste semua isi file id ed25519.pub ke bagian Key >Add SSH key
# Check di Bash
- ssh -T git@github.com
- Ketik yes
---
## ![Image Link](https://github.com/RafaelKKafka/Tugas-1/blob/main/Images/LLL.jpg)