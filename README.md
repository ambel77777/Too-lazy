how to push
fork repo dulu ygy
git init
git clone link repo
code .
kerjakan bagianmu
git add file yang kamu ubah
if file tidak ada cd dulu ke folder repo nya
git commit -m "aku sudah kerja"
git remote add origin link repo
git push

warning!!!! 
pastikan akun github nya sudah kamu ganti
jika nyangkut sama akun lain ke control panel terus search credential manager hapus akun github orang lain
gl gl yall

How to solve this problem of "! [rejected] master -> master (fetch first)"

First Do this ...

git fetch origin master
git merge  master

Then, do this ...

git fetch origin master:tmp
git rebase tmp
git push origin HEAD:master
git branch -D tmp

kalau yang error nya main yah ganti jadi main kocak

