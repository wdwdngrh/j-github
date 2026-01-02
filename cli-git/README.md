<<<<<<< HEAD
# git status

Perintah `git status` digunakan untuk melihat kondisi (status) repository Git saat ini. Hal yang bisa diketahui:
1. File yang sudah diubah (modified) \
   File yang isinya berubah tapi belum di-stage 
3. File yang sudah di-stage (staged) \
   File yang siap di-commit
5. File baru (untracked) \
   File yang belum pernah dimasukkan ke Git
7. Branch yang sedang aktif \
   Termasuk info apakah branch kamu tertinggal atau lebih maju dari remote
```
git status
```

---
# first commit ke repo kosong

```
git init
```

---
# commit ke repo yang sudah ada isi agar tidak konflik

```
git branch
```

=======
# buat repo baru
```
echo "# priv" >> README.md
git init
git add README.md
git commit -m "first commit"
git branch -M main
git remote add origin https://github.com/wdwdngrh/priv.git
git push -u origin main
```

===
# push repo yang sudah ada
```
git remote add origin https://github.com/wdwdngrh/priv.git
git branch -M main
git push -u origin main
```
