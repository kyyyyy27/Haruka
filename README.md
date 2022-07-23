## COMMAND UPLOAD 
1. pkg install git
2. termux-setup-storage 
3. cd /sdcard
4. cd nama script

> Contoh: `cd Haruka`

5. rm -rf .git
5. git config --global user.email "email github"

> Contoh: `git config --global user.email "zeeoneofc@gmail.com"`

6. git config --global user.name "username github"

> Contoh: `git config --global user.name "zeeoneofc"`

8. git init
9. git config --global --add safe.directory /storage/emulated/0/Nama script 

> Contoh: `git config --global --add safe.directory /storage/emulated/0/Haruka`

10. git add .
11. git branch -m "nama branch"

> Contoh: `git branch -m "v1"`

12. git commit -m "Isi apa aja"

> Contoh: `git commit -m "Tes upload"

13. git remote add origin link repo

> Contoh: `git remote add origin https://github.com/zeeone-ofc/Haruka`

14. git push origin nama branch (nomor 11)

> Contoh: `git push origin v1`

> username: username github lu
> password: [github token](https://github.com/settings/tokens)
